<template>
  <div class="slide">
    <div class="heading">CSS - box</div>
    <div class="content">
      <p>
        Pouvez-vous mettre en œuvre quelque chose de similaire ? Vous pouvez
        importer la famille de polices en utilisant le code suivant dans votre
        code CSS
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
<span style="color: #008800; font-weight: bold">@import</span> <span style="color: #007700">url</span><span style="color: #333333">(</span><span style="background-color: #fff0f0">&#39;https://fonts.googleapis.com/css2?family=Inter:wght@100&amp;display=swap&#39;</span><span style="color: #333333">)</span>;</pre>
      </div>

      <div class="iFrame-container" data-link="exercices\css\border\index.html">
        <iframe
          ref="myIframe"
          src="exercices\css\border\index.html"
          style="
            width: 100%;
            height: 90%;
            border: 0;
            border-radius: 4px;
            overflow: hidden;
          "
        ></iframe>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
