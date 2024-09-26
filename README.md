# -5
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>신제품 출시</title>
    <link rel="stylesheet" href="styles.css">
    <style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.header {
    background: #1c87c9;
    color: #fff;
    padding: 80px 0;
    text-align: center;
}

.header h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

.header p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

.cta-button {
    background: #ff6347;
    color: #fff;
    padding: 15px 30px;
    text-transform: uppercase;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    text-decoration: none;
}

.cta-button:hover {
    background: #ff4500;
}

.features {
    padding: 60px 0;
    background: #fff;
}

.features h2 {
    text-align: center;
    margin-bottom: 40px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.feature {
    background: #e7e7e7;
    padding: 20px;
    text-align: center;
    border-radius: 10px;
}

.feature img {
    max-width: 100px;
    margin-bottom: 20px;
}

.register {
    background: #f9f9f9;
    padding: 60px 0;
}

.register h2 {
    text-align: center;
    margin-bottom: 40px;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form input {
    padding: 10px;
    margin: 10px 0;
    width: 300px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background: #1c87c9;
    color: #fff;
    padding: 10px 30px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    text-transform: uppercase;
}

form button:hover {
    background: #005f9e;
}

.footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

      </style>
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>최신 기술을 담은 신제품</h1>
            <p>지금까지 경험하지 못한 혁신적인 기능</p>
            <a href="#register" class="cta-button">지금 등록하세요</a>
        </div>
    </header>

    <section class="features">
        <div class="container">
            <h2>제품 주요 기능</h2>
            <div class="grid">
                <div class="feature">
                    <img src="https://th.bing.com/th/id/OIP.VL6hQzlcMCVXzdSIhUKuZgHaEj?rs=1&pid=ImgDetMain" alt="기능 1">
                    <h3>고성능 배터리</h3>
                    <p>최대 48시간 지속되는 배터리 성능</p>
                </div>
                <div class="feature">
                    <img src="https://smartmania.cz/wp-content/uploads/2023/10/iPhone-16-To-Skip-A17-Feature.jpg" alt="기능 2">
                    <h3>초고속 처리 속도</h3>
                    <p>최신 AP로 빠르고 효율적인 작업 처리</p>
                </div>
                <div class="feature">
                    <img src="https://cdn.iphoneincanada.ca/wp-content/uploads/2023/07/iPhone-16-Pro-Ma.jpg" alt="기능 3">
                    <h3>최고 수준의 카메라</h3>
                    <p>프로 수준의 사진 촬영 기능</p>
                </div>
            </div>
        </div>
    </section>

    <section id="register" class="register">
        <div class="container">
            <h2>제품 등록하기</h2>
            <form action="#">
                <input type="text" placeholder="이름" required>
                <input type="email" placeholder="이메일" required>
                <button type="submit" class="cta-button">등록하기</button>
            </form>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 신제품 출시. 애플이 권리 보유.</p>
        </div>
    </footer>
</body>
</html>
