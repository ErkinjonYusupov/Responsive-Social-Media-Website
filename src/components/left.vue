<template>
  <div>
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
      <a class="menu-item active">
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
        <!-- notification popup -->
        <div class="notifications-popup">
          <div>
            <div class="profile-photo">
              <img src="../assets/images/profile-2.jpg" alt="" />
            </div>
            <div class="notification-body">
              <b>Kake Benjamin </b> accepted your friend request
              <small class="text-muted">2 KUN OLDIN</small>
            </div>
          </div>
          <div>
            <div class="profile-photo">
              <img src="../assets/images/profile-3.jpg" alt="" />
            </div>
            <div class="notification-body">
              <b>Kake Benjamin </b> comented on your post
              <small class="text-muted">2 KUN OLDIN</small>
            </div>
          </div>
          <div>
            <div class="profile-photo">
              <img src="../assets/images/profile-5.jpg" alt="" />
            </div>
            <div class="notification-body">
              <b>Kake Benjamin </b> accepted your friend request
              <small class="text-muted">2 KUN OLDIN</small>
            </div>
          </div>
          <div>
            <div class="profile-photo">
              <img src="../assets/images/profile-6.jpg" alt="" />
            </div>
            <div class="notification-body">
              <b>Kake Benjamin </b> accepted your friend request
              <small class="text-muted">2 KUN OLDIN</small>
            </div>
          </div>
          <div>
            <div class="profile-photo">
              <img src="../assets/images/profile-7.jpg" alt="" />
            </div>
            <div class="notification-body">
              <b>Kake Benjamin </b> accepted your friend request
              <small class="text-muted">2 KUN OLDIN</small>
            </div>
          </div>
        </div>
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
      <a class="menu-item">
        <span><i class="uil uil-palette"></i></span>
        <h3>Temalar</h3>
      </a>
      <a class="menu-item active">
        <span><i class="uil uil-setting"></i></span>
        <h3>Sozlamalar</h3>
      </a>
    </div>
    <!-- end of sidebar -->
    <label for="create-post" class="btn btn-primary">Post yaratish</label>
  </div>
</template>

<script>

export default {
  name: "left",
  data() {
    return {
      menu_items: [
        { icon: "mdi-home-outline", title: "Bosh sahifa", active: true },
        { icon: "mdi-compass-outline", title: "Explore", active: false },
        { icon: "mdi-bell-outline", title: "Bildirishnomalar", active: false },
        { icon: "mdi-email-open-outline", title: "Xabarlar", active: false },
        { icon: "mdi-bookmark-outline", title: "Xaridlar", active: false },
        { icon: "mdi-google-analytics", title: "Analitika", active: false },
        { icon: "mdi-format-line-style", title: "Temalar", active: false },
        { icon: "mdi-cog-outline", title: "Sozlamalar", active: false },
      ],
    };
  },
  mounted(){

  },
  methods:{
    
  }
};
</script>
