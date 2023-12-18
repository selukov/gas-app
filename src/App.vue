<template>
  <div>Hello {{ name }}!</div>
  <p>{{ sex }}</p>
</template>

<script>
export default {
  data() {
    return {
      name: "Vue",
      sex: "Some new text555 here",
    };
  },
};
</script>
