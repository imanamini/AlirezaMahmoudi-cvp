<template>
  <div>
    <img alt="" v-for="image in 29" :src="'/'+image+'.jpg'">
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style>
img{
  margin: auto;
  width: 50%;
  display: block;
  margin-bottom: 100px;
  min-width: 50%;
}
</style>
