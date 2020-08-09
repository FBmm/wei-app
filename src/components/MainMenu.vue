<template>
  <div class="main-menu__container">
    <i-row>
      <i-col span="6" i-class="main-menu-left">
        <i-icon type="other" size="18"></i-icon>
      </i-col>
      <i-col span="12" i-class="main-menu-list">
        <span class="main-menu-list__item">我的</span>
        <span class="main-menu-list__item">发现</span>
        <span class="main-menu-list__item">云村</span>
        <span class="main-menu-list__item">视频</span>
      </i-col>
      <i-col span="6" i-class="main-menu-right">
        <i-icon type="search" size="18"></i-icon>
      </i-col>
    </i-row>
  </div>
</template>

<script>
export default {};
</script>

<style>
.main-menu-left {
  padding: 0 10px;
}
.main-menu-right {
  padding: 0 10px;
  text-align: right;
}
.main-menu-list {
  display: flex !important;
  justify-content: space-between;
}
</style>
