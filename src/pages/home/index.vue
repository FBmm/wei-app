<template>
  <div class="home__container">
    <div class="main-menu">
      <MainMenu></MainMenu>
    </div>
    <div class="home-banner">
      <div class="home-banner__img">
        <img src="/static/images/banner-1.jpg" alt="">
      </div>
    </div>
    <div class="home-menu">
      <div class="home-menu__icon">
        <i-icon type="task_fill" size="30"/>
      </div>
      <div class="home-menu__icon">
        <i-icon type="activity" size="30"/>
      </div>
      <div class="home-menu__icon">
        <i-icon type="service_fill" size="30"/>
      </div>
      <div class="home-menu__icon">
        <i-icon type="eit" size="30"/>
      </div>
      <div class="home-menu__icon">
        <i-icon type="eit" size="30"/>
      </div>
      <div class="home-menu__icon">
        <i-icon type="eit" size="30"/>
      </div>
      <div class="home-menu__icon">
        <i-icon type="eit" size="30"/>
      </div>
    </div>
    <div class="home-recommend-songs-list">
      <div class="home-recommend-songs-list__header">
        <span class="title">发现好歌单</span>
        <span class="more">查看更多</span>
      </div>
      <div class="home-recommend-songs-list__container">
        <div class="home-recommend-songs-list__card">
          <div class="bg">
            <img src="/static/images/song-list-bg_01.jpg" alt="">
          </div>
          <div class="title">柔软思绪｜躺在旋律的天鹅绒上放空</div>
        </div>
        <div class="home-recommend-songs-list__card">
          <div class="bg">
            <img src="/static/images/song-list-bg_01.jpg" alt="">
          </div>
          <div class="title">柔软思绪｜躺在旋律的天鹅绒上放空</div>
        </div>
        <div class="home-recommend-songs-list__card">
          <div class="bg">
            <img src="/static/images/song-list-bg_01.jpg" alt="">
          </div>
          <div class="title">柔软思绪｜躺在旋律的天鹅绒上放空</div>
        </div>
        <div class="home-recommend-songs-list__card">
          <div class="bg">
            <img src="/static/images/song-list-bg_01.jpg" alt="">
          </div>
          <div class="title">柔软思绪｜躺在旋律的天鹅绒上放空</div>
        </div>
        <div class="home-recommend-songs-list__card">
          <div class="bg">
            <img src="/static/images/song-list-bg_01.jpg" alt="">
          </div>
          <div class="title">柔软思绪｜躺在旋律的天鹅绒上放空</div>
        </div>
        <div class="home-recommend-songs-list__card">
          <div class="bg">
            <img src="/static/images/song-list-bg_01.jpg" alt="">
          </div>
          <div class="title">柔软思绪｜躺在旋律的天鹅绒上放空</div>
        </div>
      </div>
    </div>
    <div class="home-recommend-song-list">
      <div class="home-recommend-songs-list__header">
        <span class="title">清雅古风 惊艳时光</span>
        <span class="more">查看更多</span>
      </div>
      <div class="home-recommend-song-list__item">
        <div class="left">
          <img src="/static/images/song-list-bg_01.jpg" alt="">
        </div>
        <div class="right">
          <div class="title">每一片落叶都知你姓名</div>
          <div class="des">江山未老红颜旧</div>
        </div>
      </div>
      <div class="home-recommend-song-list__item">
        <div class="left">
          <img src="/static/images/song-list-bg_01.jpg" alt="">
        </div>
        <div class="right">
          <div class="title">每一片落叶都知你姓名</div>
          <div class="des">江山未老红颜旧</div>
        </div>
      </div>
      <div class="home-recommend-song-list__item">
        <div class="left">
          <img src="/static/images/song-list-bg_01.jpg" alt="">
        </div>
        <div class="right">
          <div class="title">每一片落叶都知你姓名</div>
          <div class="des">江山未老红颜旧</div>
        </div>
      </div>
      <div class="home-recommend-song-list__item">
        <div class="left">
          <img src="/static/images/song-list-bg_01.jpg" alt="">
        </div>
        <div class="right">
          <div class="title">每一片落叶都知你姓名</div>
          <div class="des">江山未老红颜旧</div>
        </div>
      </div>
      <div class="home-recommend-song-list__item">
        <div class="left">
          <img src="/static/images/song-list-bg_01.jpg" alt="">
        </div>
        <div class="right">
          <div class="title">每一片落叶都知你姓名</div>
          <div class="des">江山未老红颜旧</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MainMenu from '@/components/MainMenu'
export default {
  data () {
    return {}
  },

  components: { MainMenu },

  methods: {
    clickHandle (ev) {
      console.log('clickHandle:', ev)
    }
  },
}
</script>

<style scoped>
.ta_r {
  text-align: right;
}
.home__container {
  color: #7f7f7f;
  font-size: 16px;
}
.home-banner__img {
  height: 150px;
  margin: 10px;
}
.home-banner__img img {
  width: 100%;
  height: 100%;
  border-radius: 10px;
}
.home-menu {
  overflow-x: auto;
  white-space: nowrap;
  height: 60px;
}
.home-menu__icon {
  display: inline-block;
  width: 50px;
  height: 50px;
  background-color: #ff3629;
  border-radius: 50%;
  color: #fff;
  font-size: 30px;
  text-align: center;
  margin: 0 10px;
}
.home-recommend-songs-list {}

.home-recommend-songs-list__container {
  overflow-x: auto;
  white-space: nowrap;
}
.home-recommend-songs-list__header {
  display: flex;
  justify-content: space-between;
  padding: 10px;
}
.home-recommend-songs-list__header .title {
  font-size: 20px;
  color: #333;
}
.home-recommend-songs-list__header .more {
  border: 1px solid #ccc;
  border-radius: 15px;
  font-size: 12px;
  padding: 0 10px;
  color: #333;
  display: inline-block;
  height: 20px;
  line-height: 20px;
}
.home-recommend-songs-list__card {
  display: inline-block;
  margin: 0 10px;
}
.home-recommend-songs-list__card .title {
  font-size: 12px;
}
.home-recommend-songs-list__card .bg {
  width: 100px;
  height: 100px;
}
.home-recommend-songs-list__card .title {
  width: 100px;
  white-space:normal;
}
.home-recommend-songs-list__card .bg img {
  width: 100%;
  height: 100%;
  border-radius: 8px;
}
.home-recommend-song-list__item {
  height: 50px;
  display: flex;
  margin-bottom: 10px;
}
.home-recommend-song-list__item .left {
  width: 50px;
  height: 50px;
  padding: 0 10px;
}
.home-recommend-song-list__item .left img{
  width: 50px;
  height: 50px;
  border-radius: 8px;
}
.home-recommend-song-list__item .right {
  flex: 1;
}
.home-recommend-song-list__item .right .title {
  padding-top: 5px;
  color: #333;
}
.home-recommend-song-list__item .right .des {
  font-size: 12px;
  padding-top: 2px;
}
</style>
