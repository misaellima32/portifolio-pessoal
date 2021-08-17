<template>
  <div>
    <b-navbar class="" toggleable="sm" type="dark" variant="dark">
      <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

      <b-navbar-brand class="m-2 p-2"><fa class="size-icon" icon="rocket"/></b-navbar-brand>

      <b-collapse id="nav-text-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-navbar-nav class="mr-3 font-weight-bold">
            <NuxtLink to="/">Início</NuxtLink>
          </b-navbar-nav>
          <b-navbar-nav class="mr-3 font-weight-bold">
            <NuxtLink to="/about">Sobre</NuxtLink>
          </b-navbar-nav>
          <b-navbar-nav class="mr-3 font-weight-bold">
            <NuxtLink to="/courses">Contato</NuxtLink>
          </b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <div class="m-5">
      <Nuxt class="app-container"/>
    </div>
    <footer id="footer">
      <div class="d-flex justify-content-center">
        <span>Footer</span>
      </div>
    </footer>
  </div>
</template>
<style lang="scss" scoped>
.size-icon {
  font-size: 3rem;
  border-radius: 2rem;
  color: rgb(255, 254, 255);
  background: rgb(180,110,255);
  background: linear-gradient(90deg, rgba(180,110,255,1) 0%, rgba(119,3,221,1) 33%, rgba(221,3,161,1) 67%);
}
#footer {
  background-color: rgb(24, 24, 24);
}
</style>