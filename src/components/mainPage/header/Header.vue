<template>
  <header class="header">
    <div class="header__wrapper">
      <select name="header__sort-by">
        <option value="">Search by</option>
        <option value="">First name</option>
        <option value="">Last Name</option>
        <option value="">Unslected</option>
      </select>

      <div class="header__search">
        <input
        type="text"
        placeholder="Find contact"
        class="header__input"
        id="search-contact"
        >

        <label class="header__search-img" for="search-contact">
          <img
            src="@/image/icons/loupe.svg"
            alt="search"
          >
        </label>
      </div>
    </div>

    <button class="header__button">
      Add contact
    </button>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style scoped lang="scss">
  .header {
    background-color: #eaeced;
    display: flex;
    justify-content: space-between;
    padding: 10px 30px;

    &__wrapper {
      display: flex;
      position: relative;
    }

    &__search {
      margin-left: 20px;
    }

    &__search-img {
      position: absolute;
      top: 50%;
      right: 10px;
      transform: translateY(-100%);
      width: 10px;
      height: 10px;
      object-fit: contain;
    }

    &__button {
      width: 20%;
      background-color: #00cc52;
      outline: none;
      border: none;
      border-radius: 5px;
      font-size: 12px;
      color: #fff;
      text-transform: uppercase;
    }
  }
</style>
