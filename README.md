# my-html-ptoject
# Мой проект
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Кнопка бар сайт</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
            padding-top: 50px;
        }

        .button {
            padding: 15px 30px;
            font-size: 16px;
            color: white;
            background-color: #4CAF50;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h1>Кнопкамен жұмыс жасау</h1>
    <button class="button" onclick="alert('Сіз кнопканы басқаныз!')">Нажми меня</button>

</body>
</html>
