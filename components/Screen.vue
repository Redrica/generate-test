<template>
  <div>
      <button @click="onButtonClick">Press me</button>
      <p>Нажато {{ clicks }} раз</p>
      <div>
          <img src="../assets/img/june.png" alt="">
      </div>
      <div>
          <img src="https://st2.depositphotos.com/3489481/5208/i/600/depositphotos_52086275-stock-photo-book-of-life.jpg" alt="">
          <br>
          <img src="https://lh3.googleusercontent.com/proxy/lySUKrdA4ThZ9zDqeWat9MhtrVtBZAKGBJBkXNSqhtwnHRtCjRcD8OGKih_hKLCs1Rrp0fE2caBIUJdmm24TRdHucSDmTLvavA" alt="">
      </div>
  </div>
</template>

<script>
export default {
    name: 'Screen',
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
