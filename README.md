<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Good Luck Message for Arsheen Umar</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            font-family: "Cursive", sans-serif;
        }

        .container {
            text-align: center;
            position: relative;
        }

        .signature {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            color: #d6336c;
            margin-bottom: 20px;
            animation: fadeIn 2s ease-in-out;
        }

        .typewriter {
            font-family: 'Courier New', monospace;
            font-size: 1.2rem;
            color: #444;
            display: inline-block;
            white-space: nowrap;
            overflow: hidden;
            border-right: 2px solid #444;
            animation: typing 3.5s steps(40, end), blink 0.5s step-end infinite;
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink {
            from, to { border-color: transparent; }
            50% { border-color: #444; }
        }

        .flowers {
            position: absolute;
            bottom: -50px;
            width: 100%;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .flower {
            width: 60px;
            height: 60px;
            background-image: url('https://example.com/rose.png'); /* Replace with actual rose image URL */
            background-size: cover;
            background-repeat: no-repeat;
            animation: popUp 2s ease-out forwards;
        }

        @keyframes popUp {
            from {
                transform: translateY(100px) scale(0);
                opacity: 0;
            }
            to {
                transform: translateY(0) scale(1);
                opacity: 1;
            }
        }

        .green-branches {
            position: absolute;
            bottom: -30px;
            width: 100%;
            height: 200px;
            background: url('https://example.com/branches.png') no-repeat center;
            background-size: contain;
            animation: grow 3s ease-in-out forwards;
        }

        @keyframes grow {
            from {
                transform: scaleY(0);
            }
            to {
                transform: scaleY(1);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="signature">Arsheen Umar, you are a wonderful Lady. May Allah Bless you with Success and Blessings.</div>
        <div class="typewriter">This is a special message to celebrate you! You are truly amazing and kind-hearted. Your wonderful nature brightens the lives of everyone around you.</div>
        <div class="typewriter">Stay the wonderful woman you are, and may all your dreams come true. <br><strong>- From M. Mudassar Ashraf</strong></div>
        <div class="green-branches"></div>
        <div class="flowers">
            <div class="flower" style="animation-delay: 0.2s;"></div>
            <div class="flower" style="animation-delay: 0.4s;"></div>
            <div class="flower" style="animation-delay: 0.6s;"></div>
            <div class="flower" style="animation-delay: 0.8s;"></div>
            <div class="flower" style="animation-delay: 1s;"></div>
        </div>
    </div>
</body>
</html>
