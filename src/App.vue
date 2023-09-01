<template>
  <NavigationMenu />
  <div class="dashboard p-3">
    <h2>DASHBOARD</h2>
  </div>
  <LeftMenu />
  <RightMenu/>
  <LeftMenu1 />
  <MiddleMenu />
  <LeftMenu2 />
</template>

<script>
import LeftMenu from "./components/LeftMenu.vue";
import NavigationMenu from "./components/NavigationMenu.vue";
import LeftMenu1 from "./components/LeftMenu1.vue";
import LeftMenu2 from "./components/LeftMenu2.vue";
import MiddleMenu from "./components/MiddleMenu.vue";
import RightMenu from "./components/RightMenu.vue";
export default {
  name: "App",
  components: {
    NavigationMenu,
    LeftMenu,
    LeftMenu1,
    LeftMenu2,
    MiddleMenu,
    RightMenu
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

}
.dashboard{
  color :#3f51b5;
}
</style>
