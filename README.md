<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>台北市近年生育男女調查</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Serif TC', serif;
            margin: 20px;
            background-color: #f4f4f9;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            text-align: center;
            font-weight: 700;
        }
        .chart-container {
            margin: 20px 0;
        }
        img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .analysis {
            margin-top: 30px;
            line-height: 1.8;
        }
        .reference-box {
            margin-top: 40px;
            padding: 20px;
            background-color: #eef1f7;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .reference-box a {
            color: #007bff;
            text-decoration: none;
            font-weight: 700;
            transition: color 0.3s ease;
        }
        .reference-box a:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>台北市近年生育男女調查</h1>
        <p class="text-center">透過數據視覺化分析，了解台北市近年生育人數與男女比例變化。</p>

        <div class="chart-container text-center">
            <h2>生育人數趨勢圖</h2>
            <img src="p1.png" alt="生育人數趨勢圖">
        </div>

        <div class="chart-container text-center">
            <h2>男女比變化</h2>
            <img src="p2.png" alt="男女比變化圖">
        </div>

        <div class="analysis">
            <h2>數據分析與解讀</h2>
            <p>從 95 年到 111 年，可以觀察到99年到101年間生育數量急遽上升，可能與當時社會風氣或政策有關。生育人數在 101 年至 105 年之間達到高峰，之後逐年下降。這種變化可能與社會經濟因素以及生育觀念改變有關，顯現出台北市近年可能出現少子化現象。</p>
            <p>觀察男女比例，可以發現生育男嬰數普遍略高於女嬰，反映出生育性別比的穩定趨勢。但有幾年男女比呈現較劇烈變化，可能會導致該年人口結構不平衡。</p>
        </div>

        <div class="reference-box">
            <p>參考資料：</p>
            <a href="https://data.gov.tw/dataset/132341" target="_blank">臺北市嬰兒出生數按出生者父母年齡及胎次別</a>
        </div>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>
