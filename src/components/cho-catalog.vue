<template>
  <div class="cho-catalog">
    <h1>Im a catalog</h1>
    <cho-catalog-item />
  </div>
</template>

<script type="text/javascript">
import choCatalogItem from './cho-catalog-item'

  export default {
    name: 'cho-catalog',
    components: {
      choCatalogItem
    },
    props: {},
    data() {
      return {}
    },
    computed: {},
    methods: {},
    watch: {},
    mounted() {
      console.log('Hello world!')
    }
  }
</script>

<style lang="scss">
  .cho-catalog {
    &_list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
    }
  }
</style>
