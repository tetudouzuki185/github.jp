<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>お問い合わせフォーム付きホームページ</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: "Yu Gothic", sans-serif;
        background: #f4f4f4;
        color: #333;
    }

    header {
        background: #0078d7;
        color: white;
        text-align: center;
        padding: 30px;
    }

    nav {
        background: #005fa3;
    }

    nav ul {
        display: flex;
        justify-content: center;
        list-style: none;
    }

    nav ul li a {
        display: block;
        color: white;
        text-decoration: none;
        padding: 15px 20px;
    }

    nav ul li a:hover {
        background: #004b82;
    }

    .container {
        max-width: 900px;
        margin: 30px auto;
        padding: 20px;
        background: white;
        border-radius: 10px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    section {
        margin-bottom: 40px;
    }

    h2 {
        margin-bottom: 15px;
        color: #0078d7;
    }

    .contact-form {
        display: flex;
        flex-direction: column;
        gap: 15px;
    }

    .contact-form label {
        font-weight: bold;
    }

    .contact-form input,
    .contact-form textarea {
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
        font-size: 16px;
    }

    .contact-form textarea {
        resize: vertical;
        min-height: 120px;
    }

    .contact-form button {
        background: #0078d7;
        color: white;
        border: none;
        padding: 12px;
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
    }

    .contact-form button:hover {
        background: #005fa3;
    }

    footer {
        background: #333;
        color: white;
        text-align: center;
        padding: 20px;
    }

    @media (max-width: 768px) {
        nav ul {
            flex-direction: column;
        }
    }
</style>
</head>
<body>

<header>
    <h1>サンプルホームページ</h1>
    <p>お問い合わせフォーム付き</p>
</header>

<nav>
    <ul>
        <li><a href="https://www.dkst.net/">どこでもステーションベル</a></li>
        <li><a href="#about">会社概要</a></li>
        <li><a href="#service">サービス</a></li>
        <li><a href="#contact">お問い合わせ</a></li>
    </ul>
</nav>

<div class="container">

    <section id="home">
        <h2>ホーム</h2>
        <p>こちらはシンプルなホームページのサンプルです。</p>
    </section>

    <section id="about">
        <h2>会社概要</h2>
        <p>会社情報や自己紹介などを掲載できます。</p>
    </section>

    <section id="service">
        <h2>サービス</h2>
        <p>提供しているサービス内容を紹介できます。</p>
    </section>

<section id="contact">
    <h2>お問い合わせ</h2>

    <iframe
        src="https://forms.gle/kjsYTXUNueXcW1486"
        width="100%"
        height="800"
        frameborder="0"
        marginheight="0"
        marginwidth="0">
        読み込み中…
    </iframe>
</section>

</div>

<footer>
    <p>&copy; 2026 サンプルホームページ</p>
</footer>

</body>
</html>
