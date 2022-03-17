<template>
  <div>
    <!-- navbar -->
    <div>
      <app-bar @onSave="showMenu" :data="menu"/>
    </div>
    <!-- main section -->
    <main class="main-section">
      <div class="container_">
        <div class="left"><left :data="menu"/></div>
        <div class="middle"><middle /></div>
        <div class="right"><right /></div>
      </div>
    </main>
  </div>
</template>
<script>
import appBar from "../components/app-bar.vue";
import Left from "../components/left.vue";
import Middle from "../components/middle.vue";
import Right from "../components/right.vue";
export default {
  components: { appBar, Left, Middle, Right },
  name: "Home",
  data() {
    return {
      menu:{
        show:true
      }
    };
  },
  methods:{
    showMenu(){
      this.menu.show=!this.menu.show
    }
  }
};
</script>
