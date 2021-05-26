<template>
  <header>
    <nav>
      <img
        id="menu-button"
        src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg"
        alt="Abrir menu"
      />
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
header {
  background: #17222d;
  width: 100%;
  height: 60px;
}

#menu-button {
  width: 30px;
}
</style>
