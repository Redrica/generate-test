<template>
  <div>
      <button @click="onButtonClick">Press me</button>
      <p>Нажато {{ clicks }} раз</p>
      <div>
          <img src="https://a.omappapi.com/users/cef824d326cb/images/f09b12bfbd7b1562172021-tech.png" alt="">
      </div>
  </div>
</template>

<script>
export default {
    name: 'ScreenLazy',
    data() {
        return {
            clicks: 0,
        }
    },
    methods: {
        onButtonClick() {
            this.clicks += 1;
        }
    }
}
</script>

<style>

</style>
