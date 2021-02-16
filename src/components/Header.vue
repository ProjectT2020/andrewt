<template>
        <nav>
            <ul>
                <li id="current"><a href="index.html">Home</a></li>
                <li id="nav-blog"><a href="blog/index.html">Blog</a></li>
                <li id="nav-ip"><a href="http://8.131.95.69:3000/foo/bar">你的IP</a></li>
                <li id="nav-distance"><a href="distance.html">我们的距离</a></li>
                <li id="nav-history"><a href="./2021年2月12日index.html">往期主页</a></li>
                <li id="nav-about"><a href="about.html">About</a></li>
            </ul>
        </nav>
</template>

<script>
export default {
  name: 'Header',
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

