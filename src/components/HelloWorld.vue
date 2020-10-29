<template>
  <div class="hello">
    <h5 class="head">{{ about1 }}</h5>
    <h5>{{ about2 }}</h5>
    <h5>{{ about3 }}</h5>
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
    <a href="https://www.instagram.com/vins_caresidoarjo/" class="btn btn-warning">Follow Us</a>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      about1: "Vin's Care, Kami bergerak dalam bidang ",
      about2: 'pelayanan jasa perawatan sepatu yang',
      about3: 'berlokasi di Sidoarjo, Jawa Timur sob.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h5.head{
  font-weight: normal;
  margin-top: 20px;
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
