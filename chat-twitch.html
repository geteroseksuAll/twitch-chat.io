<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="css/chat.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Twitch chat</title>
    <script src="https://cdn.jsdelivr.net/npm/comfy.js@latest/dist/comfy.min.js"></script>
    <style>
        html,
    body {
        margin: 0;
        font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        color:#19181A  ;
    }

    #chat {
        width:400px;
        max-height: 300px;
        overflow-y: auto;
        display: flex;
        flex-direction: column-reverse;
    }
    
    #chat::-webkit-scrollbar {
        display: none;
    }
    #chat ul {
        list-style-type: none;
        list-style-position: outside;
    }
    #chat li {
        background-color:#B19F9E;
        box-sizing: border-box;
        padding: 1rem 10px;
        margin-bottom: 10px;
        border:solid #19181A 4px
    }
    #chat li.mod {
        background-color: hsl(168, 47%, 77%);
        color: hsl(166, 86%, 58%);
    }
    #chat li.sub {
        background-color: hsl(168, 47%, 77%);
        color: hsl(235, 62%, 32%);
    }
    #chat blockquote {
        font-size: 1.2rem;
    }
    /* Animation */
    @keyframes slide-in-left {
        from {
            transform: translateX(400px);
            opacity: 0;
        }
        to {
            transform: translateX(0);
            opacity: 2;
        }
    }
    @keyframes opacity-max {
        from {
            opacity: 1;
            visibility:visible;
        }
        to {
            opacity: 0;
            visibility:hidden;
        }
    }
    #chat li:not(:last-of-type) {
        animation: opacity-max 10s ease-in;
        visibility:hidden;
        transition:ease-in 10s;
    }
    #chat li:last-of-type {
        animation-name: slide-in-left 0.15s ease-in;
        animation: opacity-max 10s ease-in;
        visibility:hidden;
        transition:ease-in 10s;
    }
    </style>
</head>

<body>
    <div id="chat">
        <ul>
        </ul>
    </div>
</body>

<script>
    var chat = document.querySelector("#chat>ul");

    ComfyJS.onChat = (user, message, flags, self, extra) => {
        var newMessage = document.createElement("li");

        if (message.mod) {
            newMessage.classList.add('mod');
        }

        if (message.subscriber) {
            newMessage.classList.add('sub');
        }

        var text = document.createElement("blockquote");

        newMessage.innerText = user;
        text.innerText = message;

        newMessage.append(text);
        chat.append(newMessage);
    }

    ComfyJS.Init("dope_dealer228");
</script>

</html>
