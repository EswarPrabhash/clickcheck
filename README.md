<!DOCTYPE html>
<html>
<head>
    <title>Token Page</title>
</head>
<body>
    <h1>Click the Button to Receive Token</h1>
    <button id="getToken">Receive Token</button>

    <script>
        document.getElementById('getToken').onclick = function() {
            // Replace with your Glide App's link including the "token received" parameter
            window.location.href = "https://go.glideapps.com/app/3fHhyYRmJlvaPKsGKxTi?token_received=true";
        };
    </script>
</body>
</html>
