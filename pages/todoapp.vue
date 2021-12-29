<template>
  <LayoutWrapper>
    <h1 class="page-title"> {{pageTitle}}</h1>
    <AppMenuArea />
    <div class="todo-app">
      <textarea v-model="message"></textarea>
      <p>{{ message }}</p>
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
      pageTitle: 'ToDoアプリ',
      message: 'message',
    }
  }
}
</script>
<style lang="scss">
  textarea{
    width: 500px;
    padding: 20px;
    border: solid 1px #888;
  }
  .todo-app{
    p{
      font-size: 50px !important;
    }
  }
</style>
