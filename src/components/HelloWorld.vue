<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div id="aa">
      sdklguhdlfjkgnsdklfjkhsdfsdklguhdlfjkgnsdklfjkhsd fsdklguhdlfjkgnsdklfjkh
      sdfsdklguhdlfjkgnsdklfjkhsdf
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="less">
#aa {
  width: 50px;
  height: 50px;
  overflow: scroll;
  .scrollbar-show();
}
</style>
