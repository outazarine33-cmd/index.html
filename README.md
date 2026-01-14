<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>الموقع الرسمي للمنتجات</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&family=Inter:wght@300;400&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  background: linear-gradient(180deg, rgba(30,20,10,0.95), rgba(245,240,230,0.95));
  color: #111;
  min-height: 100vh;
}

/* container */
.container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 40px 20px;
}

/* عنوان الموقع */
.brand {
  font-family: 'Playfair Display', serif;
  font-size: 36px;
  color: #fff;
  text-align: center;
  margin-bottom: 10px;
}

.subtitle {
  text-align: center;
  color: #e8dccb;
  font-size: 16px;
  margin-bottom: 40px;
}

/* الصف ديال المنتجات */
.product-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
}

/* بطاقة المنتج */
.product-card {
  background: rgba(255,255,255,0.95);
  border-radius: 20px;
  width: 280px;
  padding: 20px;
  box-shadow: 0 20px 50px rgba(0,0,0,0.25);
  cursor: pointer;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  display: flex;
  flex-direction: column;
  text-align: center;
}

.product-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 25px 70px rgba(0,0,0,0.35);
}

/* صورة المنتج */
.product-image {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 15px;
  transition: transform 0.3s ease;
}

.product-card:hover .product-image {
  transform: scale(1.05);
}

/* اسم المنتج */
.title {
  font-family: 'Playfair Display', serif;
  font-size: 22px;
  margin-bottom: 10px;
}

/* وصف المنتج */
.desc {
  font-size: 14.5px;
  color: #444;
  margin-bottom: 15px;
  line-height: 1.6;
}

/* مميزات */
.features {
  list-style: none;
  margin-bottom: 15px;
}

.features li {
  font-size: 14px;
  margin-bottom: 6px;
}

/* السعر */
.price {
  font-size: 20px;
  font-weight: 600;
  margin-bottom: 15px;
}

/* زر واتساب */
.btn {
  background: linear-gradient(135deg, #25D366, #1ebe5d);
  color: #fff;
  text-decoration: none;
  padding: 12px 0;
  border-radius: 12px;
  font-size: 16px;
  font-weight: bold;
  transition: background 0.3s ease;
}

.btn:hover {
  background: linear-gradient(135deg, #1ebe5d, #25D366);
}

/* responsive */
@media(max-width:900px){
  .product-row {
    flex-direction: column;
    align-items: center;
  }
}

</style>
</head>
<body>

<div class="container">

  <div class="brand">Brand Officiel</div>
  <div class="subtitle">منتجات راقية، تجربة مثالية.</div>

  <div class="product-row">
    
    <!-- المنتج الأول -->
    <a href="https://wa.me/212691444558?text=سلام، بغيت نطلب الجل" target="_blank" class="product-card">
      <img src="gel.jpg" alt="جيل تثبيت الشعر" class="product-image">
      <div class="title">جيل تثبيت الشعر</div>
      <div class="desc">
        جل قوي لتثبيت الشعر، يعطي لمعة طبيعية ويترك شعرك ثابت طوال اليوم بدون قساوة.
      </div>
      <ul class="features">
        <li>✔ ثبات قوي</li>
        <li>✔ ملمس طبيعي</li>
        <li>✔ مناسب للاستخدام اليومي</li>
      </ul>
      <div class="price">35 درهم</div>
      <div class="btn">اطلب الآن عبر واتساب</div>
    </a>

    <!-- المنتج الثاني -->
    <a href="https://wa.me/212691444558?text=سلام، بغيت نطلب سبراي" target="_blank" class="product-card">
      <img src="spray.jpg" alt="سبراي تثبيت الشعر" class="product-image">
      <div class="title">سبراي تثبيت الشعر</div>
      <div class="desc">
        سبراي خفيف يعطي ثبات متوسط ولمسة ناعمة مع حماية من الرطوبة.
      </div>
      <ul class="features">
        <li>✔ ثبات متوسط</li>
        <li>✔ حماية من الرطوبة</li>
        <li>✔ مثالي للشعر القصير والطويل</li>
      </ul>
      <div class="price">40 درهم</div>
      <div class="btn">اطلب الآن عبر واتساب</div>
    </a>

    <!-- المنتج الثالث -->
    <a href="https://wa.me/212691444558?text=سلام، بغيت نطلب واكس" target="_blank" class="product-card">
      <img src="wax.jpg" alt="واكس الشعر" class="product-image">
      <div class="title">واكس الشعر</div>
      <div class="desc">
        واكس غني لتشكيل الشعر بسهولة ولمسة نهائية لامعة طبيعية.
      </div>
      <ul class="features">
        <li>✔ تشكيل سهل ومرن</li>
        <li>✔ لمسة لامعة طبيعية</li>
        <li>✔ مثالي للشعر القصير والطويل</li>
      </ul>
      <div class="price">45 درهم</div>
      <div class="btn">اطلب الآن عبر واتساب</div>
    </a>

  </div>

</div>

</body>
</html>
