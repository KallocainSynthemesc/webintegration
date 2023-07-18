<template>
  <div class="slide">
    <div class="heading">Extra Markup - Footers</div>
    <div class="content">
      <p>le footer était à l'origine défini comme ceci</p>
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
                  <span style="color: #007700">&lt;div</span> <span style="color: #0000CC">id=</span><span style="background-color: #fff0f0">&quot;footer&quot;</span><span style="color: #007700">&gt;</span>
                    <span style="color: #007700">&lt;p&gt;</span><span style="color: #880000; font-weight: bold">&amp;#167;</span><span style="color: #007700">&lt;/p&gt;</span>
                    <span style="color: #007700">&lt;p&gt;</span><span style="color: #880000; font-weight: bold">&amp;#169;</span> 2001<span style="color: #880000; font-weight: bold">&amp;#8211;</span>9 <span style="color: #007700">&lt;a</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;#&quot;</span><span style="color: #007700">&gt;</span>Mark Pilgrim<span style="color: #007700">&lt;/a&gt;&lt;/p&gt;</span>
                  <span style="color: #007700">&lt;/div&gt;</span></pre>
      </div>
      <br />
      <p>
        Mais HTML5 fournit un élément plus spécifique pour cela, l'élément
        &lt;footer&gt;.
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
                  <span style="color: #007700">&lt;footer&gt;</span>
                  <span style="color: #007700">&lt;p&gt;</span><span style="color: #880000; font-weight: bold">&amp;#167;</span><span style="color: #007700">&lt;/p&gt;</span>
                  <span style="color: #007700">&lt;p&gt;</span><span style="color: #880000; font-weight: bold">&amp;#169;</span> 2001<span style="color: #880000; font-weight: bold">&amp;#8211;</span>9 <span style="color: #007700">&lt;a</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;#&quot;</span><span style="color: #007700">&gt;</span>Mark Pilgrim<span style="color: #007700">&lt;/a&gt;&lt;/p&gt;</span>
                  <span style="color: #007700">&lt;/footer&gt;</span></pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
