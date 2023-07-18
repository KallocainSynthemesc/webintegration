<template>
  <div class="slide">
    <div class="heading">CSS - priorité</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 26%">
          <h2 class="title" style="color: #db290eff">DERNIÈRE RÈGLE</h2>
          <p>
            Si les deux sélecteurs sont identiques, le dernier des deux aura la
            priorité.
          </p>
          <!-- HTML generated using hilite.me -->
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
<span style="color: #007700">i</span> {
    <span style="color: #008800; font-weight: bold">color</span><span style="color: #333333">:</span> <span style="color: #007020">green</span>;
}
<span style="color: #007700">i</span> {<span style="color: #888888">/* Cette règle est appliquée*/</span>
    <span style="color: #008800; font-weight: bold">color</span><span style="color: #333333">:</span> <span style="color: #007020">red</span>;
}</pre>
          </div>
        </div>
        <div style="width: 36%; margin-right: 2%; margin-left: 2%">
          <h2 class="title" style="color: #db290eff">SPÉCIFICITÉ</h2>
          <p>
            Si un sélecteur est plus spécifique que les autres, la règle la plus
            spécifique aura la priorité sur les règles plus générales
          </p>
          <!-- HTML generated using hilite.me -->
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
<span style="color: #007700">p</span> <span style="color: #007700">b</span> {<span style="color: #888888">/*p b est plus spécifique que p*/</span>
    <span style="color: #008800; font-weight: bold">color</span><span style="color: #333333">:</span> <span style="color: #007020">violet</span>;
}
<span style="color: #007700">p</span><span style="color: #0066BB; font-weight: bold">#intro</span> {<span style="color: #888888">/*p#intro est plus spécifique que p*/</span>
    <span style="color: #008800; font-weight: bold">font-size</span><span style="color: #333333">:</span> <span style="color: #6600EE; font-weight: bold">100</span><span style="color: #333333">%</span>;
}
<span style="color: #007700">p</span> {
    <span style="color: #008800; font-weight: bold">font-size</span><span style="color: #333333">:</span> <span style="color: #6600EE; font-weight: bold">75</span><span style="color: #333333">%</span>;
}</pre>
          </div>
        </div>
        <div style="width: 31%">
          <h2 class="title" style="color: #db290eff">IMPORTANT</h2>
          <p>
            Vous pouvez ajouter !important après toute valeur de propriété pour
            indiquer qu'elle doit être considérée comme plus importante que les
            autres règles qui s'appliquent au même élément.
          </p>
          <!-- HTML generated using hilite.me -->
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
<span style="color: #007700">p</span> <span style="color: #007700">b</span> { <span style="color: #888888">/*!important sera appliqué*/</span>
    <span style="color: #008800; font-weight: bold">color</span><span style="color: #333333">:</span> <span style="color: #007020">blue</span> <span style="color: #557799">!important</span>;
}
<span style="color: #007700">p</span> <span style="color: #007700">b</span> {
    <span style="color: #008800; font-weight: bold">color</span><span style="color: #333333">:</span> <span style="color: #007020">violet</span>;
}</pre>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
