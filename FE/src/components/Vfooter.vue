<template>
  <div>
    <p>Copyrights © 2014-{{ jzCurrentYear }} RoyalMjz. All Rights Reserved.</p>
  </div>
</template>

<script>
module.exports = {
  data: function () {
    var copyright = new Date()
    var update = copyright.getFullYear()
    return {
      jzCurrentYear: update
    }
  }
}
</script>

<style scoped>
  p {
    font-size: 1.4rem;
    margin: auto;
    color: #3d3d3d;
  }
</style>
