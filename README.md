<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
  <title>Мастех | Промышленные дозаторы для литья пластмасс</title>
  <!-- Шрифт Inter для современного технического стиля -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,500;14..32,600;14..32,700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background: #f5f7fb;
      color: #1e293b;
      line-height: 1.5;
    }

    /* Общие контейнеры */
    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 20px;
    }

    section {
      padding: 60px 0;
    }

    h2 {
      font-size: 2rem;
      font-weight: 700;
      margin-bottom: 1rem;
      color: #0f172a;
    }

    /* Шапка */
    header {
      background: white;
      border-bottom: 1px solid #e2e8f0;
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(8px);
      background: rgba(255,255,255,0.9);
    }

    .header-inner {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 0;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: 700;
      color: #0f172a;
      letter-spacing: -0.5px;
    }
    .logo span {
      color: #2563eb;
    }

    .contact-btn {
      background: #2563eb;
      color: white;
      border: none;
      padding: 10px 24px;
      border-radius: 8px;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      transition: background 0.2s;
      text-decoration: none;
      display: inline-block;
    }
    .contact-btn:hover {
      background: #1d4ed8;
    }

    /* Героический блок */
    .hero {
      background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
      color: white;
      text-align: center;
      padding: 80px 0;
    }

    .hero h1 {
      font-size: 2.8rem;
      font-weight: 700;
      margin-bottom: 1rem;
      letter-spacing: -1px;
    }

    .hero p {
      font-size: 1.2rem;
      opacity: 0.85;
      max-width: 600px;
      margin: 0 auto 2rem;
    }

    .price-tag {
      background: rgba(255,255,255,0.1);
      backdrop-filter: blur(4px);
      border-radius: 12px;
      padding: 1.2rem 2rem;
      display: inline-block;
      margin: 1rem 0;
    }
    .price-tag .old {
      text-decoration: line-through;
      opacity: 0.6;
      margin-right: 10px;
    }
    .price-tag .new {
      font-size: 2.5rem;
      font-weight: 700;
      color: #60a5fa;
    }

    /* Карточки */
    .grid-3 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 2rem;
    }

    .card {
      background: white;
      padding: 30px 20px;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.03);
      border: 1px solid #f1f5f9;
    }

    .card h3 {
      font-size: 1.3rem;
      margin: 15px 0 10px;
    }

    /* Таблица */
    .spec-table {
      width: 100%;
      background: white;
      border-radius: 16px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.03);
      margin-top: 2rem;
    }
    .spec-table table {
      width: 100%;
      border-collapse: collapse;
    }
    .spec-table td {
      padding: 16px 20px;
      border-bottom: 1px solid #f1f5f9;
    }
    .spec-table td:first-child {
      font-weight: 600;
      color: #475569;
      width: 40%;
    }

    /* Преимущества */
    .advantages-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 2rem;
    }
    .adv-item {
      background: white;
      padding: 20px;
      border-radius: 12px;
      display: flex;
      align-items: flex-start;
      gap: 15px;
      border: 1px solid #e2e8f0;
    }
    .adv-icon {
      font-size: 1.8rem;
      background: #eff6ff;
      border-radius: 10px;
      padding: 8px;
    }

    /* Блок с ценой и CTA */
    .cta-block {
      background: #2563eb;
      color: white;
      border-radius: 24px;
      padding: 40px;
      text-align: center;
      margin-top: 2rem;
    }
    .cta-block h3 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
    }

    .white-btn {
      background: white;
      color: #2563eb;
      padding: 14px 30px;
      border-radius: 10px;
      font-weight: 700;
      text-decoration: none;
      display: inline-block;
      margin-top: 1rem;
    }

    footer {
      text-align: center;
      padding: 30px 0;
      color: #64748b;
      border-top: 1px solid #e2e8f0;
      margin-top: 40px;
    }

    /* Адаптивность */
    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2rem;
      }
      section {
        padding: 40px 0;
      }
    }
  </style>
</head>
<body>

<!-- Шапка -->
<header>
  <div class="container header-inner">
    <div class="logo">МАСТЕХ</div>
    <div>
      <a href="tel:+79040087191" style="color:#1e293b; text-decoration:none; margin-right:20px; font-weight:500;">+7 (904) 008-71-91</a>
      <a href="#contact" class="contact-btn">Запросить КП</a>
    </div>
  </div>
</header>

