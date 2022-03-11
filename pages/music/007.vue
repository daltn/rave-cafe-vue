<template>
  <section class="threshold">
    <h1 class="mu-title"><sup>007</sup> the track ID mix</h1>
    <img
      class="header-img trackid"
      src="https://ravecafe.s3.amazonaws.com/sweet-kix.jpg"
    />
    <p class="caption">Sweet Kicks - Prospect Park - 08.20.2021</p>
    <section class="player">
      <iframe
        width="100%"
        height="166"
        scrolling="no"
        frameborder="no"
        allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1229533903&color=%234c493e&auto_play=false&hide_related=true&show_comments=true&show_user=true&show_reposts=false&show_teaser=false"
      ></iframe>
    </section>
    <section class="trackid">
      <p>A radio mix of some of our fav track IDs :)</p>
      <p>Tracklist:</p>
      <ul class="tracklist">
        <li>
          <a
            href="https://www.discogs.com/release/1565731-Val-Young-Seduction"
            target="_blank"
            rel="noreferrer nofollow"
            >Val Young - Seduction</a
          >
        </li>
        <li>
          <a
            href="https://devoye.bandcamp.com/track/bad-freaks-to-the-front-migos-x-paul-johnson"
            target="_blank"
            rel="noreferrer nofollow"
            >Devoye - Edits Vol. 1 - 02 Bad Freaks to the Front (Migos x Paul
            Johnson)
          </a>
        </li>
        <li>
          <a
            href="https://coymixltd.bandcamp.com/track/goodbye-sunshine"
            target="_blank"
            rel="noreferrer nofollow"
            >Remotif - Goodbye Sunshine</a
          >
        </li>
        <li>Ariana Grande - Positions (MJ Cole Crazy Love Garage Remix)</li>
        <li>
          <a
            href="https://warehousewax.bandcamp.com/track/unbrake-my-hardcore"
            target="_blank"
            rel="noreferrer nofollow"
            >Phuture Assassins - Unbrake My Hardcore</a
          >
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/137876-iiO-Rapture"
            target="_blank"
            rel="noreferrer nofollow"
            >iiO - Rapture</a
          >
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/1721168-Sue%C3%B1o-Latino-Sue%C3%B1o-Latino-Paradise-Version"
            target="_blank"
            rel="noreferrer nofollow"
          ></a>
        </li>
        <li>
          <a href="" target="_blank" rel="noreferrer nofollow"
            >Sueno Latino - Sueno Latino (Original Paradise Version)
          </a>
        </li>
        <li>
          <a
            href="https://dubfire.bandcamp.com/track/who-dares-to-believe-in-me-mind-readers-mix"
            target="_blank"
            rel="noreferrer nofollow"
            >The Believers - Who Dares to Believe in Me (Mind Readers Mix)</a
          >
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/3091129-Jackie-McLean-Michael-Carvin-Antiquity"
            target="_blank"
            rel="noreferrer nofollow"
            >Jackie McLean & Michael Carvin - De I Comahlee Ah (00:00 - 04:02
            excerpt from Extended)</a
          >
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/11560081-Lauren-Bousfield-The-miX-Files-Lauren-Bousfield"
            target="_blank"
            rel="noreferrer nofollow"
            >The miX-Files: Lauren Bousfield (excerpt)</a
          >
        </li>
        <li>
          <a
            href="https://www.discogs.com/sell/release/796047"
            target="_blank"
            rel="noreferrer nofollow"
            >Bruce Springsteen - Cover Me
          </a>
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/6881604-Talking-Heads-Born-Under-Punches-The-Heat-Goes-On"
            target="_blank"
            rel="noreferrer nofollow"
            >Talking Heads - Born Under Punches (The Heat Goes On)
          </a>
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/25-Kerri-Chandler-Digitalsoul-Session-Two"
            target="_blank"
            rel="noreferrer nofollow"
            >Kerri Chandler - Digitalsoul vol. 2 (I Found U)
          </a>
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/12581427-Louie-Vega-Featuring-Josh-Milan-The-World-Is-A-Family-Remixes"
            target="_blank"
            rel="noreferrer nofollow"
            >Louie Vega - The World is a Family (Afrohouse Mix)</a
          >
        </li>
        <li>
          <a
            href="https://integralrecords.bandcamp.com/track/drowning"
            target="_blank"
            rel="noreferrer nofollow"
            >Hiatt dB - 6 O'Clock Rock
          </a>
        </li>
        <li>
          <a
            href="https://www.discogs.com/release/107893-Overdubz-I-Want-Bass-Got-Me-Up"
            target="_blank"
            rel="noreferrer nofollow"
            >Overdubz - I Want Bass (Excerpt)</a
          >
        </li>
        <li>
          <a
            href="https://billlaswell.bandcamp.com/track/alsema-dub"
            target="_blank"
            rel="noreferrer nofollow"
            >Jah Wobble & Bill Laswell - Alsema Dub</a
          >
        </li>
      </ul>
    </section>
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

.trackid p {
  margin: 20px 0;
}

.caption {
  margin: 10px 0 0;
  text-align: left;
  width: 100%;
  opacity: 0.8;
}

.header-img.trackid {
  margin-bottom: 0;
}

.tracklist {
  margin: 10px 0 5%;
}

.tracklist > li {
  margin: 10px 0;
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
