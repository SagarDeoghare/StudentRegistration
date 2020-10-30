<template>
  <v-container>
    {{msg}}
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({

  }),

  props: {
    msg: ''
  }
};
</script>
