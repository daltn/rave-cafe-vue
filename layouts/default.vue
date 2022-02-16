<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=DM+Sans&display=swap');
@import url('https://fonts.googleapis.com/css2?family=PT+Serif:ital@0;1&display=swap');
:root {
  --black: #1c1c1c;
}
html {
  font-family: 'DM Sans', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  color: #fff;
}

.center {
  text-align: center;
}

.small-img {
  max-width: 500px;
  margin: 80px auto;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

body {
  background-color: var(--black);
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

a {
  color: #fff;
  text-decoration: none;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: #212121;
  background-size: 130% 130%;
  background-position: center;
  overflow: hidden;
}

h1 {
  font-size: 55px;
}
.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}

.mu-title sup {
  font-size: 25px;
  margin-right: 6px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 20px;
}

@media only screen and (max-width: 750px) {
  .grid {
    grid-template-columns: repeat(1, 1fr);
  }
}
</style>
