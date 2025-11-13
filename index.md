<html> 
<head>
    <link rel="shortcut icon" type="image/x-icon" href="favicon.ico?">
    <style>
        html, body, #twitch-embed {
            width: 100%;
            height: 100%;
            margin: 0;
        }
        body {
            background-image: url('../skeleton-dance-skeleton.gif');
            background-repeat: repeat;
            background-color: #f0f0f0;
        }
        #twitch-embed {
            display: flex;
            align-items: center;
            justify-content: center;
        }
        iframe {
            width: 75%;
            height: 75%;
        }
    </style>
</head>
<body>
    <div id="twitch-embed"></div>
    <script src="https://embed.twitch.tv/embed/v1.js"></script>
    <script type="text/javascript">
        new Twitch.Embed("twitch-embed", {
            width: 1260,
            height: 660,
            channel: "vargskelethor",
            parent: ["hahaha.bald.stream"]
        });
    </script>
</body>
</html>
