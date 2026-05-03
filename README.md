<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мастех | Промышленные дозаторы для литья пластмасс</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: #f5f7fb;
      color: #1e293b;
      font-size: 16px;
      line-height: 1.5;
    }

    /* ШАПКА */
    .header {
      background: white;
      border-bottom: 1px solid #e2e8f0;
      padding: 12px 16px;
      text-align: center;
    }

    .logo {
      font-size: 24px;
      font-weight: 700;
      color: #0f172a;
      margin-bottom: 8px;
    }
    .logo span {
      color: #2563eb;
    }

    .header a {
      color: #2563eb;
      text-decoration: none;
      font-weight: 600;
      font-size: 16px;
    }

    .header .phone {
      display: block;
      color: #1e293b;
      margin-bottom: 6px;
      font-size: 16px;
    }

    .header .btn-kp {
      display: inline-block;
      background: #2563eb;
      color: white;
      padding: 8px 18px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      font-size: 15px;
      transition: background 0.15s ease;
      margin-top: 4px;
    }
    .header .btn-kp:active {
      background: #1d4ed8;
    }

    /* ГЕРОЙ */
    .hero {
      background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
      color: white;
      text-align: center;
      padding: 50px 16px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.1);
      position: relative;
      z-index: 2;
    }

    .hero h1 {
      font-size: 26px;
      font-weight: 700;
      margin-bottom: 14px;
      line-height: 1.3;
    }

    .hero p {
      font-size: 16px;
      margin-bottom: 18px;
      opacity: 0.9;
    }

    .price-box {
      background: rgba(255,255,255,0.12);
      border-radius: 12px;
      padding: 16px 20px;
      display: inline-block;
      margin-bottom: 12px;
    }

    .price-box .old {
      display: block;
      text-decoration: line-through;
      opacity: 0.6;
      font-size: 15px;
      margin-bottom: 4px;
    }

    .price-box .new {
      font-size: 30px;
      font-weight: 700;
      color: #60a5fa;
    }

    .hero .note {
      font-size: 13px;
      opacity: 0.7;
      margin-top: 8px;
    }

    /* СЕКЦИИ */
    .section {
      padding: 44px 16px;
    }

    .section h2 {
      font-size: 24px;
      font-weight: 700;
      margin-bottom: 20px;
      color: #0f172a;
    }

    .bg-white {
      background: white;
    }

    .divider {
      height: 1px;
      background: #e2e8f0;
      max-width: 1100px;
      margin: 0 auto;
    }

    /* ТАБЛИЦА ХАРАКТЕРИСТИК */
    .spec-table {
      background: white;
      border-radius: 14px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.04);
      padding: 4px 0;
    }

    .spec-row {
      padding: 14px 16px;
      border-bottom: 1px solid #f1f5f9;
      font-size: 15px;
    }

    .spec-row:last-child {
      border-bottom: none;
    }

    .spec-label {
      font-weight: 600;
      color: #475569;
      margin-bottom: 2px;
    }

    /* КАРТОЧКИ */
    .card {
      background: white;
      border-radius: 14px;
      padding: 22px 18px;
      margin-bottom: 16px;
      border: 1px solid #e2e8f0;
      box-shadow: 0 2px 8px rgba(0,0,0,0.02);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    @media (hover: hover) {
      .card:hover {
        transform: translateY(-3px);
        box-shadow: 0 8px 20px rgba(0,0,0,0.06);
      }
    }

    .card h3 {
      font-size: 18px;
      margin-bottom: 8px;
    }

    .card p {
      font-size: 15px;
      color: #475569;
    }

    /* ПРЕИМУЩЕСТВА */
    .adv-grid {
      display: block;
    }

    .adv-item {
      background: white;
      border-radius: 14px;
      padding: 18px 16px;
      margin-bottom: 12px;
      border: 1px solid #e2e8f0;
    }

    .adv-item .icon {
      font-size: 24px;
      margin-bottom: 8px;
    }

    .adv-item strong {
      display: block;
      font-size: 16px;
      margin-bottom: 6px;
    }

    .adv-item span {
      font-size: 14px;
      color: #475569;
    }

    @media (min-width: 480px) {
      .adv-grid {
        display: flex;
        flex-wrap: wrap;
        gap: 12px;
      }
      .adv-item {
        flex: 1 1 calc(50% - 12px);
        margin-bottom: 0;
      }
    }

    /* CTA */
    .cta {
      background: #2563eb;
      color: white;
      border-radius: 16px;
      padding: 32px 20px;
      text-align: center;
      margin: 0 16px 40px;
      box-shadow: 0 8px 22px rgba(37,99,235,0.25);
    }

    .cta h3 {
      font-size: 22px;
      margin-bottom: 14px;
    }

    .cta .phone-big {
      font-size: 22px;
      font-weight: 700;
      margin-bottom: 6px;
    }
    .cta .phone-big a {
      color: white;
      text-decoration: none;
    }

    .cta .btn {
      display: inline-block;
      background: white;
      color: #2563eb;
      padding: 16px 32px;
      border-radius: 12px;
      font-weight: 700;
      text-decoration: none;
      font-size: 17px;
      margin-top: 16px;
      transition: background 0.15s ease;
    }
    .cta .btn:active {
      background: #e0e7ff;
    }

    /* КНОПКА НАВЕРХ */
    .back-to-top {
      position: fixed;
      bottom: 24px;
      right: 20px;
      z-index: 999;
      width: 48px;
      height: 48px;
      border-radius: 50%;
      background: rgba(15, 23, 42, 0.7);
      backdrop-filter: blur(8px);
      -webkit-backdrop-filter: blur(8px);
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      transition: background 0.2s ease, transform 0.2s ease;
      box-shadow: 0 4px 14px rgba(0,0,0,0.2);
      border: 1px solid rgba(255,255,255,0.15);
    }

    .back-to-top:hover {
      background: rgba(15, 23, 42, 0.85);
      transform: translateY(-2px);
    }

    .back-to-top:active {
      background: rgba(15, 23, 42, 0.9);
      transform: scale(0.94);
    }

    /* Стрелка */
    .back-to-top::after {
      content: "";
      display: block;
      width: 12px;
      height: 12px;
      border-top: 2.5px solid white;
      border-right: 2.5px solid white;
      transform: rotate(-45deg);
      position: relative;
      top: 2px;
    }

    /* ФУТЕР */
    .footer {
      text-align: center;
      padding: 24px 16px;
      color: #64748b;
      font-size: 13px;
      background: white;
      border-top: 1px solid #e2e8f0;
    }
  </style>
</head>
<body id="top">

<!-- ШАПКА -->
<div class="header">
  <div class="logo">МАСТЕХ</div>
  <a href="tel:+79032026198" class="phone">8 (903) 202-61-98</a>
  <a href="#cta" class="btn-kp">Запросить КП</a>
</div>

<!-- ГЕРОЙ -->
<div class="hero">
  <h1>Объёмный дозатор<br>для литья пластмасс</h1>
  <p>Прямой аналог Shini SCM. Собственная разработка и программа управления. Сделано в Твери.</p>
  <div class="price-box">
    <span class="old">Импортный аналог 350 000 ₽</span>
    <span class="new">от 180 000 ₽</span>
  </div>
  <div class="note">• В наличии • Сервис ЦФО • Гарантия 12 мес.</div>
</div>

<!-- РАЗДЕЛИТЕЛЬ -->
<div class="divider"></div>

<!-- ХАРАКТЕРИСТИКИ -->
<div class="section" id="specs">
  <h2>Технические характеристики</h2>
  <div class="spec-table">
    <div class="spec-row"><div class="spec-label">Производительность</div>0,1 – 130 кг/ч</div>
    <div class="spec-row"><div class="spec-label">Привод</div>Серводвигатель 0,4 кВт</div>
    <div class="spec-row"><div class="spec-label">Управление</div>Сенсорный экран 4,3″</div>
    <div class="spec-row"><div class="spec-label">Память рецептов</div>50 рецептов</div>
    <div class="spec-row"><div class="spec-label">Входной сигнал</div>24 В, сухой контакт, 0–10 В</div>
    <div class="spec-row"><div class="spec-label">Диаметр шнека</div>16 мм, хромированный</div>
    <div class="spec-row"><div class="spec-label">Бункер</div>10 л, нержавеющая сталь</div>
    <div class="spec-row"><div class="spec-label">Габариты (В×Ш×Г)</div>420 × 585 × 300 мм</div>
    <div class="spec-row"><div class="spec-label">Вес</div>18 кг</div>
    <div class="spec-row"><div class="spec-label">Питание</div>1 фаза, 230 В, 50 Гц</div>
  </div>
</div>

<!-- РАЗДЕЛИТЕЛЬ -->
<div class="divider"></div>

<!-- ВОЗМОЖНОСТИ -->
<div class="section bg-white">
  <h2>Система управления</h2>
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

<!-- РАЗДЕЛИТЕЛЬ -->
<div class="divider"></div>

<!-- ПРЕИМУЩЕСТВА -->
<div class="section">
  <h2>Почему выбирают «Мастех»</h2>
  <div class="adv-grid">
    <div class="adv-item">
      <div class="icon">🇷🇺</div>
      <strong>Производство в РФ</strong>
      <span>Собственная КД и прошивка. Нет зависимости от импорта.</span>
    </div>
    <div class="adv-item">
      <div class="icon">⚡</div>
      <strong>Сервис за часы</strong>
      <span>Инженер рядом. Тверь, Москва, ЦФО.</span>
    </div>
    <div class="adv-item">
      <div class="icon">🔌</div>
      <strong>Plug & Play</strong>
      <span>Совместимость с ТПА: 24В, сухой контакт, 0–10В.</span>
    </div>
    <div class="adv-item">
      <div class="icon">🛡️</div>
      <strong>Гарантия 12 мес.</strong>
      <span>Склад запчастей. Шнеки, платы — всегда в наличии.</span>
    </div>
  </div>
</div>

<!-- КОНТАКТЫ -->
<div class="cta" id="cta">
  <h3>Обсудим задачу?</h3>
  <div class="phone-big"><a href="tel:+79032026198">8 (903) 202-61-98</a></div>
  <p style="opacity:0.9; margin-bottom:10px;">ООО «Мастех»</p>
  <a href="mailto:info@mastech.ru" class="btn">Запросить счёт / КП</a>
  <p style="margin-top:14px; font-size:12px; opacity:0.7;">📍 Тверь, доставка по РФ</p>
</div>

<!-- КНОПКА НАВЕРХ -->
<a href="#top" class="back-to-top" title="Наверх"></a>

<!-- ФУТЕР -->
<div class="footer">
  © ООО «Мастех», 2026. Не является публичной офертой.
</div>

</body>
</html>
