<template>
  <i class="gg-play-forwards"></i>
</template>

<style scoped>
.gg-play-forwards {
   box-sizing: border-box;
   position: relative;
   display: block;
   transform: scale(var(--ggs,1));
   width: 3px;
   height: 10px;
   background: currentColor
}
.gg-play-forwards::after,
.gg-play-forwards::before {
   content: "";
   display: block;
   box-sizing: border-box;
   position: absolute;
   width: 0;
   height: 10px;
   border-top: 5px solid transparent;
   border-bottom: 5px solid transparent;
   border-left: 6px solid;
   left: -7px
}
.gg-play-forwards::before {
   left: -14px
}
</style>
