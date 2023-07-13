<!DOCTYPE html>
<html>
<head>
    <title>GitHub README</title>
    <style>
        body {
            background: linear-gradient(to bottom, #ff6699, #cc0099); /* Replace these colors with your desired gradient */
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .marquee {
            width: 100%;
            height: 40px;
            overflow: hidden;
            position: relative;
        }

        .marquee span {
            display: block;
            width: 200%;
            height: 30px;
            position: absolute;
            overflow: hidden;
            animation: marquee 10s linear infinite;
        }

        .marquee span:before, .marquee span:after {
            content: '';
            display: block;
            width: 50%;
            height: 30px;
            position: absolute;
            top: 0;
            background: inherit;
        }

        .marquee span:before {
            left: 0;
            clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
        }

        .marquee span:after {
            right: 0;
            clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
        }

        @keyframes marquee {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }
    </style>
</head>
<body>
    <div class="marquee">
        <span>Nishmal Vadakara</span> <!-- Replace this text with your desired marquee text -->
    </div>
</body>
</html>
