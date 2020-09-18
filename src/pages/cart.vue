<template>
    <div>
       
      <order-header></order-header>
     car
      <nav-footer></nav-footer>
    </div>
</template>
<script>
import orderHeader from './../components/OrderHeader'
import navFooter from './../components/NavFooter'
export default {
    name: 'order',
    components:{orderHeader, navFooter}
    
    
    
}
</script>