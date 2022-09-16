<script setup lang="ts"></script>

<template>
  <div class="container">
    <div class="row">
      <div class="avatar">
        <img src="@/assets/img/avatar.png" />
      </div>
      <div class="nickname">
        <h1>Ninja <i class=""></i></h1>
      </div>
    </div>
    <div class="row button-containers">
      <a
        href="http://youtube.com/ninja?sub_confirmation=1"
        class="btn bg-white buttons"
        ><span class="fab fa-youtube"></span> <span>Ninja Gaming</span></a
      >
    </div>
  </div>
</template>
<style scoped>
.container {
  width: 100%;
  height: 100%;
}
.avatar {
  width: 150px;
  height: 150px;
  border-radius: 150px;
  margin: 20px auto;
}
.avatar img {
  width: 100%;
  height: auto;
  object-fit: cover;
}
.nickname {
  color: #fff;
}
.buttons {
  width: 100%;
  color: #000;
}
</style>
