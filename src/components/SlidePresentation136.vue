<template>
  <div class="slide">
    <div class="heading">CSS - Unités de longueur relative</div>
    <div class="content">
      <p>
        Relative length units are used to express quantities relative to
        something else, such as the font size of the parent element or the size
        of the display area.
      </p>
      <table>
        <thead>
          <tr>
            <th>Unité</th>
            <th>Relative à</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><code>em</code></td>
            <td>
              Pour les propriétés typographiques comme
              <a href="/fr/docs/Web/CSS/font-size"><code>font-size</code></a
              >, relative à la taille de la police de l'élément parent. Pour les
              autres propriétés comme
              <a href="/fr/docs/Web/CSS/width"><code>width</code></a
              >, relative à la taille de la police de l'élément;
            </td>
          </tr>
          <tr>
            <td><code>ex</code></td>
            <td>La hauteur d'x de la police de l'élément.</td>
          </tr>
          <tr>
            <td><code>ch</code></td>
            <td>
              La
              <a
                href="https://fr.wikipedia.org/wiki/Chasse_(typographie)"
                class="external"
                target="_blank"
                >chasse/avance</a
              >
              du glyphe « 0 » pour la police de l'élément.
            </td>
          </tr>
          <tr>
            <td><code>rem</code></td>
            <td>La taille de la police pour l'élément racine.</td>
          </tr>
          <tr>
            <td><code>lh</code></td>
            <td>La hauteur de ligne pour l'élément.</td>
          </tr>
          <tr>
            <td><code>vw</code></td>
            <td>
              1% de la largeur du <i lang="en">viewport</i> (la zone
              d'affichage).
            </td>
          </tr>
          <tr>
            <td><code>vh</code></td>
            <td>
              1% de la hauteur du <i lang="en">viewport</i> (la zone
              d'affichage).
            </td>
          </tr>
          <tr>
            <td><code>vmin</code></td>
            <td>
              1% de la plus petite dimension du <i lang="en">viewport</i> (la
              zone d'affichage).
            </td>
          </tr>
          <tr>
            <td><code>vmax</code></td>
            <td>
              1% de la plus grande dimension du <i lang="en">viewport</i> (la
              zone d'affichage).
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style scoped></style>
