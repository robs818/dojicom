<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>個人網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f4f3;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #40e0d0; /* 土耳其綠 */
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 1em 0;
        }
        nav a {
            margin: 0 1em;
            color: #333;
            text-decoration: none;
        }
        section {
            padding: 2em;
            text-align: center;
        }
        .video-list img {
            width: 100%;
            max-width: 300px;
            height: auto;
            margin: 1em;
            cursor: pointer;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>歡迎來到我的個人網站</h1>
        <p>分享我的影片和創作</p>
    </header>
    <nav>
        <a href="#home">首頁</a>
        <a href="#videos">影片展示</a>
        <a href="#about">關於我</a>
        <a href="#contact">聯繫方式</a>
    </nav>
    <section id="home">
        <h2>首頁</h2>
        <p>這裡展示我的最新影片</p>
        <!-- 影片展示區域 -->
        <div class="video-list">
            <a href="https://www.youtube.com/channel/你的頻道ID">
                <img src="影片縮略圖URL" alt="影片標題">
            </a>
        </div>
    </section>
    <section id="videos">
        <h2>影片展示</h2>
        <div class="video-list">
            <!-- 影片列表 -->
            <a href="https://www.youtube.com/watch?v=影片ID1">
                <img src="影片縮略圖URL1" alt="影片標題1">
            </a>
            <a href="https://www.youtube.com/watch?v=影片ID2">
                <img src="影片縮略圖URL2" alt="影片標題2">
            </a>
            <!-- 更多影片 -->
        </div>
    </section>
    <section id="about">
        <h2>關於我</h2>
        <p>這裡是我的個人介紹和背景資訊。</p>
    </section>
    <section id="contact">
        <h2>聯繫方式</h2>
        <form>
            <label for="name">姓名：</label>
            <input type="text" id="name" name="name"><br><br>
            <label for="email">電子郵件：</label>
            <input type="email" id="email" name="email"><br><br>
            <label for="message">訊息：</label><br>
            <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
            <input type="submit" value="提交">
        </form>
        <p>或通過社交媒體聯繫我：</p>
        <a href="你的社交媒體連結">社交媒體連結</a>
    </section>
    <footer>
        <p>&copy; 2024 我的個人網站. 保留所有權利。</p>
    </footer>
</body>
</html>
