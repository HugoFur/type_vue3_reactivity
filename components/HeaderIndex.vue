<template>
  <div id="header">
    <div id="person">
      <img src="../assets/person.png" />
      <div id="welcome">
        <h1>
          <span> Hello {{ username }} !</span>
        </h1>
        <h3>Welcome</h3>
        <p>to my vue3 syntax test</p>
      </div>
    </div>
    <div id="inputName">
      <input v-model="username" placeholder=">" />
    </div>
  </div>
</template>

<style scoped>
div#header {
  display: flex;
  text-align: center;
  height: 100vh;
  flex-direction: column;
  align-items: center;
  background-color: #053cb11a;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  color: #000000;
}
</style>

<script lang="ts">
export default {
  data() {
    return {
      username: "",
    };
  },
};
</script>
