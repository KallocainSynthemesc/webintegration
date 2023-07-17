<template>
  <div class="slide">
    <div class="heading">Video et Audio - iFrame</div>
    <div class="content">
      <p>
        L'iFrame permet d'intégrer des vidéos, des audios et d'autres sites web.
      </p>
      <div
        class="iFrame-container"
        data-link="https://codesandbox.io/embed/iframe-kfsn5d?fontsize=14&hidenavigation=1&theme=dark"
      >
        <iframe
          ref="myIframe"
          src="favicon.ico"
          style="
            width: 100%;
            height: 95%;
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
