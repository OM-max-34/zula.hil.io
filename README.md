```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZULA HİLE</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #080808;
            color: white;
        }

        /* ÜST BAŞLIK */
        header {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            background:
                linear-gradient(rgba(0,0,0,.75), rgba(0,0,0,.95)),
                radial-gradient(circle, #450000, #080808 70%);
        }

        header h1 {
            font-size: 70px;
            letter-spacing: 8px;
            color: #ff2020;
            text-shadow: 0 0 25px #ff0000;
        }

        /* İÇERİK */
        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
            padding: 80px 0;
        }

        .section-title {
            color: #ff2020;
            font-size: 35px;
            margin-bottom: 25px;
            border-left: 5px solid #ff2020;
            padding-left: 15px;
        }

        .card {
            background: #111;
            border: 1px solid #292929;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 0 25px rgba(255,0,0,.08);
        }

        .card p {
            color: #bbb;
            line-height: 1.7;
            margin-bottom: 25px;
        }

        /* GÖRSEL ALANI */
        .image-box {
            width: 100%;
            height: 400px;
            border: 2px dashed #ff2020;
            border-radius: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #090909;
            overflow: hidden;
        }

        .image-box img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            display: block;
        }

        /* YAKALANMA ORANI */
        .risk {
            text-align: center;
            color: #ff2020;
            font-size: 22px;
            font-weight: bold;
            margin-top: 20px;
        }

        footer {
            text-align: center;
            padding: 30px;
            background: #050505;
            color: #555;
            border-top: 1px solid #181818;
        }

        /* TELEFON */
        @media(max-width: 700px) {

            header h1 {
                font-size: 42px;
            }

            .container {
                width: 90%;
                padding: 50px 0;
            }

            .section-title {
                font-size: 30px;
            }

            .image-box {
                height: 250px;
            }
        }
    </style>
</head>

<body>

    <!-- ANA BAŞLIK -->
    <header>
        <div>
            <h1>ZULA HİLE</h1>
        </div>
    </header>


    <!-- RÖNTGEN BÖLÜMÜ -->
    <section class="container">

        <h2 class="section-title">1] RÖNTGEN</h2>

        <div class="card">

            <p>
                Hile net yer gösterir. Sapma oranı yüzde 16'dır.
                Düşmanın üstüne nişan alarak beklemezseniz yakalanmazsınız.
            </p>

            <!-- RESİM -->
            <div class="image-box">
                <img src="zula.röntgen.png" alt="Röntgen">
            </div>

            <!-- YAKALANMA -->
            <div class="risk">
                Yakalanma: %20
            </div>

        </div>

    </section>


    <footer>
        © 2026 ZULA HİLE
    </footer>

</body>
</html>
```
