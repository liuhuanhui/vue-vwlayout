<template>
  <div class="homepage">
    <div class="box"></div>
    <hr>
    <div w-100-100 aspectratio>
      <div class="aspectratio-content">
        hello
      </div>
    </div>
    <hr>
    <div class="aspectratio1">
      <div class="aspectratio-content1">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}

[w-100-100] {
  border: 1px solid red;

  width: 100px;
}

[w-100-100] {
  aspect-ratio: '200:200';
}

.box {
  width: 100px;
  height: 100px;
  border: 1px solid red;
}
</style>
