<template>

  <div class="wapper">
    <HeaderArea />
      <div class="content">
        <slot />
      </div>
    <FooterArea />
  </div>
</template>

<script>
import HeaderArea from '@/components/modules/HeaderArea.vue'
import FooterArea from '@/components/modules/FooterArea.vue'
import '@/assets/css/common.css'
export default {
  components: {
    HeaderArea,
    FooterArea,
  }
}
</script>
<style lang="scss">

</style>
