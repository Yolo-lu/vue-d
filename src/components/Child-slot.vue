<template>
  <div>
    子组件的内容
    <div><slot></slot></div>
    <div style="color: red"><slot name="ss">依旧是子组件</slot></div>
    <div><slot name="aa"></slot></div>
  </div>
  
</template>

<script>
  export default {
    name: "Child-slot",
    components: {},
    props: {},
    data() {
      return {}
    },
    methods: {},

    mounted() {

    },
    created() {

    },
    filters: {},
    computed: {},
    watch: {},
    directives: {}
  }
</script>

<style scoped lang="scss">

</style>