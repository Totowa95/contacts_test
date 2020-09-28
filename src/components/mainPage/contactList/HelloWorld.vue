<template>
  <table class="contact__list">
    <tr class="contact__caption">
      <th class="contact__id">Id</th>
      <th class="contact__name">First name</th>
      <th class="contact__last-name">Last name</th>
      <th class="contact__phone">Phone</th>
      <th class="contact__email">Email</th>
    </tr>

    <list-item></list-item>
    <list-item></list-item>
    <list-item></list-item>
  </table>
</template>

<script>
import ListItem from '@/components/mainPage/contactList/ListItem.vue';

export default {
  name: 'HelloWorld',
  components: {
    ListItem,
  },
};
</script>

<style scope lang="scss">
  .contact {
    &__list {
    display: flex;
    flex-direction: column;
    background-color: #fff;
  }

  &__caption {
    display: flex;
    background-color: #6B757F;
    padding: 15px 0;
    text-transform: uppercase;
    text-align: left;
    color: #fff;
    font-size: 14px;
  }
}

</style>
