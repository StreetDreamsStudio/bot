<!DOCTYPE html>
<html>
<head>
    <title>Toggle Text</title>
</head>
<body>
    <h1 id="text">hi</h1>
    <button onclick="toggleText()">Toggle</button>

    <script>
        function toggleText() {
            var textElement = document.getElementById("text");
            if (textElement.innerText === "hi") {
                textElement.innerText = "bye";
            } else {
                textElement.innerText = "hi";
            }
        }
    </script>
</body>
</html>
