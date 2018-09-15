<template lang="pug">
  #main
    h1 Hello
    #contents here is #contents inner text
      #inner here is #inner text
</template>

<style lang="scss">
h1 {
  color: red;
}
#contents {
  border: 1px solid;
  #inner {
    color: blue;
  }
}
</style>
