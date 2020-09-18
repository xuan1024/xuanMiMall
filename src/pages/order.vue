<template>
    <div>
      
      <order-header></order-header>
      <router-view></router-view>
      <nav-footer></nav-footer>
      order  
    </div>
</template>
<script>
import orderHeader from './../components/OrderHeader'
import navFooter from './../components/NavFooter'
export default {
    name: 'order',
    components:{orderHeader,navFooter}
    
    
    
}
</script>