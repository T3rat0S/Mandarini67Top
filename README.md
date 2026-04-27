<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Практика Кирилла</title>

    <style>
        body {
            background-color: lightblue;
            color: blue;
            font-family: Arial, sans-serif;
        }

        h1 { text-align: left; }
        h2 { text-align: center; }
        h3 { text-align: right; }

        .center { text-align: center; }
        .left { text-align: left; }
        .right { text-align: right; }

        hr {
            margin: 30px 0;
        }
    </style>
</head>

<body>

<!-- ================= ЗАДАНИЕ 1 ================= -->
<h2>Задание 1: Заголовки и абзацы</h2>

<h1>Мое имя Кирилл</h1>
<h2>Я учусь в 11 классе</h2>
<h3>Моя любимая песенка</h3>

<p class="center">Привет! Это моя первая страничка!</p>

<p class="left">
В лесу родилась елочка,<br>
В лесу она росла.
</p>

<p class="right">
Метель ей пела песенку:<br>
Спи, елочка, бай-бай.<br>
Мороз снежком укутывал:<br>
Смотри, не замерзай.
</p>

<hr>

<!-- ================= ЗАДАНИЕ 2 ================= -->
<h2>Задание 2: Форматирование текста</h2>

<p class="center" style="font-family: 'Arial Black'; color: red;">
    <big>Привет! Это моя первая страничка!</big>
</p>

<h1>Меня зовут Кирилл</h1>
<h2 class="center">Я учусь в 11 классе</h2>
<h3 class="right">Это моя любимая песенка</h3>

<p class="left" style="font-family: 'Comic Sans MS';">
В лесу родилась <i>елочка</i><br>
В лесу она росла.
</p>

<p style="font-family: 'Courier New';">
Зимой и летом стройная,<br>
<span style="color: green;">зеленая</span> была.
</p>

<p>
<b>Метель</b> ей пела песенку:<br>
<span style="font-family: 'Monotype Corsiva';">«Спи, елочка, бай-бай»</span>
</p>

<p>
<b><i>Мороз</i></b> снежком укутывал:<br>
<span style="font-family: 'Monotype Corsiva';">«Смотри, не замерзай!»</span>
</p>

<hr>

<!-- ================= ЗАДАНИЕ 3 ================= -->
<h2>Задание 3: Картинки и выравнивание</h2>

<p>
<img src="елка.bmp" align="left">
В лесу родилась елочка, в лесу она росла.
</p>

<br><br><br>

<p>
<img src="елка.bmp" align="right">
Текст обтекает изображение слева.
</p>

<br><br><br>

<p>
<img src="елка.bmp" align="top">
Выравнивание по верхнему краю.
</p>

<p>
<img src="елка.bmp" align="middle">
Выравнивание по центру.
</p>

<p>
<img src="елка.bmp" align="bottom">
Выравнивание по нижнему краю.
</p>

<hr>

<!-- ================= ЗАДАНИЕ 4 ================= -->
<h2>Задание 4: Таблицы</h2>

<table border="2">
<tr>
    <td>Первая колонка</td>
    <td>Вторая колонка</td>
    <td>Третья колонка</td>
</tr>
<tr>
    <td>Первая колонка</td>
    <td>Вторая колонка</td>
    <td>Третья колонка</td>
</tr>
</table>

<br>

<table border="2" style="background-color: teal; border-color: maroon;">
<tr>
    <td style="background-color: yellow;">Первая колонка</td>
    <td>Вторая колонка</td>
    <td style="background-color: yellow;">Третья колонка</td>
</tr>
<tr>
    <td>Первая колонка</td>
    <td style="background-color: yellow;">Вторая колонка</td>
    <td>Третья колонка</td>
</tr>
</table>

<hr>

<!-- ================= ЗАДАНИЕ 5 ================= -->
<h2>Задание 5: Списки</h2>

<h3>Фрукты</h3>
<ul>
    <li>Сливы</li>
    <li>Яблоки</li>
    <li>Груши</li>
</ul>

<h3>Предметы</h3>
<ul>
    <li>Информатика</li>
    <li>Английский язык</li>
    <li>Математика</li>
    <li>История</li>
</ul>

<h3>Многоуровневый список</h3>
<ul>
    <li>Продажа авиабилетов</li>
    <li>Туризм
        <ul>
            <li>Испания</li>
            <li>Греция</li>
            <li>Таиланд</li>
            <li>Мексика</li>
        </ul>
    </li>
    <li>Визы</li>
</ul>

</body>
</html>
