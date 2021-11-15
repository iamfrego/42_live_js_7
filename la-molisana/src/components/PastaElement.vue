<template>
  <div>
    <div class="card">
      <img :src="image" alt="" />
      <h3>{{ titolo }}</h3>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    image: String,
    titolo: String,
  },
};
</script>


<style lang="scss">

.card{
    background-color: white;
    text-align: center;
    h3{
        padding: 0.5rem;
    }
}

</style>