<template>
  <div class="slide">
    <div class="heading">CSS - Contraste</div>
    <div class="content">
      <p>
        Lors du choix des couleurs d'avant-plan et d'arrière-plan, il est
        important de veiller à ce que le contraste soit suffisant pour que le
        texte soit lisible
      </p>
      <br />
      <div class="flex-container">
        <div style="width: 26%">
          <div style="width: 100%; background-color: lightgray; height: 70px">
            <h2 style="color: white; margin-left: 5%">CONTRASTE FAIBLE</h2>
          </div>
          <br />
          <p>
            Le texte est plus difficile à lire lorsque le contraste entre les
            couleurs d'arrière-plan et de premier plan est faible.
          </p>
        </div>
        <div style="width: 36%; margin-right: 2%; margin-left: 2%">
          <div style="width: 100%; background-color: black; height: 70px">
            <h1 style="color: white; margin-left: 5%">HAUT CONTRASTE</h1>
          </div>
          <br />
          <p>
            Le texte est plus facile à lire lorsque le contraste entre
            l'arrière-plan et le l'arrière-plan et l'avant-plan l'arrière-plan.
          </p>
        </div>
        <div style="width: 31%">
          <div style="width: 100%; background-color: darkgray; height: 70px">
            <h1 style="color: white; margin-left: 5%">MOYEN CONTRASTE</h1>
          </div>
          <br />
          <p>
            Pour les textes longs, une légère réduction du contraste améliore la
            lisibilité.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.flex-container div div {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
