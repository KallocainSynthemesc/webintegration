<template>
  <div class="slide">
    <div class="heading">CSS - Layout - Using media queries</div>
    <div class="content">
      <p>
        CSS is the most common place to spot a media query in the wild. They go
        right in the stylesheet in an @media rule that wraps elements with
        conditions for when and where to apply a set of styles when a browser
        matches those conditions.
      </p>
      <h2>HTML</h2>
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
<span style="color: #888888">/* Fenêtres d'affichage d'une largeur comprise entre 320 et 480 px */</span>
<span style="color: #008800; font-weight: bold">@media</span> <span style="color: #007700">only</span> <span style="color: #007700">screen</span> <span style="color: #007700">and</span> <span style="color: #333333">(</span><span style="color: #007700">min-device-width</span><span style="color: #333333">:</span> <span style="color: #007700">320px</span><span style="color: #333333">)</span> <span style="color: #007700">and</span> <span style="color: #333333">(</span><span style="color: #007700">max-device-width</span><span style="color: #333333">:</span> <span style="color: #007700">480px</span><span style="color: #333333">)</span> {
  <span style="color: #BB0066; font-weight: bold">.card</span> {
    <span style="color: #008800; font-weight: bold">background</span><span style="color: #333333">:</span> <span style="color: #6600EE; font-weight: bold">#bada55</span>;
  }
}
</pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
