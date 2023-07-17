<template>
  <div class="slide">
    <div class="heading">Images - Dimensions de l'image</div>
    <div class="content">
      <p>
        Les images que vous utilisez sur votre site web doivent être
        enregistrées à la même largeur et à la même hauteur que que vous voulez
        qu'elles apparaissent sur la page.
      </p>
      <div class="flex-container">
        <div style="width: 32%">
          <h2>Réduire</h2>
          <img
            src="../assets/illustrations/reduceSize.svg"
            style="width: 75%"
          />
          <p>
            Exemple : Si votre image a une largeur de 600 pixels de large et 300
            pixels de haut, vous pouvez réduire la taille de l'image de 50 %.
          </p>
          <p>Résultat : Cela créera une image plus rapide à télécharger.</p>
        </div>
        <div style="width: 32%">
          <h2>Augmenter</h2>
          <img
            src="../assets/illustrations/increaseSize.svg"
            style="width: 75%"
          />
          <p>
            Exemple : Si votre image ne fait que 100 pixels de large sur 50
            pixels de haut, augmenter la taille de 300 % serait de mauvaise
            qualité.
          </p>
          <p>Résultat : L'image est floue oufloue ou en bloc.</p>
        </div>
        <div style="width: 30%">
          <h2>Changement de forme</h2>
          <img src="../assets/illustrations/cropping.svg" style="width: 41%" />
          <p>
            Exemple : Si votre image a une taille de 300 pixels carrés, vous
            pouvez en supprimer parties. (Risque de perte d'information)
          </p>
          <p>
            Résultat : Seules certaines images peuvent être recadrées tout en
            conservant leur sens.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
