<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>簡単なホームページ</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            text-align: center;
        }

        header {
            background-color: #0078d7;
            color: white;
            padding: 20px;
        }

        nav {
            background-color: #333;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        main {
            padding: 30px;
        }

        footer {
            background-color: #f0f0f0;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>私のホームページ</h1>
    </header>

    <nav>
        <a href="#">ホーム</a>
        <a href="#">サービス</a>
        <a href="#">お問い合わせ</a>
    </nav>

    <main>
        <h2>ようこそ！</h2>
        <p>これは簡単なWebページです。</p>

        <button onclick="alert('ありがとうございます！')">
            クリック
        </button>
    </main>

    <footer>
        <p>&copy; 2026 私のホームページ</p>
    </footer>

</body>
</html>
