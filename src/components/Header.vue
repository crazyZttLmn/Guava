<template>
<div class="">
  <div slot="header" class="h_wrap">
    <div class="header clr">
      <h1 class="fl">
              <a href="/#">网易云音乐</a>
          </h1>
      <ul class="fl nav_list">
        <li><a href="#" class="n_active"><span>发现音乐</span><i class="n_tip"></i></a></li>
        <li><a href="#">我的音乐</a></li>
        <li><a href="#"><span>朋友</span><i class="n_dot"></i></a></li>
        <li><a href="#">商城</a></li>
        <li><a href="#">音乐人</a></li>
        <li><a href="#"><span>下载客户端</span><i class="n_hot"></i></a></a>
        </li>
      </ul>
      <div class="fr btn_login">
        <el-dropdown>
          <span class="el-dropdown-link">登录<i class="el-icon-arrow-down el-icon--right"></i></span>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>手机号登录</el-dropdown-item>
            <el-dropdown-item>微信登录</el-dropdown-item>
            <el-dropdown-item>QQ登录</el-dropdown-item>
            <el-dropdown-item>新浪微博登录</el-dropdown-item>
            <el-dropdown-item>网易邮箱帐号登录</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
      </div>
      <div class="fr">
        <a href="#" class="v_sub">视频投稿</a>
      </div>
      <div class="fr s_bg">
        <input type="text" name="" value="" placeholder="音乐/电台/用户" />
      </div>
    </div>
  </div>
  <div class="b_bar">
    <ul>
      <li></li>
    </ul>
  </div>
</div>
</template>

<script>
export default {
  data() {
    return {
      activeIndex: '1',
      activeIndex2: '1'
    };
  },
  methods: {
    handleSelect(key, keyPath) {
      console.log(key, keyPath);
    }
  }
}
</script>
