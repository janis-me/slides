<template>
  <SlidevVideo autoplay autoreset="slide" onended="onVideoFinished()">
    <source src="../assets/intro.mp4" type="video/mp4" />
  </SlidevVideo>

  <component is="script"> function onVideoFinished() { window.__slidev__.nav.next(); } </component>
</template>
