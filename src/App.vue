<template>
  <div id="app">
    <router-view/>
  </div>
</template>
<script>

export default {
  data(){
    return{
      res:{}
    }

  },
  mounted(){
   this.axios.get('/user/login').then((res)=>{
      this.res = res;
    });
  }
}
</script>
<style lang="scss">
@import './assets/scss/reset.scss';
@import './assets/scss/config.scss';
@import './assets/scss/button.scss';


</style>
