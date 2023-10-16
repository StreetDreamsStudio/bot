<!DOCTYPE html>
<html>
<head>
    <title>Toggle Text</title>
</head>
<body>
    <h1 id="text">hi</h1>
    <button id="toggleButton">Toggle</button>

    <script>
        var textElement = document.getElementById("text");
        var toggleButton = document.getElementById("toggleButton");

        toggleButton.addEventListener("click", function() {
            if (textElement.innerText === "hi") {
                textElement.innerText = "bye";
            } else {
                textElement.innerText = "hi";
            }
        });
    </script>
</body>
</html>
