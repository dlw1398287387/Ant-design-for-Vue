<template>
  <a-list>
    <a-list-item>
			文章
    </a-list-item>
  </a-list>
</template>

<script>
  import AList from 'ant-design-vue/es/list'
  import AListItem from 'ant-design-vue/es/list/Item'

  export default {
    name: "Article",
    components: {
      AList,
      AListItem
    }
  }
</script>

<style scoped>

</style>