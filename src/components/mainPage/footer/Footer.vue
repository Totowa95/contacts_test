<template>
  <footer class="footer">
    <span class="footer__quantity-contacts">Total: 3</span>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
};
</script>

<style scoped lang="scss">
  .footer {
    background-color: #eaeced;
    display: flex;
    justify-content: space-between;
    padding: 10px 30px;
    height: 20px;

    &__quantity-contacts {
      font-size: 14px;
      font-style: italic;
      color: gray;
    }
  }
</style>
