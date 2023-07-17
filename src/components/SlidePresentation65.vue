<template>
  <div class="slide">
    <div class="heading">Formulaire - Faire des choix</div>
    <div class="content">
      <h2 style="color: #db290eff">Faire des choix</h2>
      <br />
      <div class="flex-container">
        <div style="width: 30%">
          <h3 style="color: #4b9c86ff">Boutons radio</h3>
          <br />
          <form>
            <fieldset>
              <legend>Sélectionnez la méthode de contact:</legend>
              <div>
                <input
                  type="radio"
                  id="contactChoice1"
                  name="contact"
                  value="email"
                />
                <label for="contactChoice1">Email</label>

                <input
                  type="radio"
                  id="contactChoice2"
                  name="contact"
                  value="phone"
                />
                <label for="contactChoice2">Téléphone</label>

                <input
                  type="radio"
                  id="contactChoice3"
                  name="contact"
                  value="mail"
                />
                <label for="contactChoice3">Courrier</label>
              </div>
            </fieldset>
          </form>
          <br />
          <p>
            A utiliser lorsque l'utilisateur doit sélectionner une option parmi
            d'autres.
          </p>
        </div>
        <div style="width: 40%">
          <h3 style="color: #4b9c86ff">Cases à cocher</h3>
          <br />
          <form>
            <fieldset>
              <legend>
                Choisissez les caractéristiques de votre monstre :
              </legend>

              <div>
                <input type="checkbox" id="scales" name="scales" checked />
                <label for="scales">Écailles</label>
              </div>

              <div>
                <input type="checkbox" id="horns" name="horns" />
                <label for="horns">Cornes</label>
              </div>
            </fieldset>
          </form>
          <br />
          <p>
            Lorsqu'un utilisateur peut sélectionner et désélectionner une ou
            plusieurs options
          </p>
        </div>
        <div style="width: 25%">
          <h3 style="color: #4b9c86ff">Boîtes déroulantes</h3>
          <br />
          <form>
            <label for="cars">Choisissez une voiture :</label>
            <select id="cars" name="cars">
              <option value="volvo">Volvo</option>
              <option value="saab">Saab</option>
              <option value="fiat">Fiat</option>
              <option value="audi">Audi</option>
            </select>
          </form>
          <br />
          <p>
            Lorsqu'un utilisateur doit choisir l'une des options nombre
            d'options dans une liste
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
