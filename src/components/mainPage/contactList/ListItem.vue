<template>
  <tr class="contact__info">
    <td class="contact__id">1</td>

    <td class="contact__name">Anton</td>

    <td class="contact__last-name">Sorokin</td>

    <td class="contact__phone">0638793362</td>

    <td class="contact__email">todasf@uke.net</td>
  </tr>
</template>

<script>
export default {
  name: 'ListItem',
};
</script>

<style lang="scss">
  $contactWidth: 23%;
  $idWidth: 8%;

  .contact {
    &__info {
      display: flex;
      // justify-content: space-between;
      padding: 10px 0;
      //убрать
    }

    &__id {
      width: $idWidth;
      margin-left: 30px;
    }

    &__name {
      width: $contactWidth;
    }

    &__last-name {
      width: $contactWidth;
    }

    &__phone {
      width: $contactWidth;
    }

    &__email {
      width: $contactWidth;
      margin-right: 30px;
    }

    &--gray {
      background-color: lightgray;
    }
  }
</style>
