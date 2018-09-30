<template>
  <div class="about">
    <h1>关于我们</h1>
     <router-link to="/info">info</router-link>
     <router-view></router-view>
  </div>
</template>
<script>
export default {
 data () {
 return {

 };
 },

 components: {},

 computed: {},

 mounted() {},

 methods: {
   toinfo(){
     $router.push
   }
 }
}

</script>
<style scoped'>
</style>

