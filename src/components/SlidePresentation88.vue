<template>
  <div class="slide">
    <div class="heading">Extra Markup - Commentaires en html</div>
    <div class="content">
      <p>
        Si vous voulez ajouter un commentaire à votre code qui sera pas visible
        dans le navigateur de l'utilisateur, vous vous pouvez ajouter le texte
        entre ces caractères :
      </p>
      <div
        style="
          background: #f8f8f8;
          overflow: auto;
          width: auto;
          border: solid gray;
          border-width: 0.1em 0.1em 0.1em 0.8em;
          padding: 0.2em 0.6em;
        "
      >
        <pre
          style="margin: 0; line-height: 125%"
        ><span style="color: #008800; font-style: italic">&lt;!-- le commentaire va ici --&gt;</span></pre>
      </div>
      <div
        class="iFrame-container"
        data-link="https://codesandbox.io/embed/comments-nfydws?fontsize=14&hidenavigation=1&theme=dark"
      >
        <iframe
          ref="myIframe"
          src="favicon.ico"
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
