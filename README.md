<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Только для тебя, моя любовь</title>
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@300;700&display=swap" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            font-family: 'Montserrat', sans-serif;
            text-align: center;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
            position: relative;
        }
        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 50px;
            color: #ff3366;
        }
        p {
            font-size: 22px;
            color: #d63384;
        }
        .photo, .video, .snapshot {
            margin: 20px 0;
        }
        img, video {
            width: 100%;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        .hearts {
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 40px;
            color: #ff3366;
            animation: float 3s infinite ease-in-out;
        }
        @keyframes float {
            0%, 100% { transform: translateX(-50%) translateY(0); }
            50% { transform: translateX(-50%) translateY(-10px); }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="hearts">💖💞💖</div>
        <h1>Ты - мое сердце и душа! ❤️</h1>
        <p>Каждый миг с тобой - это магия. Пусть этот сайт напоминает тебе о нашей любви! 💕</p>
        
        <div class="photo">
            <h2>Наши незабываемые моменты 📸</h2>
            <img src="https://sun9-30.userapi.com/impg/ib4CS8F4-H_umcqy_6oiBKyZ0UJgDvDm6onaZw/cKBUHuvlbwI.jpg?size=1280x960&quality=95&sign=c392de5982ab98c282eccc8af1ee2831&type=album" alt="Наше совместное фото">
        </div>
        
        <div class="video">
            <h2>Видео нашей любви 🎥</h2>
            <video controls>
                <source src="https://vk.com/video287926390_456239151?t=0s" type="video/mp4">
            </video>
            </div>
        
        <div class="snapshot">
            <h2>Мгновения счастья 💞</h2>
            <img src="https://sun9-36.userapi.com/impg/inKBzGIIEmvpVmG9nFS2DGEf3382G1nExua7vQ/KCKAZ7nkE0E.jpg?size=960x1280&quality=95&sign=e98d08092c41eb8ad0e298e2c25dbae0&type=album" alt="Снимок с особенного момента">
        </div>
    </div>
</body>
</html>
