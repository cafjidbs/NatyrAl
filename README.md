<!DOCTYPE html>
<html lang="sq">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EkoFerma - Produktet më të freskëta sezonale</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f7ec;
            color: #2d4d23;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #3b7d30;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 24px;
        }
        .container {
            width: 90%;
            margin: auto;
            padding: 20px;
        }
        .section {
            margin-bottom: 30px;
        }
        .basket {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .basket-item {
            width: 30%;
            padding: 15px;
            background: white;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .basket-item img {
            width: 100%;
            border-radius: 10px;
        }
        .discounts, .premium-card {
            background: #e8f5e3;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
        .btn {
            background: #3b7d30;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>EkoFerma - Produktet më të freskëta sezonale</header>
    <div class="container">
        
        <section class="section">
            <h2>Shporta Sezonale</h2>
            <div class="basket">
                <div class="basket-item">
                    <img src="basket_spring.jpg" alt="Shporta Pranverore">
                    <h3>Shporta Pranverore</h3>
                    <p>Përmban fruta dhe perime të freskëta të pranverës.</p>
                    <a href="#" class="btn">Bli tani</a>
                </div>
                <div class="basket-item">
                    <img src="basket_summer.jpg" alt="Shporta Verore">
                    <h3>Shporta Verore</h3>
                    <p>Ideale për receta të lehta dhe të freskëta.</p>
                    <a href="#" class="btn">Bli tani</a>
                </div>
                <div class="basket-item">
                    <img src="basket_winter.jpg" alt="Shporta Dimërore">
                    <h3>Shporta Dimërore</h3>
                    <p>Plot me ushqime të ngrohta dhe të pasura me vlera ushqyese.</p>
                    <a href="#" class="btn">Bli tani</a>
                </div>
            </div>
        </section>
        
        <section class="discounts">
            <h2>Zbritjet e Javës</h2>
            <p>Shporta e javës me 20% ulje! Bli tani dhe shijo të mirat e natyrës me çmime fantastike.</p>
            <a href="#" class="btn">Shiko ofertën</a>
        </section>
        
        <section class="premium-card">
            <h2>Premium Card</h2>
            <p>Bëhu anëtar i EkoFerma Premium dhe përfito 10% zbritje në çdo porosi!</p>
            <a href="#" class="btn">Bëhu Anëtar</a>
        </section>
    </div>
</body>
</html>
