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
// @ is an alias to /src

import HeaderArea from '@/components/modules/HeaderArea.vue'
import FooterArea from '@/components/modules/FooterArea.vue'

export default {
  components: {
    HeaderArea,
    FooterArea,
  }
}
</script>