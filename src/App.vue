<template>
  <h1>{{ message }}</h1>
  <HelloWorld />
</template>

<script>
import HelloWorld from '~/components/HelloWorld'
export default{
  components: {
    HelloWorld
  },
  data() {
    return {
      message: 'Hello Vue!!!' // 객체 리터럴 반환
    }
  }
}
</script>
