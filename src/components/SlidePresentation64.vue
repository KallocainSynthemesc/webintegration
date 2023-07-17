<template>
  <div class="slide">
    <div class="heading">Formulaire - Ajout de texte</div>
    <div class="content">
      <p>
        Il existe plusieurs types de contrôles de formulaires vous pouvez
        utiliser pour collecter des informations auprès des visiteurs de votre
        site
      </p>
      <h2 style="color: #db290eff">Ajout de texte</h2>
      <br />
      <div class="flex-container">
        <div style="width: 30%">
          <h3 style="color: #4b9c86ff">Saisie de texte</h3>
          <br />
          <form>
            <label for="fname">Prénom :</label><br />
            <input type="text" id="fname" name="fname" value="John" /><br />
          </form>
          <br />
          <p>
            Utilisé pour une seule ligne de texte telle que les adresses
            électroniques et les noms
          </p>
        </div>
        <div style="width: 35%">
          <h3 style="color: #4b9c86ff">Saisie du mot de passe</h3>
          <br />
          <form>
            <label for="pass">Mot de passe (8 caractères minimum):</label><br />
            <input
              type="password"
              id="pass"
              name="password"
              minlength="8"
              required
            />
          </form>
          <br />
          <p>
            Comme une zone de texte d'une seule ligne, mais masque les
            caractères saisis
          </p>
        </div>
        <div style="width: 33%">
          <h3 style="color: #4b9c86ff">Zone de texte</h3>
          <br />
          <form>
            <label for="story">Racontez-nous votre histoire :</label>

            <textarea id="story" name="story" rows="5" cols="33">
C'était une nuit sombre et orageuse...
            </textarea>
          </form>
          <br />
          <p>
            Pour les zones de texte plus longues, telles que les messages et les
            commentaires
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
