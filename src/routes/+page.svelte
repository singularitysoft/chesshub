<div class="chess-board">
  <div class="row">
    <div class="square black"></div>
    <div class="square white"></div>
    <div class="square black"></div>
    <div class="square white"></div>
    <div class="square black"></div>
    <div class="square white"></div>
    <div class="square black"></div>
    <div class="square white"></div>
    <div class="square black"></div>
  </div>
  <div class="row">
    <div class="square white"></div>
    <div class="square black"></div>
    <div class="square white"></div>
    <div class="square black"></div>
    <div class="square white"></div>
    <div class="square black"></div>
    <div class="square white"></div>
    <div class="square black"></div>
    <div class="square white"></div>
  </div>
  <!-- Repeat the above pattern for 8 rows to create the chess board -->
</div>

<style>
  .chess-board {
  display: flex;
  flex-wrap: wrap;
}

.row {
  display: flex;
  width: 100%;
}

.square {
  width: 12.5%;
  height: 0;
  padding-bottom: 12.5%;
  box-sizing: border-box;
  float: left;
}

.black {
  background-color: #8B5E3C;
}

.white {
  background-color: #F0D9B5;
}
</style>
