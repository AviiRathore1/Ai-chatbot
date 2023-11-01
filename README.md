<html>
  <head>
  <meta name="viewport" content="width=device-width, initial-scale=1 viewport-fit=cover, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <style>
      body {
        background-color: white;
        margin: 0 auto;
        display: -ms-flexbox;
        display: -webkit-flex;
        display: flex;
        flex-direction: column;
        height: 100vh;
      }
      #bp-web-widget-container {
        max-height: 90%;
        width: 481px;
        margin: auto;
        flex-grow: 1;
      }
      #bp-web-widget-container div {
        height: 100%;
      }
      .webchatIframe {
        position: relative !important;
      }
    </style>
    <title>Banking ChatBot FYP2 Project</title>
  </head>
  <body>

  <script src="https://cdn.botpress.cloud/webchat/v1/inject.js"></script>
<script>
  window.botpressWebChat.init({
      "composerPlaceholder": "Ask Our A.I",
      "botConversationDescription": "Customer Service Assistant",
      "botId": "607d3b2e-adae-40ed-a60a-725638245cc0",
      "hostUrl": "https://cdn.botpress.cloud/webchat/v1",
      "messagingUrl": "https://messaging.botpress.cloud",
      "clientId": "607d3b2e-adae-40ed-a60a-725638245cc0",
      "lazySocket": true,
      "botName": "Banking ChatBot",
      "avatarUrl": "https://i.imgur.com/YZtsX1W.jpg",
      "stylesheet": "https://webchat-styler-css.botpress.app/prod/4e20bd53-7547-4b38-8a25-9a3106eecc3c/v15264/style.css",
      "frontendVersion": "v1",
      "useSessionStorage": true,
      "enableConversationDeletion": true,
      "theme": "prism",
      "themeColor": "#2563eb",
      "hideWidget": true,
      "disableAnimations": true,
      "closeOnEscape": false,
      "showConversationsButton": false,
      "enableTranscriptDownload": false,
      "className": "webchatIframe",
      "containerWidth": "100%25",
      "layoutWidth": "100%25",
      "showCloseButton": false
  });
window.botpressWebChat.onEvent(function () { window.botpressWebChat.sendEvent({ type: 'show' }) }, ['LIFECYCLE.LOADED']);
</script>

  </body>
</html>
