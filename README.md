
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>میرے چاند آئیشہ کے نام 🌙</title>
    <style>
        body {
            font-family: 'Nastaliq', 'Segoe UI', sans-serif;
            background: linear-gradient(to bottom, #fff5f5, #ffecec);
            text-align: center;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            color: #333;
            line-height: 1.8;
        }

        .container {
            padding: 20px;
            max-width: 700px;
            margin: 0 auto;
            position: relative;
        }

        h1 {
            color: #c72c41;
            font-size: 2.5em;
            margin: 30px 0;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        .message-box {
            background: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            margin: 20px 0;
            border: 1px solid #ffd6d6;
            position: relative;
            overflow: hidden;
        }

        .message-box::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(to right, #ff9a9e, #fad0c4, #ff9a9e);
        }

        .signature {
            font-style: italic;
            margin-top: 40px;
            color: #8b3a3a;
            font-size: 1.2em;
        }

        .petal {
            position: absolute;
            background-size: contain;
            background-repeat: no-repeat;
            opacity: 0.7;
            z-index: -1;
            animation: falling linear infinite;
        }

        @keyframes falling {
            0% {
                transform: translateY(-10vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 0.7;
            }
            90% {
                opacity: 0.7;
            }
            100% {
                transform: translateY(110vh) rotate(360deg);
                opacity: 0;
            }
        }

        .moon {
            font-size: 50px;
            display: inline-block;
            margin: 20px 0;
            animation: glow 3s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #e3f2fd, 0 0 20px #bbdefb;
            }
            to {
                text-shadow: 0 0 10px #fff, 0 0 20px #e3f2fd, 0 0 30px #bbdefb, 0 0 40px #90caf9;
            }
        }

        .heart-beat {
            animation: heartbeat 1.5s infinite;
            display: inline-block;
            color: #ff6b81;
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            25% { transform: scale(1.1); }
            50% { transform: scale(1); }
            75% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>میرے چاند <span style="color: #d23669;">آئیشہ</span> کے نام</h1>
        
        <div class="moon">🌙</div>
        
        <div class="message-box">
            <p style="font-size: 1.3em; margin-bottom: 25px;">میرے چاند، میرے سورج، میری ہر خوشی...</p>
            
            <p>جب بھی تم مسکراتی ہو، میرے دل کی دھڑکنیں تمہارے نام لینے لگتی ہیں۔</p>
            
            <p>تمہاری آنکھوں میں وہ جادو ہے جو مجھے تمہارے علاوہ کچھ نہیں دیکھنے دیتا۔</p>
            
            <p>تم نہ صرف میرے دل میں ہو بلکہ تم میرے ہر خیال، ہر خواب، ہر تمنا ہو۔</p>
            
            <p style="margin-top: 30px; font-weight: bold;">تم میرے لیے صرف ایک لفظ نہیں ہو... تم میرے لیے پوری ایک کہانی ہو <span class="heart-beat">❤️</span></p>
        </div>
        
        <div class="signature">
            <p>ہمیشہ تمہارے،</p>
            <p style="font-weight: bold; font-size: 1.4em; margin-top: 5px;">ثمر</p>
        </div>
    </div>

    <!-- Falling Petals Animation -->
    <script>
        function createPetal() {
            const petal = document.createElement('div');
            petal.className = 'petal';
            
            // Random petal styles
            const types = ['🌸', '🌹', '🍂', '🌼'];
            const sizes = ['20px', '25px', '18px', '22px'];
            const durations = [15, 20, 18, 22];
            
            petal.innerHTML = types[Math.floor(Math.random() * types.length)];
            petal.style.left = Math.random() * 100 + 'vw';
            petal.style.fontSize = sizes[Math.floor(Math.random() * sizes.length)];
            petal.style.animationDuration = durations[Math.floor(Math.random() * durations.length)] + 's';
            petal.style.animationDelay = Math.random() * 5 + 's';
            
            document.body.appendChild(petal);
            
            // Remove petal after animation completes
            setTimeout(() => {
                petal.remove();
            }, durations[Math.floor(Math.random() * durations.length)] * 1000);
        }
        
        // Create petals periodically
        setInterval(createPetal, 300);
        
        // Initial petals
        for (let i = 0; i < 15; i++) {
            setTimeout(createPetal, i * 200);
        }
    </script>
</body>
</html>
