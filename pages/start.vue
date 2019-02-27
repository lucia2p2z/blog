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
          <a class="navbar-item" href="https://github.com/cypherpuncakes/cypherpuncakes.github.io"  target="_blank" >GitHub</a>
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
        <span class="subtitle">A simple container</span>
        <span class="subtitle is-italic">to divide</span>
        <span class="subtitle">your page into</span>
        <span class="subtitle is-bold">sections,</span>
        <span class="subtitle">like the one you're currently reading</span>
        <h4>Trying to make a paragraph</h4>
      </div>
    </section>

    <!-- <section class="section">
      <div class="container has-text-centered">
        <div class="columns is-centered">
          <div class="column">
            <nuxt-link to="first">
              <button class="button">First Project</button>
            </nuxt-link>
          </div>
          <div class="column">
            <button class="button">Second Project</button>
          </div>
          <div class="column">
            <button class="button">...</button>
          </div>
        </div>
      </div>
    </section>-->
    <section class="hero is-warning is-bold">
      <div class="hero-body">
        <div class="container">
          <nuxt-link to="story">
            <h1 class="title">Our Story</h1>
          </nuxt-link>
          <h2 class="subtitle">Bah... Things</h2>
        </div>
      </div>
    </section>

    <br>
    <section class="hero is-info is-bold">
      <div class="hero-body">
        <div class="container">
          <nuxt-link to="projects">
            <h1 class="title">Our Projects</h1>
          </nuxt-link>
          <h2 class="subtitle">I'm kidding... just trying to make some stuff</h2>
        </div>
      </div>
    </section>
  </div>
</template>
