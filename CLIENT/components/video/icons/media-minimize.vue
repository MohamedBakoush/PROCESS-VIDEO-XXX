<template>
  <i class="gg-minimize"></i>
</template>

<style scoped>
 .gg-minimize {
 box-sizing: border-box;
 position: relative;
 display: block;
 transform: scale(var(--ggs,1));
 width: 4px;
 height: 4px;
 box-shadow:
 -8px -4px 0 -1px,
 -6px -4px 0 -1px,
 8px 4px 0 -1px,
 6px 4px 0 -1px,
 8px -4px 0 -1px,
 6px -4px 0 -1px,
 -8px 4px 0 -1px,
 -6px 4px 0 -1px
}

.gg-minimize::after,
.gg-minimize::before {
 content: "";
 display: block;
 box-sizing: border-box;
 position: absolute;
 width: 2px;
 height: 18px;
 border-top: 6px solid;
 border-bottom: 6px solid;
 box-shadow: 18px 0 0 -2px;
 top: -7px
}

.gg-minimize::after {
 left: -3px
}

.gg-minimize::before {
 right: -3px
} 
</style>
