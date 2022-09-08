<template>
  <div v-html="htmlString"></div>
</template>

<script>
export default {
  name: 'IndexPage',
  computed: {
    htmlString: function () {
      return "<a href=\"/relative/path/to/website\">Click here!</a>"
    }
  }
}
</script>
