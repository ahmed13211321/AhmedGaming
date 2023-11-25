# AhmedGaming
Ahd
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>ألعابي الرائعة</title>
</head>
<body>
    <h1>مرحبًا بك في ألعابي الرائعة</h1>
    
</body>
</html>
/* styles.css */
body {
    font-family: 'Arial', sans-serif;
    text-align: center;
}

h1 {
    color: #3366cc;
}
<!-- index.html (تحديث) -->

<body>
    <h1>مرحبًا بك في ألعابي الرائعة</h1>
    <ul>
        <li><a href="game1.html">لعبة 1</a></li>
        <li><a href="game2.html">لعبة 2</a></li>
    
    </ul>
</body>
<!-- game1.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <title>لعبة 1</title>
</head>
<body>
    <h1>لعبة 1 - اسم اللعبة</h1>
    <p>وصف قصير للعبة 1.</p>
    <!-- يمكنك هنا إضافة المزيد من عناصر HTML للعبة -->
</body>
</html>
<!-- game2.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <title>لعبة 2</title>
</head>
<body>
    <h1>لعبة 2 - اسم اللعبة</h1>
    <p>وصف قصير للعبة 2.</p>
    <!-- يمكنك هنا إضافة المزيد من عناصر HTML للعبة -->
</body>
</html>
// script.js
// يمكنك هنا إضافة أي تفاعلات JavaScript للألعاب

// مثال: عندما يتم النقر على زر "بدء اللعبة"
document.addEventListener('DOMContentLoaded', function() {
    const startGameButton = document.getElementById('startGameButton');
    if (startGameButton) {
        startGameButton.addEventListener('click', function() {
            alert('لعبة قيد التطوير!');
        });
    }
});
