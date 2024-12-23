<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dashboard</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #007BFF;
      color: white;
      padding: 10px 20px;
    }
    .navbar a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }
    .sidebar {
      width: 250px;
      height: 100vh;
      background-color: #f4f4f4;
      position: fixed;
      top: 0;
      left: 0;
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0,0,0,0.1);
    }
    .content {
      margin-left: 270px;
      padding: 20px;
    }
  </style>
</head>
<body>
  <div class="navbar">
    <div>Логотип</div>
    <div>
      <a href="#">Главная</a>
      <a href="#">Отели</a>
      <a href="#">Контакты</a>
    </div>
  </div>
  <div class="sidebar">
    <h3>Фильтры</h3>
    <ul>
      <li>По цене</li>
      <li>По удобствам</li>
      <li>Для семей</li>
    </ul>
  </div>
  <div class="content">
    <h1>Добро пожаловать на Dashboard</h1>
    <p>Здесь будет отображаться список отелей.</p>
  </div>
</body>
</html>
