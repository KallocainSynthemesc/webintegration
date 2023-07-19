<template>
  <div class="slide">
    <div class="heading">CSS - Typeface</div>
    <div class="content">
      <img
        src="../assets/illustrations/typeface.svg"
        style="width: 100%; margin-bottom: 5%"
      />
      <div class="flex-container">
        <div style="width: 45%; margin-left: 25%">
          <h2 class="title" style="color: #db290eff">Weight</h2>
          <ul>
            <li style="font-weight: lighter">Light</li>
            <li style="font-weight: normal">Normal</li>
            <li style="font-weight: bold">Bold</li>
            <li style="font-weight: bolder">Bolder</li>
          </ul>
        </div>
        <div style="width: 45%; margin-right: 2%; margin-left: 2%">
          <h2 class="title" style="color: #db290eff">Style</h2>
          <ul>
            <li style="font-style: normal">Normal</li>
            <li style="font-style: italic">Italic</li>
            <li style="font-style: oblique">Oblique</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.flex-container div ul li {
  font-family: arial;
}
</style>
