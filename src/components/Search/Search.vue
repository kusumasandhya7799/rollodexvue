<template>
<div className='search'>
    <input 
        className="Search-box"
        name="search"
        type="text"
        placeholder="search monsters"/>
</div>
</template>
<script>
    export default {
    name: 'Search',
    components: {Search}
    }
</script>

<style>
.search-box {
    -webkit-appearance: none;
    border: none;
    outline: none;
    padding: 10px;
    width: 150px;
    line-height: 30px;
    margin-bottom: 30px;
  }
</style>
