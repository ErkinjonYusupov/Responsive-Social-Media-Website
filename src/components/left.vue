<template>
  <div v-if="data.show">
    <a href="" class="profile">
      <div class="profile-photo">
        <img src="../assets/images/profile-1.jpg" alt="" />
      </div>
      <div class="handle">
        <h4>Diana Ayi</h4>
        <p class="text-muted">@dayi</p>
      </div>
    </a>
    <!-- sidebar -->
    <div class="sidebar">
      <a class="menu-item">
        <span><i class="uil uil-home"></i></span>
        <h3>Bosh sahifa</h3>
      </a>
      <a class="menu-item">
        <span><i class="uil uil-compass"></i></span>
        <h3>Explore</h3>
      </a>
      <a class="menu-item" id="notifications">
        <span
          ><i class="uil uil-bell">
            <small class="notification-count">7+</small></i
          ></span
        >
        <h3>Bildirishnomalar</h3>
      </a>
      <a class="menu-item">
        <span
          ><i class="uil uil-envelope-alt"
            ><small class="notification-count">7</small></i
          ></span
        >
        <h3>Xabarlar</h3>
      </a>
      <a class="menu-item">
        <span><i class="uil uil-bookmark"></i></span>
        <h3>Haridlar</h3>
      </a>
      <a class="menu-item">
        <span><i class="uil uil-chart-line"></i></span>
        <h3>Analitika</h3>
      </a>
      <a @click="show_theme" class="menu-item">
        <span><i class="uil uil-palette"></i></span>
        <h3>Temalar</h3>
      </a>
      <a class="menu-item">
        <span><i class="uil uil-setting"></i></span>
        <h3>Sozlamalar</h3>
      </a>
    </div>
    <!-- end of sidebar -->
    <label for="create-post" class="btn btn-primary">Post yaratish</label>
    <theme-dialog ref="sidebar" />
  </div>
</template>

<script>
import themeDialog from "./theme/theme-dialog.vue";
export default {
  components: { themeDialog },
  name: "left",
  props: {
    data: {
      type: Object,
      required: true,
    },
  },
  data() {
    return {
      menu_dialog: true,
    };
  },
  methods: {
    show_theme() {
      this.$refs.sidebar.show();
    },
  },
};
</script>
