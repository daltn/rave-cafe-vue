<template>
  <section class="threshold">
    <h1 class="mu-title"><sup>006</sup> winter listening party</h1>
    <img class="header-img" src="~/assets/welcome/welcome.jpg" />
    <section class="player">
      <iframe
        width="100%"
        height="450"
        scrolling="no"
        frameborder="no"
        allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/1365793810&color=%231c1c1c&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=false"
      ></iframe>
    </section>
    <section>
      <p>
        On 12.11.21 we hosted a high-fidelity listening party in our basement.
        Three months prior, during Hurricane Ida, the space had been flooded
        with 6 inches of water, so this was the first time we’d had a chance to
        invite friends into our new apartment, and provided another opportunity
        to build off the learnings from our natural tie-dye event in July.
      </p>
      <p>
        Zim, Fine Touch, disco smile and Devoye played a selection of music
        ranging from ambient, jazz, & a capella, to spaced-out house & techno.
        Adi & Aileen rigged a custom LED ceiling light installation and vibed
        out the space with a smattering of iridescent fabric and a gradient of
        pink to orange hues of light. They also brought Adi’s two ojas hi-fi
        speakers, and a QSC speaker to create an immersive three-point listening
        experience.
      </p>
      <p>
        Inspired by Justin Carter and Eamon Harkin’s Planetarium party, we
        decided to make the basement a no-talking zone where guests could sit or
        lie on the floor, snuggle up in blankets and experience active
        listening. We sought to create a space where guests were given
        permission to be left alone to observe and just be. We laid down a 10x12
        foot area of black ⅝ inch gym mats, and littered the space with blue ink
        pens and white paper to encourage guests to sketch and then tape up
        their drawings on the wall. I was interested in seeing how blue ink in
        particular would reflect the lights to create a psychedelic art
        experience.
      </p>
      <p>
        We felt that it was important for guests to be able to fully relax
        without feeling like they were on-camera so for the livestream we angled
        the webcam into a mirror tilted towards the ceiling light installation,
        resulting in a more abstract image of the silhouetted DJ, with brief
        silhouettes of guests moving through the space. We also placed the
        computer running the stream behind a curtain in the back of the DJ booth
        so that each DJ could pop in and engage with the chat as they wished,
        without creating any light pollution.
      </p>
      <p>
        One of my biggest takeaways was realizing that our upstairs neighbor is
        an amazing artist! This has left questions in my mind around the
        importance of, and different ways in which we might be able to document
        the happenings within the dance music scene in NYC. How do you record
        the vibe of a dance floor if the very presence of a camera ruins it? Is
        the experience of dance one that is inherently ephemeral? Do stories and
        the feeling left behind by the music suffice?
      </p>

      - L
    </section>
    <ul class="grid">
      <li><img src="~/assets/winter/Scan 12.jpeg" /></li>
      <li><img src="~/assets/winter/Scan 13.jpeg" /></li>
    </ul>
    <NuxtLink to="/welcome">
      <Logo height="30" />
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

.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 20px;
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
  .grid {
    grid-template-columns: repeat(1, 1fr);
  }
}
</style>
