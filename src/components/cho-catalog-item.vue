<template>
  <div class="cho-catalog-item">
    <p>Item 1</p>
    <p>Price: 1000</p>
    <button>Add to cart</button>
  </div>
</template>

<script>

  export default {
    name: 'cho-catalog-item',
    components: {},
    props: {},
    data() {
      return {}
    },
    computed: {},
    methods: {},
    watch: {}
  }
</script>

<style lang="scss">
  .cho-catalog-item {
    flex-basis: 25%;
    box-shadow: 0 0 8px 0 #e0e0e0;
    padding: $padding;
    margin-bottom: $margin;
  }
</style>
