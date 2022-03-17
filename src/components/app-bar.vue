<template>
  <div>
    <nav class="nav_">
      <div class="container_">
        <h2 class="log">erickSocial</h2>
        <div class="search-bar">
          <i class="uil uil-search"></i>
          <input type="search" placeholder="Qidirish..." />
        </div>
        <div class="create">
          <label @click="doneFunction" class="btn_" for="crate-post">
            <v-icon :color="data.show ? 'red' : '#6B4CE6'">{{
              data.show ? "mdi-close" : "mdi-menu"
            }}</v-icon>
          </label>
          <div class="profile-photo">
            <img src="../assets/images/profile-1.jpg" alt="" />
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  props: {
    data: {
      type: Object,
      required: true,
    },
  },
  methods: {
    doneFunction() {
      this.$emit("onSave");
    },
  },
};
</script>
<style>
@import "../assets/style/style.css";
</style>
