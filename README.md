<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>کافه خانلی | منو</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'Vazirmatn', Tahoma, sans-serif;
    background: #1a120b;
    color: #f3e9dc;
    line-height: 1.8;
  }

  /* هدر */
  header {
    text-align: center;
    padding: 45px 20px 30px;
    background: linear-gradient(180deg, #2b1d12 0%, #1a120b 100%);
    border-bottom: 3px solid #c89b6d;
  }
  header h1 {
    font-size: 2.6rem;
    color: #e8c39e;
    letter-spacing: 1px;
  }
  header p {
    margin-top: 6px;
    font-size: 1.05rem;
    color: #b99a77;
  }
  .divider {
    width: 70px; height: 3px;
    background: #c89b6d;
    margin: 16px auto 0;
    border-radius: 5px;
  }

  main {
    max-width: 720px;
    margin: 0 auto;
    padding: 20px 18px 60px;
  }

  /* دسته‌بندی‌ها */
  section h2 {
    display: flex;
    align-items: center;
    gap: 12px;
    font-size: 1.35rem;
    color: #e8c39e;
    margin: 38px 0 16px;
  }
  section h2::after {
    content: "";
    flex: 1;
    height: 1px;
    background: #3d2c1c;
  }

  /* آیتم‌ها */
  .item {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 12px;
    padding: 11px 4px;
    border-bottom: 1px dashed #3d2c1c;
  }
  .item .name {
    font-size: 1.02rem;
    color: #f3e9dc;
  }
  .item .dots {
    flex: 1;
    border-bottom: 1px dotted #4a3826;
    transform: translateY(-4px);
  }
  .item .price {
    font-weight: bold;
    color: #c89b6d;
    white-space: nowrap;
  }

  footer {
    text-align: center;
    padding: 25px;
    font-size: 0.9rem;
    color: #8a6f54;
    border-top: 1px solid #3d2c1c;
  }
</style>
</head>
<body>

<header>
  <h1>☕ کافه خانلی</h1>
  <p>منوی دیجیتال</p>
  <div class="divider"></div>
</header>

<main>

  <!-- بار گرم -->
  <section>
    <h2>☕ بار گرم</h2>
    <div class="item"><div class="name">اسپرسو سینگل</div><div class="dots"></div><div class="price">۶۵,۰۰۰</div></div>
    <div class="item"><div class="name">اسپرسو دابل</div><div class="dots"></div><div class="price">۸۵,۰۰۰</div></div>
    <div class="item"><div class="name">آمریکانو</div><div class="dots"></div><div class="price">۹۵,۰۰۰</div></div>
    <div class="item"><div class="name">کاپوچینو</div><div class="dots"></div><div class="price">۱۱۰,۰۰۰</div></div>
    <div class="item"><div class="name">لاته</div><div class="dots"></div><div class="price">۱۱۰,۰۰۰</div></div>
    <div class="item"><div class="name">موکا</div><div class="dots"></div><div class="price">۱۳۰,۰۰۰</div></div>
    <div class="item"><div class="name">کارامل ماکیاتو</div><div class="dots"></div><div class="price">۱۳۰,۰۰۰</div></div>
    <div class="item"><div class="name">هات چاکلت</div><div class="dots"></div><div class="price">۱۲۰,۰۰۰</div></div>
    <div class="item"><div class="name">وایت چاکلت</div><div class="dots"></div><div class="price">۱۲۰۰۰۰</div></div>
  </section>

  <!-- بار سرد -->
  <section>
    <h2>🧊 بار سرد</h2>
    <div class="item"><div class="name">آیس آمریکانو</div><div class="dots"></div><div class="price">۹۵,۰۰۰</div></div>
    <div class="item"><div class="name">آیس لاته</div><div class="dots"></div><div class="price">۱۲۵,۰۰۰</div></div>
    <div class="item"><div class="name">آیس موکا</div><div class="dots"></div><div class="price">۱۴۰,۰۰۰</div></div>
    <div class="item"><div class="name">آیس کارامل ماکیاتو</div><div class="dots"></div><div class="price">۱۴۰,۰۰۰</div></div>
    <div class="item"><div class="name">آفوگاتو</div><div class="dots"></div><div class="price">۱۱۰,۰۰۰</div></div>
  </section>

  <!-- چای و دمنوش -->
  <section>
    <h2>🍵 چای و دمنوش</h2>
    <div class="item"><div class="name">چای سیاه قوری</div><div class="dots"></div><div class="price">۷۰,۰۰۰</div></div>
    <div class="item"><div class="name">چای سبز</div><div class="dots"></div><div class="price">۸۰,۰۰۰</div></div>
    <div class="item"><div class="name">دمنوش آرامبخش</div><div class="dots"></div><div class="price">۹۵,۰۰۰</div></div>
    <div class="item"><div class="name">دمنوش ترش</div><div class="dots"></div><div class="price">۹۵,۰۰۰</div></div>
    <div class="item"><div class="name">چای ماسالا</div><div class="dots"></div><div class="price">۱۱۰,۰۰۰</div></div>
  </section>

  <!-- شیک‌ها -->
  <section>
    <h2>🥤 شیک‌ها</h2>
    <div class="item"><div class="name">شیک شکلات</div><div class="dots"></div><div class="price">۱۵۰,۰۰۰</div></div>
    <div class="item"><div class="name">شیک وانیل</div><div class="dots"></div><div class="price">۱۴۰,۰۰۰</div></div>
    <div class="item"><div class="name">شیک نوتلا</div><div class="dots"></div><div class="price">۱۸۰,۰۰۰</div></div>
    <div class="item"><div class="name">شیک بادام زمینی</div><div class="dots"></div><div class="price">۱۷۰,۰۰۰</div></div>
    <div class="item"><div class="name">شیک توت فرنگی</div><div class="dots"></div><div class="price">۱۵۰,۰۰۰</div></div>
  </section>

  <!-- کیک و دسر -->
  <section>
    <h2>🍰 کیک و دسر</h2>
    <div class="item"><div class="name">کیک روز</div><div class="dots"></div><div class="price">۹0,۰۰۰</div></div>
    <div class="item"><div class="name">چیزکیک نوتلا</div><div class="dots"></div><div class="price">۱۳0,۰۰۰</div></div>
    <div class="item"><div class="name">براونی</div><div class="dots"></div><div class="price">۱۱۰,۰۰۰</div></div>
    <div class="item"><div class="name">تیرامیسو</div><div class="dots"></div><div class="price">۱۲۰,۰۰۰</div></div>
  </section>

  <!-- ماکتل و اسموتی -->
  <section>
    <h2>🍹 ماکتل و اسموتی</h2>
    <div class="item"><div class="name">موهیتو</div><div class="dots"></div><div class="price">۱۳۰,۰۰۰</div></div>
    <div class="item"><div class="name">پیناکولادا</div><div class="dots"></div><div class="price">۱۵۰,۰۰۰</div></div>
    <div class="item"><div class="name">بلوکوراچائو</div><div class="dots"></div><div class="price">۱۴۰,۰۰۰</div></div>
    <div class="item"><div class="name">اسموتی استوایی</div><div class="dots"></div><div class="price">۱۶۰,۰۰۰</div></div>
    <div class="item"><div class="name">اسموتی توت فرنگی</div><div class="dots"></div><div class="price">۱۵۰,۰۰۰</div></div>
  </section>

  <!-- صبحانه -->
  <section>
    <h2>🍳 صبحانه</h2>
    <div class="item"><div class="name">صبحانه انگلیسی</div><div class="dots"></div><div class="price">۲۸۰,۰۰۰</div></div>
    <div class="item"><div class="name">املت بیکن</div><div class="dots"></div><div class="price">۱۶۰,۰۰۰</div></div>
    <div class="item"><div class="name">املت گوجه</div><div class="dots"></div><div class="price">۱۲۰,۰۰۰</div></div>
    <div class="item"><div class="name">نیمرو با بیکن</div><div class="dots"></div><div class="price">۱۴۰,۰۰۰</div></div>
  </section>

  <!-- پیش‌غذا و سالاد -->
  <section>
    <h2>🥗 پیش‌غذا و سالاد</h2>
    <div class="item"><div class="name">سیب زمینی سرخ کرده</div><div class="dots"></div><div class="price">۱۰۰,۰۰۰</div></div>
    <div class="item"><div class="name">سیب زمینی با پنیر</div><div class="dots"></div><div class="price">۱۳0,۰۰۰</div></div>
    <div class="item"><div class="name">سالاد سزار با مرغ گریل</div><div class="dots"></div><div class="price">۲۲۰,۰۰۰</div></div>
    <div class="item"><div class="name">سالاد فصل</div><div class="dots"></div><div class="price">۱۱۰,۰۰۰</div></div>
  </section>

  <!-- ساندویچ و برگر -->
  <section>
    <h2>🍔 ساندویچ و برگر</h2>
    <div class="item"><div class="name">برگر مخصوص خانلی</div><div class="dots"></div><div class="price">۲۷۰,۰۰۰</div></div>
    <div class="item"><div class="name">چیزبرگر</div><div class="dots"></div><div class="price">۲۵0,۰۰۰</div></div>
    <div class="item"><div class="name">ساندویچ فیله مرغ</div><div class="dots"></div><div class="price">۲۳۰,۰۰۰</div></div>
    <div class="item"><div class="name">پاستا آلفردو</div><div class="dots"></div><div class="price">۲۴۰,۰۰۰</div></div>
  </section>

</main>

<footer>
  کافه خانلی
</footer>

</body>
</html>
