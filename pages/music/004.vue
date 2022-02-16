<template>
  <section class="threshold">
    <h1 class="mu-title"><sup>004</sup> rave cafe @ bossa</h1>
    <img class="header-img" src="~/assets/bossa/000310030007.jpg" />
    <section class="player">
      <iframe
        width="100%"
        height="285"
        scrolling="no"
        frameborder="no"
        allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/1389574348&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"
      ></iframe>
    </section>
    <section>
      <p>
        <a href="https://soundcloud.com/taal-nyc" rel="noreferrer nofollow"
          >Taal</a
        >
        b2b
        <a href="https://soundcloud.com/dlc_nyc" rel="noreferrer nofollow"
          >Downloadable Content</a
        >
        and
        <a href="https://soundcloud.com/discosmile" rel="noreferrer nofollow"
          >L</a
        >&<a href="https://soundcloud.com/daltonsaffe" rel="noreferrer nofollow"
          >D</a
        >
        from a monday night @ bossa :)
      </p>
      <p>
        Donate here to help support their recovery from the fire that occurred
        on 01.12.2022 -
        <a
          target="_blank"
          rel="norefferer nofollow"
          href="https://www.gofundme.com/f/bossa-nova-civic-club-restoration-staff-fund"
          >bossa gofundme</a
        >
      </p>
    </section>
    <div class="grid">
      <img class="header-img" src="~/assets/bossa/000310030012.jpg" />
      <img class="header-img" src="~/assets/bossa/000310030015.jpg" />
    </div>
    <img class="header-img" src="~/assets/bossa/000310030011.jpg" />
    <img class="flyer" src="~/assets/flyers/rc-bossa.png" />

    <br />
    <NuxtLink to="/music">
      <Logo height="80" :bottom="true" />
    </NuxtLink>
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
