<template>
  <Layout>
    <h1 v-html="$context.title"></h1>
    <h2 v-html="$context.author"></h2>
    <div v-html="$context.content"></div>
  </Layout>
</template>

<script>
export default {
  metaInfo: function () {
    return {
      title: this.$context.title
    }
  }
}
</script>