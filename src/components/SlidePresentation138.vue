<template>
  <div class="slide">
    <div class="heading">CSS - font type</div>
    <div class="content">
      <p>
        Les différents navigateurs prennent en charge des formats différents
        pour les polices, il se peut donc que vous deviez fournir la police en
        plusieurs variantes pour qu'elle soit accessible à tous les navigateurs.
      </p>
      <table class="browserref notranslate">
        <tbody>
          <tr>
            <th style="width: 15%; font-size: 22px; text-align: left">
              Font format
            </th>
            <th
              style="
                width: 15%;
                background-image: url('https://www.w3schools.com/images/compatible_edge.png');
                background-repeat: no-repeat;
              "
              title="Internet Explorer / Edge"
            ></th>
            <th
              style="
                width: 17%;
                background-image: url('https://www.w3schools.com/images/compatible_chrome.png');
                background-repeat: no-repeat;
              "
              class="bsChrome"
              title="Chrome"
            ></th>
            <th
              style="
                width: 18%;
                background-image: url('https://www.w3schools.com/images/compatible_firefox.png');
                background-repeat: no-repeat;
              "
              class="bsFirefox"
              title="Firefox"
            ></th>
            <th
              style="
                width: 18%;
                background-image: url('https://www.w3schools.com/images/compatible_safari.png');
                background-repeat: no-repeat;
              "
              class="bsSafari"
              title="Safari"
            ></th>
            <th
              style="
                width: 17%;
                background-image: url('https://www.w3schools.com/images/compatible_opera.png');
                background-repeat: no-repeat;
              "
              class="bsOpera"
              title="Opera"
            ></th>
          </tr>
          <tr>
            <td>TTF/OTF</td>
            <td>9.0*</td>
            <td>4.0</td>
            <td>3.5</td>
            <td>3.1</td>
            <td>10.0</td>
          </tr>
          <tr>
            <td>WOFF</td>
            <td>9.0</td>
            <td>5.0</td>
            <td>3.6</td>
            <td>5.1</td>
            <td>11.1</td>
          </tr>
          <tr>
            <td>WOFF2</td>
            <td>14.0</td>
            <td>36.0</td>
            <td>39.0</td>
            <td>10.0</td>
            <td>26.0</td>
          </tr>
          <tr>
            <td>SVG</td>
            <td><span class="deprecated">Not supported</span></td>
            <td><span class="deprecated">Not supported</span></td>
            <td><span class="deprecated">Not supported</span></td>
            <td>3.2</td>
            <td><span class="deprecated">Not supported</span></td>
          </tr>
          <tr>
            <td>EOT</td>
            <td>6.0</td>
            <td><span class="deprecated">Not supported</span></td>
            <td><span class="deprecated">Not supported</span></td>
            <td><span class="deprecated">Not supported</span></td>
            <td><span class="deprecated">Not supported</span></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style scoped></style>
