<template>
  <section class="email-page">
    <h1 class="mu-title">email</h1>
    <p>
      If you’d like to join the newsletter drop your email below. We won't spam
      you.
    </p>
    <div id="mc_embed_signup">
      <form
        action="https://cafe.us7.list-manage.com/subscribe/post?u=7ac7e285f8d8826591ef315a7&amp;id=47d255f050"
        method="post"
        id="mc-embedded-subscribe-form"
        name="mc-embedded-subscribe-form"
        class="validate"
        target="_blank"
        novalidate
      >
        <div id="mc_embed_signup_scroll">
          <div class="mc-field-group">
            <input
              type="email"
              value=""
              name="EMAIL"
              class="email"
              id="mce-EMAIL"
            />
          </div>
          <div id="mce-responses" class="clear">
            <div
              class="response"
              id="mce-error-response"
              style="display: none"
            ></div>
            <div
              class="response"
              id="mce-success-response"
              style="display: none"
            ></div>
          </div>
          <div style="position: absolute; left: -5000px" aria-hidden="true">
            <input
              type="text"
              name="b_7ac7e285f8d8826591ef315a7_47d255f050"
              tabindex="-1"
              value=""
            />
          </div>
          <div class="clear">
            <input
              type="submit"
              value="⮕"
              name="subscribe"
              id="mc-embedded-subscribe"
              class="button"
            />
          </div>
        </div>
      </form>
    </div>
    <NuxtLink to="/welcome">
      <Logo height="80" :bottom="true" />
    </NuxtLink>
  </section>
</template>

<script>
export default {}
</script>

<style>
.email-page {
  text-align: center;
  padding-top: 5%;
  width: 80%;
  margin: 0 auto;
  max-width: 900px;
}

.email-page p {
  margin: 50px 0;
}
#mc_embed_signup {
  margin: 50px 0;
  width: 100%;
}
#mc_embed_signup_scroll {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.email {
  color: #fff;
  border: 1px solid #fff;
  background-image: none;
  background-color: transparent;
  -webkit-box-shadow: none;
  -moz-box-shadow: none;
  box-shadow: none;
  font-size: 20px;
  padding: 10px;
  font-family: inherit;
  width: 100%;
}
.button {
  display: inline-block;
  border: 1px solid #fff;
  padding: 1rem;
  width: 100%;
  font-size: 2rem;
  text-decoration: none;
  background: transparent;
  color: #ffffff;
  font-family: sans-serif;
  font-size: 1rem;
  cursor: pointer;
  text-align: center;
  transition: background 250ms ease-in-out, transform 150ms ease;
  -webkit-appearance: none;
  -moz-appearance: none;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  margin-left: 10px;
}
</style>
