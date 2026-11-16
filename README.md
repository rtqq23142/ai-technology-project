# ai-technology-project
A school project about technology and artificial intelligence.
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Проєкт про технології та штучний інтелект, їхні можливості та застосування.">
    <title>Технології та штучний інтелект</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #101820;
            color: #F2F2F2;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 30px;
        }

        .container {
            max-width: 900px;
            width: 100%;
        }

        h1 {
            font-size: 42px;
            margin-bottom: 20px;
        }

        .description {
            font-size: 18px;
            line-height: 1.7;
            margin-bottom: 35px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
        }

        .card {
            border: 1px solid #00D1B2;
            padding: 25px;
            border-radius: 12px;
            transition: 0.3s;
        }

        .card:hover {
            background: #00D1B2;
            color: #101820;
            transform: translateY(-5px);
        }

        .card h2 {
            font-size: 23px;
            margin: 0;
        }

        .subtitle {
            color: #00D1B2;
            font-size: 14px;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 32px;
            }

            .cards {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>
    <main class="container">
        <div class="subtitle">Річний проєкт · 10 клас</div>

        <h1>Технології та штучний інтелект</h1>

        <p class="description">
            Штучний інтелект — одна з важливих технологій сучасного світу.
            Він використовується для обробки інформації, створення текстів
            та зображень. Мета мого проєкту — дослідити можливості штучного
            інтелекту та його застосування в повсякденному житті.
        </p>

        <section class="cards">
            <div class="card">
                <h2>🎮 Гра</h2>
            </div>

            <div class="card">
                <h2>🤖 Бот</h2>
            </div>

            <div class="card">
                <h2>🌐 Сайт</h2>
            </div>

            <div class="card">
                <h2>📱 Застосунок</h2>
            </div>
        </section>
    </main>
</body>
</html>
