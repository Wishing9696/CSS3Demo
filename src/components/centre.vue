<template>
  <div>
    <div class="box1">
      <span>垂直居中1</span>
    </div>
    <div class="box2">
      <span>垂直居中2</span>
    </div>
        <div class="box3">
      <span>垂直居中3</span>
    </div>
  </div>
</template>

<style>
.box1 {
  text-align: center;
}
.box2 {
    width: 160px; /*此width为span的边框，设置后，字体在边框最左边*/
    margin-left: auto;
    margin-right: auto;
}
</style>
