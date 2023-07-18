<template>
  <div class="slide">
    <div class="heading">CSS - priorité</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 26%">
          <h2 class="title" style="color: #db290eff">Valeurs RGB</h2>
          <p>
            Les valeurs pour le rouge, le vert et le bleu sont exprimées sous
            forme de nombres entre 0 et 255
          </p>
          <div
            style="
              width: 100%;
              background-color: rgb(102, 205, 170);
              height: 35px;
            "
          >
            <p style="color: white; margin-left: 5%">rgb(102,205,170)</p>
          </div>
          <br />
          <p>
            Cette couleur est composée des valeurs suivantes : <br />102
            rouge<br />
            205 vert<br />
            170 bleu
          </p>
        </div>
        <div style="width: 36%; margin-right: 2%; margin-left: 2%">
          <h2 class="title" style="color: #db290eff">Hex Codes</h2>
          <p>
            Les valeurs hexagonales représentent les valeurs pour le rouge, le
            vert et le bleu en code hexadécimal.
          </p>
          <div style="width: 100%; background-color: #66cdaa; height: 35px">
            <p style="color: white; margin-left: 5%">#66cdaa</p>
          </div>
          <br />
          <p>
            La valeur du rouge, 102, est exprimée par 66 en code hexadécimal
            hexadécimal. La valeur 205 du vert est exprimée en cd et la 170 du
            bleu équivaut à du bleu équivaut à aa.
          </p>
        </div>
        <div style="width: 31%">
          <h2 class="title" style="color: #db290eff">Noms de couleurs</h2>
          <p>
            Les couleurs sont représentées par des noms prédéfinis. Cependant,
            elles sont très limitées en nombre
          </p>
          <div
            style="
              width: 100%;
              background-color: MediumAquaMarine;
              height: 35px;
            "
          >
            <p style="color: white; margin-left: 5%">MediumAquaMarine</p>
          </div>
          <br />
          <p>
            Les navigateurs prennent en charge 147 noms de couleurs. Il s'agit
            d'une palette de couleurs limitée
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