<!-- Главный экран -->
<section class="hero">
  <div class="container">
    <h1>Объёмный дозатор<br>для литья пластмасс «Мастех»</h1>
    <p>Прямой аналог Shini SCM. Собственная разработка, программа управления и полная совместимость с ТПА и экструдерами. Сделано в Твери.</p>
    <div class="price-tag">
      <span class="old">350 000 ₽</span>
      <span class="new">180 000 ₽</span>
    </div>
    <div style="margin-top: 1.5rem; opacity:0.8;">• В наличии • Сервис 24/7 • Доставка по РФ</div>
  </div>
</section>

<!-- Блок характеристик (из инструкции) -->
<section>
  <div class="container">
    <h2>Технические характеристики</h2>
    <div class="spec-table">
      <table>
        <tr><td>Модель</td><td><strong>Мастех СЦМ-1</strong></td></tr>
        <tr><td>Тип</td><td>Одноцветный объёмный дозатор</td></tr>
        <tr><td>Производительность</td><td>0,1 – 130 кг/ч</td></tr>
        <tr><td>Тип привода</td><td>Серводвигатель 0,4 кВт (IMS/Delta)</td></tr>
        <tr><td>Управление</td><td>Сенсорный экран 4,3″, панель VS-043QE</td></tr>
        <tr><td>Память рецептов</td><td>50 рецептов</td></tr>
        <tr><td>Входной сигнал</td><td>24 В, сухой контакт, 0–10 В (режим экструдера)</td></tr>
        <tr><td>Диаметр шнека</td><td>16 мм, хромированное покрытие</td></tr>
        <tr><td>Бункер</td><td>10 л (нерж. сталь)</td></tr>
        <tr><td>Габариты (В×Ш×Г)</td><td>420 × 585 × 300 мм</td></tr>
        <tr><td>Вес</td><td>18 кг</td></tr>
      </table>
    </div>
  </div>
</section>

<!-- Функциональные возможности -->
<section style="background: white;">
  <div class="container">
    <h2>Возможности системы управления</h2>
    <div class="grid-3">
      <div class="card">
        <h3>📊 50-секундный тест</h3>
        <p>Автоматическая калибровка по весу для предельной точности дозирования (±1.5%).</p>
      </div>
      <div class="card">
        <h3>🔄 Микродозирование</h3>
        <p>Режим для малых долей добавок (менее 0,5 г). Настраиваемый интервал циклов.</p>
      </div>
      <div class="card">
        <h3>⚠️ Защита и безопасность</h3>
        <p>Определение закупорки, перегрузки, контроль уровня материала. Автостоп и сигнал.</p>
      </div>
    </div>
  </div>
</section>

<!-- Почему мы -->
<section>
  <div class="container">
    <h2>Почему выбирают «Мастех»</h2>
    <div class="advantages-list">
      <div class="adv-item">
        <div class="adv-icon">🇷🇺</div>
        <div><strong>Производство в РФ</strong><br>Собственная КД и прошивка. Никакой зависимости от импортных протоколов.</div>
      </div>
      <div class="adv-item">
        <div class="adv-icon">⚡</div>
        <div><strong>Сервис за часы</strong><br>Инженер приедет к вам в цех. Тверь, Москва, ЦФО — мы рядом.</div>
      </div>
      <div class="adv-item">
        <div class="adv-icon">🔌</div>
        <div><strong>Plug & Play</strong><br>Полная совместимость с ТПА: 24В, сухой контакт, 0-10В.</div>
      </div>
      <div class="adv-item">
        <div class="adv-icon">🛡️</div>
        <div><strong>Гарантия 12 мес.</strong><br>Собственный склад запчастей. Шнеки, цилиндры, платы всегда в наличии.</div>
      </div>
    </div>
  </div>
</section>

<!-- Контакты и CTA -->
<section id="contact">
  <div class="container">
    <div class="cta-block">
      <h3>Обсудим ваш проект?</h3>
      <p style="font-size: 1.2rem; margin-bottom: 0.5rem;">Звоните: +7 (904) 008-71-91</p>
      <p style="opacity:0.9;">Александр Мензулов, технический директор</p>
      <p style="margin: 15px 0;">ИП Мензулов А.А. | ИНН 690140652031</p>
      <a href="mailto:info@mastech.ru" class="white-btn">Запросить счет / КП</a>
      <p style="margin-top: 20px; font-size:0.9rem;">📍 Тверь, доставка по РФ</p>
    </div>
  </div>
</section>

<footer>
  <div class="container">
    © Мастех, 2026. Все права защищены. Не является публичной офертой.
  </div>
</footer>

</body>
</html>
