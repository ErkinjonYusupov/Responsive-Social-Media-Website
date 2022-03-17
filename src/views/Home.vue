<template>
  <div>
    <!-- navbar -->
    <div>
      <app-bar />
    </div>
    <!-- main section -->
    <main class="main-section">
      <div class="container_">
        <div class="left"><left /></div>
        <div class="middle"><middle /></div>
        <div class="right"><right /></div>
      </div>
    </main>
    <div><theme /></div>
  </div>
</template>
<script>
import appBar from "../components/app-bar.vue";
import Left from "../components/left.vue";
import Middle from "../components/middle.vue";
import Right from "../components/right.vue";
import Theme from "../components/theme.vue";
export default {
  components: { appBar, Left, Middle, Right, Theme },
  name: "Home",
};
</script>

