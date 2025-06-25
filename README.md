# my-edu.time-website
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Eğitim Test Sitesi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 700px;
            margin: 40px auto;
            padding: 0 15px;
            background-color: #f5f5f5;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #2c3e50;
        }
        select, button {
            padding: 8px;
            margin: 10px 0;
            font-size: 16px;
        }
        .question {
            background: white;
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 5px;
            box-shadow: 0 0 8px rgba(0,0,0,0.1);
        }
        .answers label {
            display: block;
            margin: 8px 0;
            cursor: pointer;
        }
        .result {
            text-align: center;
            font-size: 20px;
            padding: 15px;
            background-color: #dff0d8;
            color: #3c763d;
            border-radius: 5px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Eğitim Test Sitesi</h1>

    <label for="sinif">Sınıf Seçiniz:</label>
    <select id="sinif">
        <option value="">Seçiniz</option>
        <option value="1">1. Sınıf</option>
        <option value="2">2. Sınıf</option>
        <option value="3">3. Sınıf</option>
    </select>

    <label for="ders">Ders Seçiniz:</label>
    <select id="ders" disabled>
        <option value="">Önce sınıf seçiniz</option>
    </select>

    <button id="baslaBtn" disabled>Teste Başla</button>

    <div id="testAlani" style="margin-top: 30px;"></div>

    <script src="app.js"></script>
</body>
</html>
