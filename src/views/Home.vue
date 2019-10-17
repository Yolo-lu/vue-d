<template>
  <div>
    <ChildSlot>插入的内容
      <div slot="aa">我要插入到子组件</div>
    </ChildSlot>
  </div>

</template>

<script>
  import ChildSlot from '../components/Child-slot'
  export default {
    name: "AboutSlot",
    components: {
      ChildSlot
    },
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
