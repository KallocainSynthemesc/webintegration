<template>
  <div class="slide">
    <div class="heading">CSS - Typeface</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 31%">
          <h2 class="title" style="color: #db290eff">Serif</h2>
          <p>
            Les polices avec empattement comportent des détails supplémentaires
            l'extrémité des traits principaux des lettres. Ces détails sont
            appelés "serifs"
          </p>
          <h2 class="sub-title" style="font-family: serif; color: #66cdaa">
            im
          </h2>
        </div>
        <div style="width: 31%; margin-right: 2%; margin-left: 2%">
          <h2 class="title" style="color: #db290eff">sans-serif</h2>
          <p>
            Les polices sans-serif ont des extrémités des lettres et, par
            conséquent, ont un design beaucoup plus net
          </p>
          <h2 class="sub-title" style="font-family: sans-serif; color: #66cdaa">
            im
          </h2>
        </div>
        <div style="width: 31%">
          <h2 class="title" style="color: #db290eff">Monospace</h2>
          <p>Toutes les lettres d'une police monospace ont la même largeur.</p>
          <h2 class="sub-title" style="font-family: monospace; color: #66cdaa">
            im
          </h2>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.flex-container div .sub-title {
  color: #66cdaa;
  font-size: 7rem;
}
</style>
