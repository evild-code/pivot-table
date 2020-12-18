<template>
  <div id="app">
    <TestPivotTable></TestPivotTable>
  </div>
</template>

<script>
import TestPivotTable from "./example";

export default {
  name: "App",
  components: {
    TestPivotTable
  },
  data() {
    return {};
  },
  methods: {}
};
</script>

<style lang="scss">
#app {
  height: 100%;
}
* {
  margin: 0;
  padding: 0;
}
html,
body {
  height: 100%;
}
</style>
