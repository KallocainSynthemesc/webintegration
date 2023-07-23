<template>
  <div class="slide">
    <div class="heading">CSS - Sélecteurs d'attribut</div>
    <div class="content">
      <p>
        Il existe également un ensemble de sélecteurs d'attributs qui vous
        permettent de créer des règles s'appliquant aux éléments dont l'attribut
        a une valeur spécifique
      </p>
      <table class="ws-table-all notranslate">
        <tbody>
          <tr>
            <th style="width: 20%">Sélecteur</th>
            <th style="width: 20%">Exemple</th>
            <th>Description de l'exemple</th>
          </tr>
          <tr>
            <td>Existence</td>
            <td class="notranslate">[target]</td>
            <td>Sélectionne tous les éléments avec un attribut target</td>
          </tr>
          <tr>
            <td>Égalité</td>
            <td class="notranslate">[target="_blank"]</td>
            <td>Sélectionne tous les éléments avec target="_blank"</td>
          </tr>
          <tr>
            <td>Contient</td>
            <td class="notranslate">[title~="flower"]</td>
            <td>
              Sélectionne tous les éléments avec un attribut title contenant le
              mot "flower"
            </td>
          </tr>
          <tr>
            <td>Commence par</td>
            <td class="notranslate">[lang|="en"]</td>
            <td>
              Sélectionne tous les éléments avec une valeur d'attribut lang
              commençant par "en"
            </td>
          </tr>
          <tr>
            <td>Préfixe</td>
            <td>a[href^="https"]</td>
            <td>
              Sélectionne chaque élément &lt;a&gt; dont la valeur d'attribut
              href commence par "https"
            </td>
          </tr>
          <tr>
            <td>Sous-chaîne</td>
            <td>a[href$=".pdf"]</td>
            <td>
              Sélectionne chaque élément &lt;a&gt; dont la valeur d'attribut
              href se termine par ".pdf"
            </td>
          </tr>
          <tr>
            <td>Suffixe</td>
            <td>a[href*="bge"]</td>
            <td>
              Sélectionne chaque élément &lt;a&gt; dont la valeur d'attribut
              href contient la sous-chaîne "bge"
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style scoped></style>
