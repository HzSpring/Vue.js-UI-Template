<template>
  <h1
    class="font-weight-thin display-2 text-center text-md-right white--text d-flex align-center justify-center flex-column flex-md-row"
  >
    <strong class="mt-12 grey darken-4 ps-3 pr-3">{{ header_text_one }}</strong>
    <span class="mt-12 white--text ps-3 pr-3">{{ header_text_two }}</span>
  </h1>
</template>

<script>
export default {
  name: "Header",
  props: {
    header_text_one: {
      type: String,
    },
    header_text_two: {
      type: String,
    },
  },
};
</script>

<style lang="scss" scoped>
$header-background-color: #26267454;

h1 {
  height: 100%;
  background-color: $header-background-color;
}

span {
  background-color: $header-background-color;
}
</style>
