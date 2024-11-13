<script setup>

</script>

<template>
  <dialog class="mobile-overlay visible-mobile" id="mobileOverlay">
    <form class="mobile-overlay__close-button-wrapper" method="dialog">
      <button
          class="mobile-overlay__close-button cross-button"
          type="submit"
      >
        <span class="visually-hidden">Close navigation menu</span>
      </button>
    </form>
    <div class="mobile-overlay__body">
      <ul class="mobile-overlay__list">
        <li class="mobile-overlay__item">
          <a class="mobile-overlay__link" href="/">About us</a>
        </li>
        <li class="mobile-overlay__item">
          <a class="mobile-overlay__link" href="/">Services</a>
        </li>
        <li class="mobile-overlay__item">
          <a class="mobile-overlay__link" href="/">Use Cases</a>
        </li>
        <li class="mobile-overlay__item">
          <a class="mobile-overlay__link" href="/">Pricing</a>
        </li>
        <li class="mobile-overlay__item">
          <a class="mobile-overlay__link" href="/">Blog</a>
        </li>
      </ul>
    </div>
  </dialog>
</template>

<style scoped>

</style>