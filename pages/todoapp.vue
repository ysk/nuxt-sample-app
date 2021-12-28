
<template>

  <div class="wapper">

    <HeaderArea />
    <MenuArea />

    <div class="content">
      <h1> ToDoアプリページ</h1>
      <p>{{ greeting }} World</p>
      <p>{{ message }} </p>
    </div>
    <FooterArea />
  </div>

</template>


<script>
// @ is an alias to /src
import HeaderArea from '@/components/modules/HeaderArea.vue'
import FooterArea from '@/components/modules/FooterArea.vue'

export default {
  data(){
    return{
      greeting: 'Hello',
      message: 'ToDoアプリ'
    }
  },
  components: {
    HeaderArea,
    FooterArea
  }
}

</script>
