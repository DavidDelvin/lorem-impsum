<template>
  <div id="app">
    <Header/>
    <IpsumForm/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import IpsumForm from "@/components/IpsumForm";

export default {
  name: "app",
  components: {
    Header,
    IpsumForm
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html,
body {
  background: #333;
  color: #fff;
  height: 100vh;
  width: 100vw;
  font-family: sans-serif;
  text-align: center;
}

a {
  color: #fff;
  text-decoration: none;
}

#app {
}
</style>
