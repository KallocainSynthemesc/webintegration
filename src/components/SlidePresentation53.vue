<template>
  <div class="slide">
    <div class="heading">Images - HTML5 - figure et figurecaption</div>
    <div class="content">
      <p>
        Pouvez-vous reproduire ce site?
        <a href="/exercices/photos/images.zip" download="images.zip"
          ><img
            src="../assets/illustrations/image-logo.svg"
            style="width: 5%"
          />Télécharger les images</a
        >
      </p>
      <div class="iFrame-container" data-link="exercices\links\index.html">
        <iframe
          ref="myIframe"
          src="exercices\photos\index.html"
          style="
            width: 100%;
            height: 90%;
            border: 0;
            border-radius: 4px;
            overflow: hidden;
          "
          title="priceless-microservice-jvlqnq"
          allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
          sandbox="allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts"
        ></iframe>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
