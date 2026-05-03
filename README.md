<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мастех | Промышленные дозаторы</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
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
      font-size: 22px;
      font-weight: 700;
      color: #0f172a;
      margin-bottom: 8px;
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
      font-size: 15px;
    }

    /* ГЕРОЙ */
    .hero {
      background: #0f172a;
      color: white;
      text-align: center;
      padding: 40px 16px;
    }

    .hero h1 {
      font-size: 24px;
      font-weight: 700;
      margin-bottom: 12px;
    }

    .hero p {
      font-size: 15px;
      margin-bottom: 16px;
      opacity: 0.9;
    }

    .price-box {
      background: rgba(255,255,255,0.1);
      border-radius: 10px;
      padding: 14px;
      display: inline-block;
      margin-bottom: 10px;
    }

    .price-box .old {
      text-decoration: line-through;
      opacity: 0.6;
      font-size: 14px;
      display: block;
    }

    .price-box .new {
      font-size: 28px;
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
      padding: 36px 16px;
    }

    .section h2 {
      font-size: 22px;
      font-weight: 700;
      margin-bottom: 16px;
      color: #0f172a;
    }

    /* ТАБЛИЦА */
    .spec-table {
      background: white;
      border-radius: 12px;
      padding: 4px 0;
    }

    .spec-row {
      padding: 12px 14px;
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
      border-radius: 12px;
      padding: 18px 14px;
      margin-bottom: 12px;
      border: 1px solid #e2e8f0;
    }

    .card h3 {
      font-size: 17px;
      margin-bottom: 6px;
    }

    .card p {
      font-size: 14px;
      color: #475569;
    }

    /* ПРЕИМУЩЕСТВА */
    .adv-item {
      background: white;
      border-radius: 12px;
      padding: 16px 14px;
      margin-bottom: 10px;
      border: 1px solid #e2e8f0;
    }

    .adv-item .icon {
      font-size: 22px;
      margin-bottom: 6px;
    }

    .adv-item strong {
      display: block;
      font-size: 16px;
      margin-bottom: 4px;
    }

    .adv-item span {
      font-size: 14px;
      color: #475569;
    }

    /* CTA */
    .cta {
      background: #2563eb;
      color: white;
      border-radius: 14px;
      padding: 28px 16px;
      text-align: center;
      margin: 0 16px 36px;
    }

    .cta h3 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    .cta .phone-big {
      font-size: 20px;
      font-weight: 700;
      margin-bottom: 4px;
    }

    .cta .btn {
      display: inline-block;
      background: white;
      color: #2563eb;
      padding: 14px 28px;
      border-radius: 10px;
      font-weight: 700;
      text-decoration: none;
      font-size: 16px;
      margin-top: 14px;
    }

    /* ФУТЕР */
    .footer {
      text-align: center;
      padding: 20px 16px;
      color: #64748b;
      font-size: 13px;
      border-top: 1px solid #e2e8f0;
    }

    /* БЕЛЫЙ ФОН ДЛЯ ЧЕРЕДУЮЩИХСЯ СЕКЦИЙ */
    .bg-white {
      background: white;
    }
  </style>
</head>
<body>

<!-- ШАПКА -->
<div class="header">
  <div class="logo">МАСТЕХ</div>
  <a href="tel:+79040087191" class="phone">+7 (904) 008-71-91</a>
  <a href="#cta">Запросить КП</a>
</div>

<!-- ГЕРОЙ -->
<div class="hero">
  <h1>Объёмный дозатор для литья пластмасс</h1>
  <p>Прямой аналог Shini SCM. Собственная разработка и программа управления. Сделано в Твери.</p>
  <div class="price-box">
    <span class="old">Импортный аналог 350 000 ₽</span>
    <span class="new">от 180 000 ₽</span>
  </div>
  <div class="note">• В наличии • Сервис ЦФО • Гарантия 12 мес.</div>
</div>

<!-- ХАРАКТЕРИСТИКИ -->
<div class="section">
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

<!-- ПРЕИМУЩЕСТВА -->
<div class="section">
  <h2>Почему выбирают «Мастех»</h2>
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

<!-- КОНТАКТЫ -->
<div class="cta" id="cta">
  <h3>Обсудим задачу?</h3>
  <div class="phone-big">+7 (904) 008-71-91</div>
  <p style="opacity:0.9; margin-bottom:4px;">Александр Мензулов, технический директор</p>
  <p style="font-size:13px; opacity:0.7; margin-bottom:10px;">ИП Мензулов А.А. | ИНН 690140652031</p>
  <a href="mailto:info@mastech.ru" class="btn">Запросить счёт / КП</a>
  <p style="margin-top:12px; font-size:12px; opacity:0.7;">📍 Тверь, доставка по РФ</p>
</div>

<!-- ФУТЕР -->
<div class="footer">
  © Мастех, 2026. Не является публичной офертой.
</div>

</body>
</html>
