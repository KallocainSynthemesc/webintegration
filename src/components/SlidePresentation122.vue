<template>
  <div class="slide">
    <div class="heading">CSS - Comprendre la couleur</div>
    <div class="content">
      <p>
        Toutes les couleurs d'un écran d'ordinateur sont créées en mélangeant
        des montages de rouge, de vert et de bleu.
      </p>
      <br />
      <div class="flex-container" :style="{ backgroundColor: selectedColor }">
        <div style="width: 50%">
          <p>
            Les éléments &lt;input&gt; de type "color" permettent de
            sélectionner une couleur via une interface ou en saisissant le code
            hexadécimal de la couleur au format "#rrggbb".
          </p>
          <div
            style="
              background: #ffffff;
              overflow: auto;
              width: auto;
              border: solid gray;
              border-width: 0.1em 0.1em 0.1em 0.8em;
              padding: 0.2em 0.6em;
            "
          >
            <pre style="margin: 0; line-height: 125%">
            <span style="color: #007700">&lt;input</span> <span style="color: #0000CC">type=</span><span style="background-color: #fff0f0">&quot;color&quot;</span> <span style="color: #0000CC">value=</span><span style="background-color: #fff0f0">&quot;#ff0000&quot;</span> <span style="color: #007700">/&gt;</span></pre>
          </div>
        </div>
        <div style="width: 15%">
          <p>Choisir la couleur</p>
          <div>
            <input type="color" id="head" name="head" v-model="selectedColor" />
            <label for="head"> Color</label>
          </div>
        </div>
        <div style="width: 20%">
          <img src="../assets/illustrations/RGB.svg" style="width: 100%" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      selectedColor: "#ffffff",
    };
  },
};
</script>
<style scoped></style>
