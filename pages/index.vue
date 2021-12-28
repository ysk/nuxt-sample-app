<template>

  <div class="wapper">
  <HeaderArea />
  <MenuArea />
  <FooterArea />
  </div>

</template>


<script>
// @ is an alias to /src
import HeaderArea from '@/components/modules/HeaderArea.vue'
import FooterArea from '@/components/modules/FooterArea.vue'
import MenuArea from '@/components/modules/MenuArea.vue'

export default {
  components: {
    HeaderArea,
    FooterArea,
    MenuArea,
  }
}
</script>