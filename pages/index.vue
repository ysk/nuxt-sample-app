<template>
  <LayoutWrapper>
    <h1 class="page-title"> {{pageTitle}}</h1>
    <nav class="nav">
      <ul class="app-list">
        <li class="app-list-item"><a href="/todoapp/">ToDoアプリ</a></li>
      </ul>
    </nav>
  </LayoutWrapper>
</template>


<script>

export default {
  data(){
    return{
      pageTitle: 'サンプルアプリ一覧',
    }
  }
}
</script>