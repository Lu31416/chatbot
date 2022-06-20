# chatbot
# link to chatbot
<script SameSite="None; Secure" src="https://cdn.landbot.io/landbot-widget/landbot-widget-1.0.0.js"></script>
<script>
  var myLandbot = new LandbotLivechat({
    index: 'https://chats.landbot.io/v2/H-694449-5KA2W3JHIME0RMDO/index.html',
  });
</script><script>
  // Show a proactive message on landbot load
  myLandbot.on('landbot-load', function() {
    myLandbot.sendProactive({
  "message": "",
  "author": "landbot",
  "avatar": "https://storage.googleapis.com/media.helloumi.com/brands/helloumi.png",
  "extra": {
    "hide_textbox": true
  }
});
  });
</script>
