<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class="logo" src="./assets/build-a-bot-logo.png"/>
            Build-a-Bot
            </li>
        </ul>

      </nav>
    </header>
    <main>
      <RobotBuilder/>
    </main>
  </div>
</template>

<script>
import RobotBuilder from './build/RobotBuilder.vue';
export default {
  name: 'app',
  components: {
    RobotBuilder,
  },
};
</script>

<style>
body {
  background: linear-gradient(to bottom, rgb(16, 3, 73), rgb(24, 71, 133));
  background-attachment: fixed;
}
main {
margin: 0 auto;
padding: 30px;
background-color: antiquewhite;
width: 1024px;
min-height: 300px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}
header {
background-color: white;
width: 1084px;
margin: 0 auto;
}
ul{
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo{
  vertical-align: middle;
  height: 30px;
}
</style>
