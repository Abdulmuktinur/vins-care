<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h5>{{ about1 }}</h5>
    <h5>{{ about2 }}</h5>
    <h4>Pelayanan</h4>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
        >
          Fast Clean
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          Deep Clean
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          Unyellowing
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          Recoloring
        </a>
      </li>
    </ul>
    <button class="btn btn-warning">Follow Us</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: "Welcome to Vin's Care",
      about1: "Vin's Care, Kami bergerak dalam bidang pelayanan jasa",
      about2: 'perawatan sepatu yang berlokasi di Sidoarjo, Jawa Timur sob.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  margin-top: 10px;
}
h4{
  font-weight: bold;
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
  color: #000000;
}
</style>
