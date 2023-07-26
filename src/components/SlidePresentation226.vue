<template>
  <div class="slide">
    <div class="heading">CSS - Layout - types de requêtes média</div>
    <div class="content">
      <p>
        Lors de la conception de designs réactifs, les requêtes média les plus
        utilisées se rapportent généralement aux viewport width (width). D'après
        ma propre expérience, je n'ai guère eu besoin d'utiliser les autres
        capacités.
      </p>
      <div class="flex-container">
        <div style="width: 49%">
          <ul>
            <p>
              <span style="font-size: 1.5rem">↪</span> width: La largeur de la
              fenêtre
            </p>
            <p>
              <span style="font-size: 1.5rem">↪</span> height: La hauteur de la
              fenêtre
            </p>
            <p>
              <span style="font-size: 1.5rem">↪</span> device-width: en
              principe, la largeur de l'écran
            </p>
            <p>
              <span style="font-size: 1.5rem">↪</span> device-heigh: en
              principe, la hauteur de l'écran
            </p>
            <p>
              <span style="font-size: 1.5rem">↪</span> orientation: l'appareil
              est orienté en mode portrait ou paysage.
            </p>
          </ul>
        </div>
        <div style="width: 49%">
          <p>
            <span style="font-size: 1.5rem">↪</span> aspect-ratio: Un écran
            large 16:9 peut s'écrire en tant que rapport d'aspect : 16/9
          </p>
          <p>
            <span style="font-size: 1.5rem">↪</span> device-aspect-ratio:: basée
            sur la largeur et la hauteur de la surface de rendu de l'appareil.
          </p>
          <p>
            <span style="font-size: 1.5rem">↪</span> color: Nombre de bits par
            composante de couleur
          </p>
          <p>
            <span style="font-size: 1.5rem">↪</span> resolution: Cette fonction
            peut être utilisée pour tester la résolution de l'écran.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
