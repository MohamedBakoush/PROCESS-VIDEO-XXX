<template>
  <i class="gg-play-backwards"></i>
</template>

<style scoped>
 .gg-play-backwards {
 box-sizing: border-box;
 position: relative;
 display: block;
 transform: scale(var(--ggs,1));
 width: 3px;
 height: 10px;
 background: currentColor
}

.gg-play-backwards::after,
.gg-play-backwards::before {
 content: "";
 display: block;
 box-sizing: border-box;
 position: absolute;
 width: 0;
 height: 10px;
 border-top: 5px solid transparent;
 border-bottom: 5px solid transparent;
 border-right: 6px solid;
 right: -7px
}

.gg-play-backwards::before {
 right: -14px
} 
</style>
