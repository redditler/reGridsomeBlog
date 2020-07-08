<template>
  <header class="header">
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-brand href="/">Gridsome Blog</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/">Home</b-nav-item>
          <b-nav-item href="/blog">Blog</b-nav-item>
          <b-nav-item href="/about">About</b-nav-item>
          <b-nav-item href="/contact">Contact</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Facebook</b-nav-item>
          <b-nav-item href="#">Twitter</b-nav-item>
          <b-nav-item href="#">Instagram</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </header>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style lang="scss">
nav {
  width: 100%;
  padding-top: 1rem;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}

.logo-home {
  font-size: 24px;
  max-width: 75%;
  font-weight: bold;
  &:hover {
    text-decoration: none;
  }
}

.logo-desktop {
  @media(max-width: 419px) {
    display: none;
  }
  @media (min-width: 420px) {
    display: default;
  }
}

.logo–mobile {
  @media(max-width: 419px) {
    display: default;
  }
  @media (min-width: 420px) {
    display: none;
  }
}

.logo-image {
  width: 40px;
}

.nav--link {
  margin-left: 20px;
  @media (max-width: 419px) {
    margin: 0;
    padding: 15px 10px 10px 0;
  }
}

.active--exact {
  font-weight: bold;
}
</style>
