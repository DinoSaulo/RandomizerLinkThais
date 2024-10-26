# RandomizerLinkThais

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random Redirect</title>
    <script type="text/javascript">
        function randomRedirect() {
            var links = [
                "https://link1.com",
                "https://link2.com",
                "https://link3.com",
                "https://link4.com"
            ];
            var randomLink = links[Math.floor(Math.random() * links.length)];
            window.location.href = randomLink;
        }
    </script>
</head>
<body onload="randomRedirect()">
</body>
</html>