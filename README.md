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
    padding: 50px 20px 35px;
    background: linear-gradient(180deg, #2b1d12 0%, #1a120b 100%);
    border-bottom: 3px solid #c89b6d;
  }
  header h1 {
    font-size: 2.6rem;
    color: #e8c39e;
    letter-spacing: 1px;
  }
  header p {
    margin-top: 8px;
    font-size: 1.05rem;
    color: #b99a77;
  }
  .divider {
    width: 70px; height: 3px;
    background: #c89b6d;
    margin: 18px auto 0;
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
    font-size: 1.4rem;
    color: #e8c39e;
    margin: 42px 0 18px;
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
    padding: 12px 4px;
    border-bottom: 1px dashed #3d2c1c;
  }
  .item .name {
    font-size: 1.05rem;
    color: #f3e9dc;
  }
  .item .desc {
    display: block;
    font-size: 0.85rem;
    color: #9a7f63;
    margin-top: 2px;
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
  <p>منوی نوشیدنی و غذا</p>
  <div class="divider"></div>
</header>

<main>

  <section>
    <h2>☕ بار گرم</h2>
    <div class="item"><div class="name">اسپرسو</div><div class="dots"></div><div class="price">۹۵</div></div>
    <div class="item"><div class="name">آمریکانو</div><div class="dots"></div><div class="price">۱۱۰</div></div>
    <div class="item"><div class="name">لاته</div><div class="dots"></div><div class="price">۱۳۰</div></div>
    <div class="item"><div class="name">کاپوچینو</div><div class="dots"></div><div class="price">۱۳۰</div></div>
    <div class="item"><div class="name">موکا</div><div class="dots"></div><div class="price">۱۵۰</div></div>
    <div class="item"><div class="name">هات چاکلت</div><div class="dots"></div><div class="price">۱۵۰</div></div>
  </section>

  <section>
    <h2>🧊 بار سرد</h2>
    <div class="item"><div class="name">آیس آمریکانو</div><div class="dots"></div><div class="price">۱۲۰</div></div>
    <div class="item"><div class="name">آیس لاته</div><div class="dots"></div><div class="price">۱۴۰</div></div>
    <div class="item"><div class="name">آیس موکا</div><div class="dots"></div><div class="price">۱۶۰</div></div>
    <div class="item"><div class="name">فراپه</div><div class="dots"></div><div class="price">۱۶۰</div></div>
  </section>

  <section>
    <h2>🍵 چای و دمنوش</h2>
    <div class="item"><div class="name">چای سیاه</div><div class="dots"></div><div class="price">۸۰</div></div>
    <div class="item"><div class="name">دمنوش</div><div class="dots"></div><div class="price">۹۵</div></div>
    <div class="item"><div class="name">چای ماسالا</div><div class="dots"></div><div class="price">۱۲۰</div></div>
  </section>

  <section>
    <h2>🥤 شیک</h2>
    <div class="item"><div class="name">شیک شکلات</div><div class="dots"></div><div class="price">۱۷۰</div></div>
    <div class="item"><div class="name">شیک وانیل</div><div class="dots"></div><div class="price">۱۷۰</div></div>
    <div class="item"><div class="name">شیک نوتلا</div><div class="dots"></div><div class="price">۱۹۰</div></div>
  </section>

  <section>
    <h2>🍰 کیک و دسر</h2>
    <div class="item"><div class="name">چیز کیک</div><div class="dots"></div><div class="price">۱۴۵</div></div>
    <div class="item"><div class="name">کیک شکلاتی</div><div class="dots"></div><div class="price">۱۳۵</div></div>
    <div class="item"><div class="name">تیرامیسو</div><div class="dots"></div><div class="price">۱۶۵</div></div>
  </section>

  <section>
    <h2>🍹 ماکتل</h2>
    <div class="item"><div class="name">موحدو</div><div class="dots"></div><div class="price">۱۶۰</div></div>
    <div class="item"><div class="name">سونرایز</div><div class="dots"></div><div class="price">۱۶۰</div></div>
    <div class="item"><div class="name">پینا کولادا</div><div class="dots"></div><div class="price">۱۸۰</div></div>
  </section>

  <section>
    <h2>🍓 اسموتی</h2>
    <div class="item"><div class="name">اسموتی توت‌فرنگی</div><div class="dots"></div><div class="price">۱۵۰</div></div>
    <div class="item"><div class="name">اسموتی موز</div><div class="dots"></div><div class="price">۱۵۰</div></div>
    <div class="item"><div class="name">اسموتی مخلوط</div><div class="dots"></div><div class="price">۱۶۵</div></div>
  </section>

  <section>
    <h2>🍳 صبحانه</h2>
    <div class="item"><div class="name">صبحانه انگلیسی</div><div class="dots"></div><div class="price">۲۸۰</div></div>
    <div class="item"><div class="name">املت ویژه</div><div class="dots"></div><div class="price">۱۸۰</div></div>
    <div class="item"><div class="name">نان و پنیر و گردو</div><div class="dots"></div><div class="price">۱۲۰</div></div>
  </section>

  <section>
    <h2>🥗 پیش‌غذا</h2>
    <div class="item"><div class="name">سیب‌زمینی سرخ‌کرده</div><div class="dots"></div><div class="price">۱۱۰</div></div>
    <div class="item"><div class="name">ناچو</div><div class="dots"></div><div class="price">۱۶۰</div></div>
    <div class="item"><div class="name">سالاد سزار</div><div class="dots"></div><div class="price">۱۹۰</div></div>
  </section>

  <section>
    <h2>🥪 ساندویچ و پاستا</h2>
    <div class="item"><div class="name">ساندویچ مرغ</div><div class="dots"></div><div class="price">۲۲۰</div></div>
    <div class="item"><div class="name">برگر ویژه</div><div class="dots"></div><div class="price">۲۶۰</div></div>
    <div class="item"><div class="name">پاستا آلفردو</div><div class="dots"></div><div class="price">۲۴۰</div></div>
    <div class="item"><div class="name">پاستا پستو</div><div class="dots"></div><div class="price">۲۴۰</div></div>
  </section>

</main>

<footer>
  کافه خانلی
</footer>

</body>
</html>
