<template>
    <div class="hello">
    <h1>Monster Rollodex</h1>
    <input type="text" v-model="Search" placeholder="Search-title"/>
    <label>Search</label>
</div>
</template>
<script>
export default {
  name:'Home'
}
</script>
<style >
.App {
    text-align: center;
  }
  
  h1 {
    font-family: 'Bigelow Rules';
    font-size: 72px;
    color: #0ccac4;
  }
</style>