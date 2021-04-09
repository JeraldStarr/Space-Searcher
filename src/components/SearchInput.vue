<template>
    <div class="searchWrapper">
      <input id="search" name="search" type="text" v-model='searchValue' @input="handleInput"/>
    </div>
</template>

<script>
export default {
    name: 'SearchInput',
};
</script>

<style lang="scss" scoped>
.searchWrapper {
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    width: 300px;
    input {
      height: 30px;
      border: 0;
      border-bottom: 1px solid #fff;
      transition: box-shadow .5s;
    }
    input:focus {
        outline: none;
        box-shadow: 0 5px -8px white;
    }
  }
</style>
