<template>
  <div class="slide">
    <div class="heading">CSS - Layout - Grid</div>
    <div class="content">
      <p>
        Nous avions l'habitude de créer des grilles avec la propriété float.
        C'était une véritable plaie. Aujourd'hui, nous disposons de grid et de
        flexbox comme meilleures alternatives. float peut toujours être utilisé
        pour que le texte circule autour des images, mais c'est à peu près tout.
      </p>
      <div class="app-layout">
        <div class="tweets">Tweets</div>
        <div class="replies">Replies</div>
        <div class="search">Search</div>
        <div class="messages">Messages</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.app-layout {
  display: grid; /* 1 */
  grid-template-columns: 1fr 1fr 1fr 1fr; /* 2 */
  grid-template-rows: 30vh; /* 3 */
}

.tweets {
  background-color: lightgreen;
}
.replies {
  background-color: lightcoral;
}

.search {
  background-color: lightseagreen;
}

.messages {
  background-color: lightpink;
}
</style>
