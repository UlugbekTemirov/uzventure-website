<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <a href="index.html" class="navbar-brand"
        ><img src="/images/logos-logo.png" alt=""
      /></a>

      <button
        type="button"
        class="navbar-toggler collapsed"
        data-toggle="collapse"
        data-target="#main-nav"
      >
        <span class="menu-icon-bar"></span>
        <span class="menu-icon-bar"></span>
        <span class="menu-icon-bar"></span>
      </button>

      <div id="main-nav" class="collapse navbar-collapse">
        <ul class="navbar-nav ml-auto">
          <li>
            <RouterLink to="/" class="nav-item nav-link">Home</RouterLink>
          </li>
          <li>
            <RouterLink to="/about-us" class="nav-item nav-link"
              >About</RouterLink
            >
          </li>
          <li>
            <RouterLink to="/tours" class="nav-item nav-link">Tours</RouterLink>
          </li>
          <li class="dropdown">
            <a href="#" class="nav-item nav-link" data-toggle="dropdown"
              >Pages</a
            >
            <div class="dropdown-menu">
              <a href="gallery-grid.html" class="dropdown-item">Gallery Grid</a>
              <a href="team.html" class="dropdown-item">Team</a>
              <a href="testimonials.html" class="dropdown-item">Testimonials</a>
              <a href="faq.html" class="dropdown-item">FAQ</a>
              <a href="404-error-page.html" class="dropdown-item">404 Page</a>
            </div>
          </li>
          <li class="dropdown">
            <a href="#" class="nav-item nav-link" data-toggle="dropdown"
              >Blogs</a
            >
            <div class="dropdown-menu">
              <a href="blog-grid.html" class="dropdown-item">Blog Grid</a>
              <a href="blog-left-sidebar.html" class="dropdown-item"
                >Blog Left Sidebar</a
              >
              <a href="blog-right-sidebar.html" class="dropdown-item"
                >Blog Right Sidebar</a
              >
              <a href="blog-single.html" class="dropdown-item">Blog Single</a>
            </div>
          </li>
          <li>
            <a href="contact.html" class="nav-item nav-link last-link-item"
              >CONTACT</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
