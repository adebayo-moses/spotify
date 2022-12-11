<script setup>

</script>

<template>
<header>
  <img class="logo" src="@/assets/logo.svg" alt="Logo" />
  <div class="wrapper">
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <div class="social">
      <a href="#"><img src="@/assets/facebook.svg" alt="Facebook" /></a>
      <a href="#"><img src="@/assets/twitter.svg" alt="Twitter" /></a>
      <a href="#"><img src="@/assets/instagram.svg" alt="Instagram" /></a>
    </div>
  </div>
  </header>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
