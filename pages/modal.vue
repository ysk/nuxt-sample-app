<template>
  <LayoutWrapper>
    <h1 class="page-title"> {{pageTitle}}</h1>
    <AppMenuArea />
    <div class="modal-app">
      モーダルウィンドウ
    </div>
  </LayoutWrapper>
</template>

<script>
import AppMenuArea from '@/components/modules/AppMenuArea.vue'
export default {
  components: {
    AppMenuArea
  },
  data(){
    return{
      pageTitle: 'モーダルウィンドウ',
    }
  }
}
</script>
<style lang="scss">

</style>
