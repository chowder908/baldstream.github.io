<html> 
<head>
    <link rel="shortcut icon" type="image/x-icon" href="favicon.ico?">
    <style>
        body {
            background-image: url('../skeleton-dance-skeleton.gif');
            background-repeat: repeat;
            background-color: #f0f0f0;
        }
        #twitch-embed {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100%;
            width: 100%;
        }
    </style>
</head>
<body>
    <div id="twitch-embed"></div>
    <script src="https://embed.twitch.tv/embed/v1.js"></script>
    <script type="text/javascript">
        new Twitch.Embed("twitch-embed", {        
            channel: "vargskelethor",
            parent: ["hahaha.bald.stream"]
            width: 1280,
            height: 720,
        });
    </script>
</body>
</html>
