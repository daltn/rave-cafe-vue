<template>
  <section class="container">
    <h1 class="mu-title">music</h1>
    <ul class="mix-listing">
      <li class="mix-link">
        <sup>007</sup>
        <NuxtLink to="/music/007">the track ID mix</NuxtLink>
      </li>
      <li class="mix-link">
        <sup>006</sup>
        <NuxtLink to="/music/006">winter listening party </NuxtLink>
      </li>
      <li class="mix-link">
        <sup>005</sup>
        <NuxtLink to="/music/005">color potential</NuxtLink>
      </li>
      <li class="mix-link">
        <sup>004</sup> <NuxtLink to="/music/004">rave cafe @ bossa </NuxtLink>
      </li>
      <li class="mix-link">
        <sup>003</sup> <NuxtLink to="/music/003">the chill mix </NuxtLink>
      </li>
      <li class="mix-link">
        <sup>002</sup> <NuxtLink to="/music/002">welcome 2 the cafe </NuxtLink>
      </li>
      <li class="mix-link">
        <sup>001</sup> <NuxtLink to="/music/001">L&D </NuxtLink>
      </li>
    </ul>
    <NuxtLink to="/welcome">
      <Logo height="80" />
    </NuxtLink>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.mu-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: normal;
  font-size: 80px;
  color: #fff;
  width: 100%;
  letter-spacing: 1px;
  mix-blend-mode: difference;
  padding: 20px;
}

.mix-link {
  color: #fff;
  text-decoration: none;
  font-size: 50px;
  margin: 5px 0;
}

.mix-link sup {
  font-size: 25px;
}

.mix-listing {
  margin: 20px 0 40px;
}

a:hover {
  text-decoration: underline;
}

@media only screen and (max-width: 700px) {
  .mix-link {
    color: #fff;
    text-decoration: none;
    font-size: 25px;
  }
  .mix-link sup {
    font-size: 18px;
  }
}
</style>
