<template>
  <div class="login">
    <ul :class="[{ loading: loading }, 'bg-bubbles']">
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
    <div class="container">
      <nuxt/>
    </div>
  </div>
</template>


<script>
  export default {
    data () {
      return {
        loading: false,
      };
    },
    mounted () {
      console.log(this);
    },
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-weight: 300;
  }

  body {
    font-family: 'Source Sans Pro', sans-serif;
    color: white;
    font-weight: 300;
  }
    ::-webkit-input-placeholder {
      /* WebKit browsers */
      font-family: 'Source Sans Pro', sans-serif;
      color: white;
      font-weight: 300;
    }
    :-moz-placeholder {
      /* Mozilla Firefox 4 to 18 */
      font-family: 'Source Sans Pro', sans-serif;
      color: white;
      opacity: 1;
      font-weight: 300;
    }
    ::-moz-placeholder {
      /* Mozilla Firefox 19+ */
      font-family: 'Source Sans Pro', sans-serif;
      color: white;
      opacity: 1;
      font-weight: 300;
    }
    :-ms-input-placeholder {
      /* Internet Explorer 10+ */
      font-family: 'Source Sans Pro', sans-serif;
      color: white;
      font-weight: 300;
    }
</style>
