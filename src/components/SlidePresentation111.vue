<template>
  <div class="slide">
    <div class="heading">CSS - Selectors</div>
    <div class="content">
      <table class="tg" style="width: 100%">
        <thead>
          <tr>
            <th class="tg-0lax">
              <span style="font-weight: bold">Selector</span>
            </th>
            <th class="tg-0lax">
              <span style="font-weight: bold">Signification</span>
            </th>
            <th class="tg-0lax">
              <span style="font-weight: bold">Exemple</span>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="tg-0lax">Sélecteur universel</td>
            <td class="tg-0lax">S'applique à tous les éléments du document</td>
            <td class="tg-0lax">* {}</td>
          </tr>
          <tr>
            <td class="tg-0lax">Sélecteur de type</td>
            <td class="tg-0lax">Correspond aux noms des éléments</td>
            <td class="tg-0lax">h1, h2, h3 {}</td>
          </tr>
          <tr>
            <td class="tg-0lax">Sélecteur de classe</td>
            <td class="tg-0lax">
              Correspond à un élément dont l'attribut a une valeur qui
              correspond à celle spécifiée après le symbole du point (ou du
              point final)
            </td>
            <td class="tg-0lax">.note {}<br />p.note {}<br /></td>
          </tr>
          <tr>
            <td class="tg-0lax">Sélecteur d'ID</td>
            <td class="tg-0lax">
              Correspond à un élément dont l'attribut a une valeur qui
              correspond à celle spécifiée après le dièse
            </td>
            <td class="tg-0lax">#introduction {}</td>
          </tr>
          <tr>
            <td class="tg-0lax">Sélecteur d'enfant<br /></td>
            <td class="tg-0lax">
              Correspond à un élément qui est un enfant direct d'un autre
            </td>
            <td class="tg-0lax">li&gt;a {}</td>
          </tr>
          <tr>
            <td class="tg-0lax">Sélecteur de descendants</td>
            <td class="tg-0lax">
              Correspond à un élément qui est un descendant d'un autre élément
              spécifié (et pas seulement un enfant direct de cet élément)
            </td>
            <td class="tg-0lax">p a {}</td>
          </tr>
          <tr>
            <td class="tg-0lax">Adjacent Sibling Selector</td>
            <td class="tg-0lax">
              Correspond à un élément qui est le frère suivant d'un autre
            </td>
            <td class="tg-0lax">h1+p {}</td>
          </tr>
          <tr>
            <td class="tg-0lax">General sibling selector<br /></td>
            <td class="tg-0lax">
              Correspond à un élément qui est un frère d'un autre, bien qu'il ne
              ne doit pas nécessairement être l'élément précédent
            </td>
            <td class="tg-0lax">h1~p {}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style scoped>
tr td:first-child {
  color: #db290eff;
}

tr td:last-child {
  color: #db290eff;
}
</style>
