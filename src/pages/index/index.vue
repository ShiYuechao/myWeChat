<template>
  <div>
    <header>
        <p>这是index的标签</p>
    </header>
    <!-- <h1>这是index的标签</h1> -->
  </div>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>

<style>
div > header {
  width: 100%;
  height: 3rem;
  background: red;
}
div > header > p{
    text-align: center;
    font-size: 0.8rem;
    line-height: 3rem;
    margin: 0 auto;     
}
</style>

