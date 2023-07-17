<template>
  <div class="slide">
    <div class="heading">Links - URL relatif</div>
    <div class="content">
      <div class="linkcontainer">
        <div class="Linktype"><b>Type de lien relatif</b></div>
        <div class="Example"><b>Exemple</b></div>
        <div class="same-folder">
          Même dossier: Pour créer un lien vers un fichier situé dans le même
          dossier, il suffit d'utiliser le nom du fichier.
        </div>
        <div class="child-folder">
          Dossier enfant: Pour un dossier enfant, utilisez le nom du dossier
          enfant, suivi d'une barre oblique, puis du nom du fichier
        </div>
        <div class="grandchild-folder">
          Dossier des petits-enfants: Utilisez le nom du dossier enfant, suivi
          d'une barre oblique, puis le nom du dossier petit-enfant.
        </div>
        <div class="parent-folder">
          Dossier parent: Utilisez ../ pour indiquer le dossier situé au-dessus
          du dossier actuel, puis le faire suivre du nom du fichier
        </div>
        <div class="grandparent-folder">
          Dossier des grands-parents: Répétez le ../ pour indiquer que vous
          voulez remonter deux dossiers (au lieu d'un), puis faites-le suivre du
          nom du fichier.
        </div>
        <div class="example1">
          Lien vers les revues musicales à partir de la page d'accueil sur la
          musique :
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #007700">&lt;a</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;reviews.html&quot;</span><span style="color: #007700">&gt;</span>Reviews<span style="color: #007700">&lt;/a&gt;</span></pre>
          </div>
        </div>
        <div class="example2">
          Pour créer un lien vers les listes de musique à partir de la page
          d'accueil :
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #007700">&lt;a</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;music/listings.html&quot;</span><span style="color: #007700">&gt;</span>Listings<span style="color: #007700">&lt;/a&gt;</span></pre>
          </div>
        </div>
        <div class="example3">
          Pour créer un lien vers les critiques de DVD à partir de la page
          d'accueil :
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #007700">&lt;a</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;movies/dvd/reviews.html&quot;</span><span style="color: #007700">&gt;</span>Reviews<span style="color: #007700">&lt;/a&gt;</span></pre>
          </div>
        </div>
        <div class="example4">
          Pour créer un lien vers la page d'accueil à partir des revues
          musicales :
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #007700">&lt;a</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;../index.html&quot;</span><span style="color: #007700">&gt;</span>Home<span style="color: #007700">&lt;/a&gt;</span></pre>
          </div>
        </div>
        <div class="example5">
          Pour créer un lien vers la page d'accueil à partir des revues de DVD :
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #007700">&lt;a</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;../../index.html&quot;</span><span style="color: #007700">&gt;</span>Home<span style="color: #007700">&lt;/a&gt;</span></pre>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.linkcontainer {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  grid-template-rows: 0.5fr 1fr 1fr 1fr 1fr 1fr;
  gap: 1px 1px;
  grid-template-areas:
    "Linktype Example"
    "same-folder example1"
    "child-folder example2"
    "grandchild-folder example3"
    "parent-folder example4"
    "grandparent-folder example5";
  border: 1px solid #000;
}

.linkcontainer div {
  border: 2px solid #000;
}
.Linktype {
  grid-area: Linktype;
}
.Example {
  grid-area: Example;
}
.same-folder {
  grid-area: same-folder;
}
.child-folder {
  grid-area: child-folder;
}
.grandchild-folder {
  grid-area: grandchild-folder;
}
.parent-folder {
  grid-area: parent-folder;
}
.grandparent-folder {
  grid-area: grandparent-folder;
}
.example1 {
  grid-area: example1;
}
.example2 {
  grid-area: example2;
}
.example3 {
  grid-area: example3;
}
.example4 {
  grid-area: example4;
}
.example5 {
  grid-area: example5;
}
</style>
