<script>
export default {};
</script>

<template>
  <header>
    <div>
      <img src="../assets/img/dc-logo.png" alt="" />
    </div>
    <div class="section">
      <div class="characters">CHARACTERS</div>
      <div class="comics">COMICS</div>
      <div class="movies">MOVIES</div>
      <div class="tv">TV</div>
      <div class="games">GAMES</div>
      <div class="collectibles">COLLETTIBLES</div>
      <div class="video">VIDEO</div>
      <div class="fans">FANS</div>
      <div class="news">NEWS</div>
      <div class="shop">SHOP</div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  width: 1100px;
  height: 150px;
  margin: auto;
  display: flex;
  justify-content: space-around;
}
.section {
  gap: 1rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 20px;
}
</style>
