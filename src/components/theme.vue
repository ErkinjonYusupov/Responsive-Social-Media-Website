<template>
  <div class="customize-theme">
    <div class="card">
      <h2>Sahifa ko'rinishi</h2>
      <p class="text-muted">Sahifa ko'rinishi va rangini tahrirlang</p>
      <!-- ===========font sizes=========== -->
      <div class="font-size">
        <h4>Shrift o'lchamlari</h4>
        <div>
          <h6>Aa</h6>
          <div class="choose-size">
            <span class="font-size-1"></span>
            <span class="font-size-2 active"></span>
            <span class="font-size-3"></span>
            <span class="font-size-4"></span>
            <span class="font-size-5"></span>
          </div>
          <h3>Aa</h3>
        </div>
      </div>
      <!-- ===========colors=========== -->
      <div class="color">
        <h4>Ranglar</h4>
        <div class="choose-color">
          <span class="color-1 active"></span>
          <span class="color-2"></span>
          <span class="color-3"></span>
          <span class="color-4"></span>
          <span class="color-5"></span>
        </div>
      </div>
      <!-- ===========background colors=========== -->
      <div class="background">
        <h4>Orqa fon</h4>
        <div class="choose-bg">
          <div class="bg-1 active">
            <span></span>
            <h5 for="bg-1">Kungi rejim</h5>
          </div>
          <div class="bg-2">
            <span></span>
            <h5 for="bg-2">Aralash</h5>
          </div>
          <div class="bg-3">
            <span></span>
            <h5 for="bg-3">Tungi rejim</h5>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "theme",
};
</script>

