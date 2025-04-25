<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>میرے چاند کے نام 🌙</title>
    <style>
        body {
            font-family: 'Segoe UI', 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            text-align: center;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            color: #5e3a3a;
        }
        
        .container {
            padding: 30px;
            max-width: 800px;
            margin: 0 auto;
        }
        
        h1 {
            color: #d23669;
            font-size: 2.8em;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        .message {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            margin: 20px 0;
            font-size: 1.3em;
            line-height: 1.8;
            border: 1px solid rgba(255, 182, 193, 0.5);
        }
        
        .flower {
            position: absolute;
            font-size: 24px;
            opacity: 0.8;
            animation: float 6s infinite ease-in-out;
            z-index: -1;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-25px) rotate(5deg); }
        }
        
        .heart {
            color: #ff6b81;
            font-size: 28px;
            animation: pulse 1.5s infinite;
            display: inline-block;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.4); }
            100% { transform: scale(1); }
        }
        
        .signature {
            font-style: italic;
            margin-top: 30px;
            font-size: 1.3em;
            color: #8b3a3a;
        }
        
        .rose {
            font-size: 40px;
            margin: 10px;
            animation: spin 4s linear infinite;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .music-control {
            margin-top: 20px;
            font-size: 1em;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>میرے چاند <span style="color: #d23669;">آئیشہ</span> کے نام <span class="heart">❤️</span></h1>
        
        <div class="rose">🌙</div>
        
        <div class="message">
            <p>تم میرے چاند ہو، میرے اندھیروں میں روشنی بن کر آئے ہو۔</p>
            <p>تمہاری ہر بات میرے دل کو چھو جاتی ہے، جیسے کوئی نغمہ ہو جو دھڑکنوں میں سما جائے۔</p>
            <p>تمہاری مسکراہٹ کی روشنی میرے اندھیروں کو دور کر دیتی ہے۔</p>
            <p>تم میرے لیے صرف ایک شخص نہیں ہو، تم میری خوشی ہو، میری امید ہو، میری چاہت ہو۔</p>
            <p><strong>تم میرے دل کی سب سے خوبصورت حقیقت ہو، میرے چاند۔</strong> <span class="heart">💖</span></p>
        </div>
        
        <div class="signature">
            <p>ہمیشہ تمہارا،</p>
            <p style="font-weight: bold; font-size: 1.4em;">ثمر</p>
        </div>
        
        <!-- Music Control (Auto-plays softly) -->
        <div class="music-control">
            <p>♫ پس منظر میں نرم موسیقی چل رہی ہے...</p>
            <audio controls autoplay loop style="width: 80%; max-width: 300px; margin: 10px auto; display: block;">
                <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <small>(Volume is set low for a soft effect)</small>
        </div>
    </div>

    <!-- Animated Flowers -->
    <script>
        const flowers = ['🌸', '🌺', '🌹', '🌻', '🌼', '💐', '🏵️', '🥀', '🌷'];
        const colors = ['#ff6b81', '#ffb8b8', '#d23669', '#ff4757', '#ff7f50', '#ff8c69'];
        
        function createFlower() {
            const flower = document.createElement('div');
            flower.innerHTML = flowers[Math.floor(Math.random() * flowers.length)];
            flower.className = 'flower';
            
            flower.style.left = Math.random() * 100 + 'vw';
            flower.style.top = Math.random() * 100 + 'vh';
            flower.style.fontSize = (Math.random() * 25 + 15) + 'px';
            flower.style.animationDuration = (Math.random() * 6 + 4) + 's';
            flower.style.color = colors[Math.floor(Math.random() * colors.length)];
            
            document.body.appendChild(flower);
            
            setTimeout(() => {
                flower.remove();
            }, 12000);
        }
        
        setInterval(createFlower, 350);

        // Set volume to 20% when page loads
        window.onload = function() {
            document.querySelector('audio').volume = 0.2;
        };
    </script>
</body>
</html>
