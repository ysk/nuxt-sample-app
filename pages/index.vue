<template>
  <LayoutWrapper>
    <h1 class="page-title"> {{pageTitle}}</h1>
    <AppMenuArea />
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
      pageTitle: 'サンプルアプリ一覧',
    }
  }
}
</script>
<style lang="scss">

</style>
