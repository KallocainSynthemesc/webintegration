<template>
  <div class="slide">
    <div class="heading">CSS - Layout - Concepts clés</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 33%">
          <h2>Flux normal</h2>
          <p>
            Chaque élément au niveau du bloc apparaît sur une nouvelle ligne, ce
            qui fait que chaque élément apparaît plus bas dans la page que le
            précédent.
          </p>
          <img
            src="../assets/illustrations/normalflow.svg"
            style="width: 73%"
          />
        </div>
        <div style="width: 33%">
          <h2>Positionnement relatif</h2>
          <p>
            Cette fonction permet de déplacer un élément par rapport à la
            position qu'il occuperait dans le flux normal, en le déplaçant vers
            le haut, la droite, le bas ou la gauche.
          </p>
          <img
            src="../assets/illustrations/relativpos.svg"
            style="width: 73%"
          />
        </div>
        <div style="width: 33%">
          <h2>Positionnement absolut</h2>
          <p>
            Cela positionne l'élément par rapport à l'élément qui le contient.
            Il est retiré du flux normal, ce qui signifie qu'il n'affecte pas la
            position des éléments environnants.
          </p>
          <img
            src="../assets/illustrations/posabsolut.svg"
            style="width: 73%"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
