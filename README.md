<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Таблица цветов</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
        }
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            background: white;
        }
        th, td {
            padding: 12px;
            border: 1px solid #ddd;
            text-align: center;
        }
        th {
            background-color: #333;
            color: white;
        }
        .color-box {
            width: 50px;
            height: 20px;
            display: inline-block;
            border-radius: 4px;
            border: 1px solid #000;
        }
    </style>
</head>
<body>
    <h1>Таблица навозных цветов</h1>
    <table>
        <tr>
            <th>Название</th>
            <th>HEX</th>
            <th>RGBA</th>
            <th>Превью</th>
        </tr>
        <tr>
            <td>Навозный коричневый</td>
            <td>#8B4513</td>
            <td>rgba(139, 69, 19, 1)</td>
            <td><span class="color-box" style="background: rgba(139, 69, 19, 1);"></span></td>
        </tr>
        <tr>
            <td>Глинисто-коричневый</td>
            <td>#9C661F</td>
            <td>rgba(156, 102, 31, 1)</td>
            <td><span class="color-box" style="background: rgba(156, 102, 31, 1);"></span></td>
        </tr>
        <tr>
            <td>Жёлто-коричневый</td>
            <td>#D2691E</td>
            <td>rgba(210, 105, 30, 1)</td>
            <td><span class="color-box" style="background: rgba(210, 105, 30, 1);"></span></td>
        </tr>
        <tr>
            <td>Серовато-коричневый</td>
            <td>#A0522D</td>
            <td>rgba(160, 82, 45, 1)</td>
            <td><span class="color-box" style="background: rgba(160, 82, 45, 1);"></span></td>
        </tr>
        <tr>
            <td>Темный навозный</td>
            <td>#654321</td>
            <td>rgba(101, 67, 33, 1)</td>
            <td><span class="color-box" style="background: rgba(101, 67, 33, 1);"></span></td>
        </tr>
    </table>

</body>
</html>

