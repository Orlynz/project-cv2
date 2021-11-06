<template>
  <div id="app" class="container">
    <div class="row py-4">
      <project-1 />
    </div>
    <br /><br />
    <div>
      <project-2 />
    </div>
  </div>
</template>

<script>
import Project1 from "./components/Project1.vue";
import Project2 from "./components/Project2.vue";

export default {
  name: "app",
  components: {
    Project1,
    Project2,
  },
};
</script>