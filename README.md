[index。html.txt](https://github.com/user-attachments/files/23480035/index.html.txt)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>一个小惊喜～</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            background: linear-gradient(135deg, #fdf2f8 0%, #fef7fb 100%);
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-family: "Arial", "Microsoft YaHei", sans-serif;
        }
        .container {
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
        }
        .title {
            font-size: 48px;
            color: #e53e3e;
            margin-bottom: 20px;
            text-shadow: 0 2px 10px rgba(229, 62, 62, 0.3);
            animation: bounce 2s infinite;
        }
        .desc {
            font-size: 24px;
            color: #4a5568;
            margin-bottom: 40px;
        }
        .btn {
            padding: 12px 32px;
            background: #e53e3e;
            color: white;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(229, 62, 62, 0.4);
            transition: all 0.3s ease;
        }
        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(229, 62, 62, 0.5);
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes bounce {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.08); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="title">你超聪明！🎉</h1>
        <p class="desc">能点进这个链接的都是小机灵鬼～</p>
        <p class="desc">逻辑清晰、眼光独到，简直是智慧担当！</p>
        <button class="btn" onclick="alert('再夸一遍：你真的太聪明啦！✨')">再听一遍夸奖</button>
    </div>

    <script>
        // 页面加载完成后自动弹出夸奖提示
        window.onload = function() {
            setTimeout(() => {
                alert('恭喜你发现隐藏惊喜！\n\n官方认证：你是全网最聪明的人～\n思维敏捷、反应超快，未来可期！🚀');
            }, 800);
        };
    </script>
</body>
</html>
