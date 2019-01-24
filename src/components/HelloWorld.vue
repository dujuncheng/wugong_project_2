<template>
  <div class="hello">
    <h1>该页面用来实验缓存</h1>
    <h1>该页面JS/CSS资源，浏览器强缓存2分钟</h1>
    <h1>该页面HTML/JS/CSS资源，CDN缓存4分钟，协商缓存6分钟</h1>
    <h2>g该页面的缓存有两种方式控制: nginx 和 node静态资源服务，可以在后台进行配置 </h2>
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
