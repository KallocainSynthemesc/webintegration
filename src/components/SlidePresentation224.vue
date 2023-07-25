<template>
  <div class="slide">
    <div class="heading">CSS - Layout - Using media queries</div>
    <div class="content">
      <p>
        Les requêtes de média sont généralement associées à CSS, mais elles
        peuvent également être utilisées dans HTML et JavaScript.
      </p>
      <h2>HTML</h2>
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
<span style="color: #007700">&lt;html&gt;</span>
  <span style="color: #007700">&lt;head&gt;</span>
    <span style="color: #888888">&lt;!-- Served to all users --&gt;</span>
    <span style="color: #007700">&lt;link</span> <span style="color: #0000CC">rel=</span><span style="background-color: #fff0f0">&quot;stylesheet&quot;</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;all.css&quot;</span> <span style="color: #0000CC">media=</span><span style="background-color: #fff0f0">&quot;all&quot;</span> <span style="color: #007700">/&gt;</span>
    <span style="color: #888888">&lt;!-- Served to screens that are at least 20em wide --&gt;</span>
    <span style="color: #007700">&lt;link</span> <span style="color: #0000CC">rel=</span><span style="background-color: #fff0f0">&quot;stylesheet&quot;</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;small.css&quot;</span> <span style="color: #0000CC">media=</span><span style="background-color: #fff0f0">&quot;(min-width: 20em)&quot;</span> <span style="color: #007700">/&gt;</span>
    <span style="color: #888888">&lt;!-- Served to screens that are at least 64em wide --&gt;</span>
    <span style="color: #007700">&lt;link</span> <span style="color: #0000CC">rel=</span><span style="background-color: #fff0f0">&quot;stylesheet&quot;</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;medium.css&quot;</span> <span style="color: #0000CC">media=</span><span style="background-color: #fff0f0">&quot;(min-width: 64em)&quot;</span> <span style="color: #007700">/&gt;</span>
    <span style="color: #888888">&lt;!-- Served to screens that are at least 90em wide --&gt;</span>
    <span style="color: #007700">&lt;link</span> <span style="color: #0000CC">rel=</span><span style="background-color: #fff0f0">&quot;stylesheet&quot;</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;large.css&quot;</span> <span style="color: #0000CC">media=</span><span style="background-color: #fff0f0">&quot;(min-width: 90em)&quot;</span> <span style="color: #007700">/&gt;</span>
    <span style="color: #888888">&lt;!-- Served to screens that are at least 120em wide --&gt;</span>
<span style="color: #007700">&lt;/html&gt;</span></pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
