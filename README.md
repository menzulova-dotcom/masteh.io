<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover, shrink-to-fit=yes">
  <title>Мастех | Промышленные дозаторы для литья пластмасс</title>
  <!-- Системные шрифты, которые точно есть на iOS и Android -->
  <style>
    /* Сброс и базовые стили — максимальная совместимость */
    *, *::before, *::after {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      -webkit-text-size-adjust: 100%; /* Запрет масштабирования текста в Safari */
      -moz-text-size-adjust: 100%;
      text-size-adjust: 100%;
      scroll-behavior: smooth;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
      background: #f5f7fb;
      color: #1e293b;
      line-height: 1.5;
      padding: env(safe-area-inset-top) env(safe-area-inset-right) env(safe-area-inset-bottom) env(safe-area-inset-left);
      /* env(safe-area-inset-*) учитывает вырезы и скругления экранов */
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 16px;
    }

    section {
      padding: 40px 0;
    }

    h2 {
      font-size: 1.7rem;
      font-weight: 700;
      margin-bottom: 1rem;
      color: #0f172a;
    }

    /* Шапка — без блюра (Safari его срезает) */
    header {
      background: white;
      border-bottom: 1px solid #e2e8f0;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .header-inner {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 12px 0;
      flex-wrap: wrap;
      gap: 8px;
    }

    .logo {
      font-size: 1.5rem;
      font-weight: 700;
      color: #0f172a;
      letter-spacing: -0.5px;
    }
    .logo span {
      color: #2563eb;
    }

    .header-phone {
      color: #1e293b;
      text-decoration: none;
      font-weight: 500;
      font-size: 0.9rem;
      white-space: nowrap;
    }

    .contact-btn {
      background: #2563eb;
      color: white;
      border: none;
      padding: 10px 18px;
      border-radius: 8px;
      font-weight: 600;
      font-size: 0.9rem;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      white-space: nowrap;
    }
    .contact-btn:active {
      background: #1d4ed8;
    }

    /* Героический блок */
    .hero {
      background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
      color: white;
      text-align: center;
      padding: 50px 0;
    }

    .hero h1 {
      font-size: 1.8rem;
      font-weight: 700;
      margin-bottom: 0.8rem;
      letter-spacing: -0.5px;
      line-height: 1.2;
    }

    .hero p {
      font-size: 1rem;
      opacity: 0.85;
      max-width: 600px;
      margin: 0 auto 1.5rem;
      padding: 0 10px;
    }

    .price-tag {
      background: rgba(255,255,255,0.12);
      border-radius: 12px;
      padding: 1rem 1.5rem;
      display: inline-block;
      margin: 0.5rem 0;
    }
    .price-tag .old {
      text-decoration: line-through;
      opacity: 0.6;
      display: block;
      font-size: 0.9rem;
      margin-bottom: 4px;
    }
    .price-tag .new {
      font-size: 2rem;
      font-weight: 700;
      color: #60a5fa;
    }

    .hero-note {
      margin-top: 1rem;
      opacity: 0.7;
      font-size: 0.85rem;
    }

    /* Карточки */
    .grid-3, .grid-2 {
      display: flex;
      flex-direction: column;
      gap: 16px;
      margin-top: 1.5rem;
    }

    .card {
      background: white;
      padding: 20px 16px;
      border-radius: 14px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.03);
      border: 1px solid #f1f5f9;
    }

    .card h3 {
      font-size: 1.1rem;
      margin: 8px 0 6px;
    }

    .card p {
      color: #475569;
      font-size: 0.95rem;
    }

    /* Таблица */
    .spec-table {
      background: white;
      border-radius: 14px;
      overflow-x: auto;
      -webkit-overflow-scrolling: touch;
      box-shadow: 0 2px 8px rgba(0,0,0,0.03);
      margin-top: 1.5rem;
    }
    .spec-table table {
      width: 100%;
      border-collapse: collapse;
      min-width: 300px;
    }
    .spec-table td {
      padding: 12px 14px;
      border-bottom: 1px solid #f1f5f9;
      font-size: 0.9rem;
    }
    .spec-table td:first-child {
      font-weight: 600;
      color: #475569;
      width: 45%;
    }

    /* Преимущества */
    .advantages-list {
      display: flex;
      flex-direction: column;
      gap: 12px;
      margin-top: 1.5rem;
    }
    .adv-item {
      background: white;
      padding: 16px;
      border-radius: 12px;
      display: flex;
      align-items: flex-start;
      gap: 12px;
      border: 1px solid #e2e8f0;
    }
    .adv-icon {
      font-size: 1.5rem;
      background: #eff6ff;
      border-radius: 10px;
      padding: 6px 8px;
      flex-shrink: 0;
    }
    .adv-text strong {
      display: block;
      margin-bottom: 4px;
    }
    .adv-text {
      font-size: 0.9rem;
    }

    /* CTA */
    .cta-block {
      background: #2563eb;
      color: white;
      border-radius: 16px;
      padding: 30px 20px;
      text-align: center;
      margin-top: 1.5rem;
    }
    .cta-block h3 {
      font-size: 1.5rem;
      margin-bottom: 0.8rem;
    }
    .cta-block p {
      font-size: 1rem;
      margin-bottom: 0.5rem;
    }

    .white-btn {
      background: white;
      color: #2563eb;
      padding: 14px 28px;
      border-radius: 10px;
      font-weight: 700;
      text-decoration: none;
      display: inline-block;
      margin-top: 1rem;
      border: none;
      cursor: pointer;
      font-size: 1rem;
      transition: opacity 0.2s;
    }
    .white-btn:active {
      opacity: 0.8;
    }

    footer {
      text-align: center;
      padding: 24px 0;
      color: #64748b;
      border-top: 1px solid #e2e8f0;
      font-size: 0.85rem;
    }

    /* Планшеты и ноутбуки — включаем многоколоночные сетки */
    @media (min-width: 640px) {
      .header-inner {
        flex-wrap: nowrap;
      }
      .hero h1 {
        font-size: 2.4rem;
      }
      .grid-3 {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
      }
      .advantages-list {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
      }
      .hero p {
        font-size: 1.1rem;
      }
      .price-tag .old {
        display: inline;
        margin-right: 10px;
      }
      .price-tag .new {
        font-size: 2.2rem;
      }
    }

    /* Для очень маленьких экранов (< 370px) */
    @media (max-width: 370px) {
      .header-phone {
        font-size: 0.8rem;
      }
      .contact-btn {
        padding: 8px 12px;
        font-size: 0.8rem;
      }
      .hero h1 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

<!-- Шапка -->
<header>
  <div class="container header-inner">
    <div class="logo">МАСТЕХ</div>
    <a href="tel:+79040087191" class="header-phone">+7 (904) 008-71-91</a>
    <a href="#contact" class="contact-btn">Запросить КП</a>
  </div>
</header>

<!-- Главный экран -->
<section class="hero">
  <div class="container">
    <h1>Объёмный дозатор<br>для литья пластмасс «Мастех»</h1>
    <p>Прямой аналог Shini SCM. Собственная разработка и программа управления. Сделано в Твери.</p>
    <div class="price-tag">
      <span class="old">Импортный аналог 350 000 ₽</span>
      <span class="new">от 180 000 ₽</span>
    </div>
    <div class="hero-note">• В наличии • Сервис ЦФО • Гарантия 12 мес.</div>
  </div>
</section>

<!-- Характеристики -->
<section>
  <div class="container">
    <h2>Технические характеристики</h2>
    <div class="spec-table">
      <table>
        <tr><td>Производительность</td><td><strong>0,1 – 130 кг/ч</strong></td></tr>
        <tr><td>Привод</td><td>Серводвигатель 0,4 кВт</td></tr>
        <tr><td>Управление</td><td>Сенсорный экран 4,3″</td></tr>
        <tr><td>Память рецептов</td><td>50 рецептов</td></tr>
        <tr><td>Входной сигнал</td><td>24 В, сухой контакт, 0–10 В</td></tr>
        <tr><td>Диаметр шнека</td><td>16 мм, хромированный</td></tr>
        <tr><td>Бункер</td><td>10 л, нержавеющая сталь</td></tr>
        <tr><td>Габариты (В×Ш×Г)</td><td>420 × 585 × 300 мм</td></tr>
        <tr><td>Вес</td><td>18 кг</td></tr>
        <tr><td>Питание</td><td>1 фаза, 230 В, 50 Гц</td></tr>
      </table>
    </div>
  </div>
</section>

<!-- Возможности -->
<section style="background: white;">
  <div class="container">
    <h2>Система управления</h2>
    <div class="grid-3">
      <div class="card">
        <h3>📊 50-секундный тест</h3>
        <p>Автоматическая калибровка для точности дозирования ±1,5%.</p>
      </div>
      <div class="card">
        <h3>🔄 Микродозирование</h3>
        <p>Режим для малых долей добавок. Настраиваемый интервал циклов.</p>
      </div>
      <div class="card">
        <h3>⚠️ Защита</h3>
        <p>Контроль закупорки, перегрузки, уровня материала. Автостоп и сигнал.</p>
      </div>
    </div>
  </div>
</section>

<!-- Преимущества -->
<section>
  <div class="container">
    <h2>Почему выбирают «Мастех»</h2>
    <div class="advantages-list">
      <div class="adv-item">
        <div class="adv-icon">🇷🇺</div>
        <div class="adv-text"><strong>Производство в РФ</strong>Собственная КД и прошивка. Нет зависимости от импорта.</div>
      </div>
      <div class="adv-item">
        <div class="adv-icon">⚡</div>
        <div class="adv-text"><strong>Сервис за часы</strong>Инженер рядом. Тверь, Москва, ЦФО.</div>
      </div>
      <div class="adv-item">
        <div class="adv-icon">🔌</div>
        <div class="adv-text"><strong>Plug & Play</strong>Совместимость с ТПА: 24В, сухой контакт, 0–10В.</div>
      </div>
      <div class="adv-item">
        <div class="adv-icon">🛡️</div>
        <div class="adv-text"><strong>Гарантия 12 мес.</strong>Склад запчастей. Шнеки, платы — всегда в наличии.</div>
      </div>
    </div>
  </div>
</section>

<!-- Контакты -->
<section id="contact">
  <div class="container">
    <div class="cta-block">
      <h3>Обсудим задачу?</h3>
      <p><strong>+7 (904) 008-71-91</strong></p>
      <p style="opacity:0.9;">Александр Мензулов, технический директор</p>
      <p style="font-size:0.85rem; margin:10px 0;">ИП Мензулов А.А. | ИНН 690140652031</p>
      <a href="mailto:info@mastech.ru" class="white-btn">Запросить счёт / КП</a>
      <p style="margin-top:14px; font-size:0.8rem; opacity:0.7;">📍 Тверь, доставка по РФ</p>
    </div>
  </div>
</section>

<footer>
  <div class="container">
    © Мастех, 2026. Не является публичной офертой.
  </div>
</footer>

</body>
</html>
