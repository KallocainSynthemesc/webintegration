<template>
  <div class="slide">
    <div class="heading">CSS - Box - border</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 31%">
          <h2 class="title" style="color: #db290eff">Border</h2>
          <p>
            Chaque boîte possède une bordure. La bordure sépare le bord d'une
            boîte de celui d'une autre.
          </p>
        </div>
        <div style="width: 31%; margin-right: 2%; margin-left: 2%">
          <h2 class="title" style="color: #ffe5b8ff">Margin</h2>
          <p>Les Margin se situent à l'extérieur de la bordure.</p>
        </div>
        <div style="width: 31%">
          <h2 class="title" style="color: #fabeb7ff">Padding</h2>
          <p>
            Le Padding est l'espace entre le bord d'une boîte et son contenu.
          </p>
        </div>
      </div>
      <img
        src="../assets/illustrations/margin-padding-border.svg"
        style="width: 45%; margin-left: 25%"
      />
    </div>
  </div>
</template>

<style scoped>
.flex-container div .sub-title {
  color: #66cdaa;
  font-size: 7rem;
}
</style>
