<template>
  <div class="pink">
    <h1>夏株奕爱{{message}}</h1>
  </div>
</template>

<script>
  export default {
    name: 'test',
    props: {
      message: {
        type: String,
        default: "颜燕"
      }
    },
    methods: {

    },
    data() {
      return {
        // message: 'yy'
      }
    }
  }
</script>

<style>
  .pink {
    color: antiquewhite;
    font-size: 15px;
  }
</style>
