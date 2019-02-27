<template>
  <div>
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a
          role="button"
          class="navbar-burger burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-start">
          <nuxt-link to="index" class="navbar-item">Home</nuxt-link>
          <nuxt-link to="story" class="navbar-item">Our Story</nuxt-link>
          <nuxt-link to="projects" class="navbar-item">Projects</nuxt-link>
          <nuxt-link to="contatti" class="navbar-item">Contacts</nuxt-link>
          <a
            class="navbar-item"
            href="https://github.com/cypherpuncakes/cypherpuncakes.github.io"
            target="_blank"
          >GitHub</a>
        </div>
      </div>
    </nav>
    <section class="section">
      <div class="container has-text-centered">
        <h1 class="title is-1">Chyperpuncakes</h1>
      </div>
    </section>

    <section class="section">
      <div class="container has-text-centered">
        <h1 class="title">Our Story</h1>
        <section class="section">
          <h3 class="subtitle is-6">He is a
            <strong>Lion</strong>. She is a
            <strong>donkey</strong>. Nothing more.
          </h3>
        </section>
      </div>
    </section>
  </div>
</template>
