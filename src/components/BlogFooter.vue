<template>
  <transition appear name="v--mask">
    <footer v-once class="blog__footer">
      <div class="privacy policy">
        Privacy <a href="/privacy"> policy </a>
      </div>
      <div class="signature cosmicjs">
        Powered by <a href="https://cosmicjs.com" target="_blank">Cosmic JS</a>
      </div>
    </footer>
  </transition>
</template>

<script>
export default { name: 'blog-footer' }
</script>
