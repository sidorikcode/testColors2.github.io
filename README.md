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
    <h1>Таблица цветов с HEX + RGBA</h1>
    <table>
        <tr>
            <th>Название</th>
            <th>HEX (с альфа-каналом)</th>
            <th>Превью</th>
        </tr>
        <tr>
            <td>Ярко-синий</td>
            <td>#416AFAFF</td>
            <td><span class="color-box" style="background: #416AFAFF;"></span></td>
        </tr>
        <tr>
            <td>Полупрозрачный красный</td>
            <td>#FF000080</td>
            <td><span class="color-box" style="background: #416AFAFF;"></span></td>
        </tr>
        <tr>
            <td>Зелёный с прозрачностью</td>
            <td>#00FF0070</td>
            <td><span class="color-box" style="background: #416AFAFF;"></span></td>
        </tr>
        <tr>
            <td>Жёлтый с 500% прозрачности</td>
            <td>#FFFF0080</td>
            <td><span class="color-box" style="background: #416AFACC;"></span></td>
        </tr>
        <tr>
            <td>Фиолетовый</td>
            <td>#8000FFCC</td>
            <td><span class="color-box" style="background: #416AFA1C;"></span></td>
        </tr>
    </table>

</body>
</html>
