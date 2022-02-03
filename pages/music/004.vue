<template>
  <section class="threshold">
    <h1 class="mu-title"><sup>004</sup> rave cafe @ bossa</h1>
    <img class="header-img" src="~/assets/bossa/000310030012.jpg" />
    <img class="header-img" src="~/assets/bossa/000310030015.jpg" />
    <img class="header-img" src="~/assets/bossa/000310030007.jpg" />
    <img class="header-img" src="~/assets/bossa/000310030011.jpg" />
    <img class="flyer" src="~/assets/flyers/rc-bossa.png" />
    <section class="player">
      <iframe
        width="100%"
        height="450"
        scrolling="no"
        frameborder="no"
        allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/1389574348&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"
      ></iframe>
    </section>
    <section>
      <p>a couple b2b sets from a monday night @ bossa :)</p>
      <p>love to their recovery from the fire</p>
      <p>
        donations here -
        <a
          href="https://www.gofundme.com/f/bossa-nova-civic-club-restoration-staff-fund"
          >bossa gofundme</a
        >
      </p>
    </section>
    <br />
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

a {
  text-decoration: underline;
}

.header-img {
  margin: 40px 0;
}

.flyer {
  width: 400px;
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
