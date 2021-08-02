<template>
  <div>
    <router-link to="/">HOME</router-link>
    <router-link to="/menu">Menu</router-link>
    <router-link to="/login">Log in</router-link>
    <router-link to="/signup">Sign up</router-link>
    <router-link to="/mypage">Mypage</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  margin: 0;
  font-family: "Trebuchet MS", Verdana, sans-serif;
}
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-between;
  width: 100%;
  height: 100%;
}
.menu_area {
  width: 350px;
  padding: 40px;
  background: #000000;
  height: 100vh;
}
.menu_area .logo_area {
  margin: 30px 150px 30px 0;
  text-align: center;
  font-size: 40px;
  font-weight: 1000;
  border-bottom: 5px solid #d9d9dc;
  text-align: left;
}
.menu_area .logo_area .logo_title {
  margin: 15px 0;
}
.title_area {
  margin: 60px 0;
}
.title_area .menu_title_area {
  font-size: 18px;
  font-weight: bold;
  width: 100%;
  border-bottom: 1px solid #d9d9dc;
  color: #434343;
  text-align: left;
}
.title_area .menu_title_area .menu_title {
  margin: 15px 0 20px 0;
}
a {
  text-decoration: none;
}
a:hover {
  color: #eb8888;
}
.content_area {
  padding: 50px;
}
</style>
