<template>
  <div>
  <h2>About my gallery</h2>
  <div>This is a test project, in which I try to create some website with some pages.</div>
  <div>Other my projects you cat see here -
    <a href="https://github.com/lethoss/lethoss.github.io"  target="_blank">https://github.com/lethoss/lethoss.github.io </a>
  </div>
  <div>
      <router-link to="/about/contacts" exact>My contacts </router-link>
    <router-view />
  </div>
  </div>
</template>
