<!DOCTYPE html>
<html>
  <head>
    <title>Hello Webpage</title>
    <script>
      function callUnityFunction() {
        // Use Unity's WebGL API to send a message to Unity
        UnitySendMessage("YourUnityGameObjectName", "YourUnityFunctionName", "Message from web page");
      }
    </script>
  </head>
  <body>
    <h1>Hello</h1>
    <button onclick="callUnityFunction()">Trigger Unity Function</button>
  </body>
</html>
