<template>
   <div class="hello">
   {{msg}}
   </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "../styles/varibles.scss";
.hello{
  font-size:$Primary-size;
  color:$fame-orange;
}


</style>
