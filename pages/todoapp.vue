
<template>


<LayoutWrapper>
      <h1 class="page-title"> {{pageTitle}}</h1>
      <p>{{ greeting }} World</p>
      <p>{{ message }} </p>
</LayoutWrapper>

</template>


<script>

export default {
  data(){
    return{
      greeting: 'Hello',
      message: 'ToDoアプリ',
      pageTitle: 'ToDoアプリ',
    }
  }
}

</script>
