<template>
  <section class="threshold">
    <h1 class="mu-title"><sup>003</sup> the chill mix</h1>
    <img class="header-img" src="~/assets/misc/000310000022.jpg" />
    <section class="player">
      <iframe
        width="100%"
        height="166"
        scrolling="no"
        frameborder="no"
        allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1145310292&color=%231c1c1c&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=false"
      ></iframe>
    </section>
    <section>
      <p>
        We asked our friends to contribute nondance music for a chill radio mix
        :)
      </p>
      <p>Tracklist:</p>
      <ul class="tracklist">
        <li>Connan Mockasin - Charlotte's Thong</li>
        <li>Atlantic Starr - When Love Calls</li>
        <li>Nicolas Godin - Alger La Blanche</li>
        <li>Peggy Lee - Black Coffee</li>
        <li>Angelo Badalamenti - Dance Of The Dream Man (Instrumental)</li>
        <li>Agnes Obel - The Curse</li>
        <li>rei harakami - grief & loss</li>
        <li>Tornado Wallace - Voices</li>
        <li>Demdike Stare - Ambient Glory - last 6 mins of Side B</li>
        <li>Christina Chatfield - Sutro - Concatenate I</li>
        <li>Simon & Garfunkel - So Long, Frank Lloyd Wright</li>
      </ul>
    </section>
    <NuxtLink to="/music">
      <Logo height="80" />
    </NuxtLink>
    <br />
    <br />
    <br />
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.threshold {
  padding-top: 5%;
  width: 80%;
  margin: 0 auto;
  max-width: 900px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.tracklist {
  margin: -20px 0 20px;
}

a {
  text-decoration: underline;
}

.header-img {
  margin: 40px 0;
}

.mu-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: normal;
  font-size: 60px;
  color: #fff;
  width: 100%;
  letter-spacing: 1px;
  mix-blend-mode: difference;
  padding: 20px;
  text-align: center;
}

.mu-title sup {
  font-size: 25px;
}

.threshold p {
  margin: 5% auto;
  max-width: 500px;
}

.center {
  text-align: center;
}

.photos {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-bottom: 10%;
}

.player {
  display: flex;
  justify-content: center;
  width: 80%;
  margin: 5% 0;
}

h3 {
  font-size: 40px;
  text-align: center;
  margin: 10% 0 5%;
}

img {
  width: 100%;
  margin: 5% 0;
  transition: opacity 5s ease-out;
}
@media only screen and (max-width: 750px) {
  .mu-title {
    color: #fff;
    text-decoration: none;
    font-size: 25px;
    padding: 10px;
    margin-top: 10px;
  }
  .mu-title sup {
    font-size: 18px;
  }
}
</style>
