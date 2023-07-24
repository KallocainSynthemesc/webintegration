<template>
  <div class="slide">
    <div class="heading">CSS - Layout - Concepts clés</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 45%; margin-left: 4%">
          <h2 class="title">Block element</h2>
          <p>
            Les éléments de niveau bloc commencent toujours sur une nouvelle
            ligne dans la fenêtre du navigateur.
          </p>
          <img
            src="../assets/illustrations/block.svg"
            style="width: 65%; margin-left: 23%"
          />
          <p>
            Voici quelques exemples d'éléments de bloc: &lt;h1&gt;, &lt;p&gt;,
            &lt;ul&gt;, et&lt;li&gt;.
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
<span style="color: #007700">display</span><span style="color: #333333">:</span> <span style="color: #007700">block</span><span style="color: #333333">;</span></pre>
          </div>
        </div>
        <div style="width: 45%; margin-right: 4%">
          <h2 class="title">Inline element</h2>
          <p>
            Les éléments en ligne continueront toujours sur la même ligne que
            les éléments voisins.
          </p>
          <img
            src="../assets/illustrations/inline.svg"
            style="width: 65%; margin-left: 23%"
          />
          <p>
            Exemples d'éléments en ligne: &lt;a&gt;, &lt;b&gt;, &lt;em&gt;, and
            &lt;img&gt;.
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
<span style="color: #007700">display</span><span style="color: #333333">:</span> <span style="color: #007700">inline</span><span style="color: #333333">;</span> <span style="color: #007700">display</span><span style="color: #333333">:</span> <span style="color: #007700">inline-block</span></pre>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
