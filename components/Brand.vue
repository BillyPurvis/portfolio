<template>
  <div class="branding">
    <h1>Glen Sargent</h1>
    <h2>I write specifically in Go. I don't work in inferior languages. Unlike PHP developers, I'm aware this isn't 1999 anymore. PRAISE BE GO.</h2>
    <ul>
      <a href="mailto:glen@muttnik.io"><li>Email</li></a>
      <a href="https://twitter.com/glensarge"><li>Twitter</li></a>
      <a href="https://linkedin.com/in/glensargent/"><li>LinkedIn</li></a>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
.branding {
  font-size: 12px;
  margin: 50px 0;
  h1 {
    text-transform: uppercase;
    font-size: inherit;
    font-weight: bold;
  }
  ul {
    padding: 0;
    margin: 0;
    li {
      display: inline-block;
      margin-right: 10px;
    }
  }
}
</style>
