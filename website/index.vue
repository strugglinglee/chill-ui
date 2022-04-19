<template>
  <div class="app">
    hello,chill ui
    <button></button>
  </div>
</template>

<script>
import { onMounted } from 'vue'
import {button} from '../packages/index'
export default{
  name: 'app',
  components:{
  },
  setup(){
      onMounted(()=>{
          console.log(button,'gugugugu')
      })
  }
}
</script>