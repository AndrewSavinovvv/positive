<script setup>

</script>

<template>
  <header class="header">
    <div class="header__inner container">
      <a class="header__logo logo" href="/">
        <img
            class="logo__image"
            src="@/images/logo.svg"
            alt="Positivus"
            width="220" height="36" loading="lazy"
        />
      </a>
      <nav class="header__menu hidden-mobile">
        <ul class="header__menu-list">
          <li class="header__menu-item">
            <a class="header__menu-link" href="/">About us</a>
          </li>
          <li class="header__menu-item">
            <a class="header__menu-link" href="/">Services</a>
          </li>
          <li class="header__menu-item">
            <a class="header__menu-link" href="/">Use Cases</a>
          </li>
          <li class="header__menu-item">
            <a class="header__menu-link" href="/">Pricing</a>
          </li>
          <li class="header__menu-item">
            <a class="header__menu-link" href="/">Blog</a>
          </li>
        </ul>
      </nav>
      <button
          class="header__button button button--transparent hidden-mobile"
          type="button"
      >
        Request a quote
      </button>
      <button
          class="header__burger-button burger-button visible-mobile"
          type="button"
          onclick="mobileOverlay.showModal()"
      >
        <span class="visually-hidden">Open navigation menu</span>
      </button>
    </div>
  </header>
</template>

<style scoped>

</style>