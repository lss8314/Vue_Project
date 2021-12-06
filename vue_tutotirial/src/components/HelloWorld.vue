<template>

  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      {한글도 가능하게해야지,}<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Google</h3>
    <ul>
      <li><a href="https://www.Google.com" target="_blank" rel="noopener">Google</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">googleMail</a></li>
    </ul>
    <h3>Naver</h3>
    <ul>
      <li><a href="https://www.naver.com" target="_blank" rel="noopener">Naver</a></li>
      <li><a href="https://www.wowtv.co.kr/NewsCenter/Main/Index?menuSeq=458" target="_blank" rel="noopener">NaverNews</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">NaverEncyclopedia</a></li>
    </ul>
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
