# Maak-website.
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>معك - العمل التطوعي</title>
  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
      background-color: #f4fdf6;
      color: #1b5e20;
    }

    header {
      background-color: #2e7d32;
      color: white;
      padding: 25px 0;
      text-align: center;
    }

    nav {
      background-color: #388e3c;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      background-color: #2e7d32;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #2e7d32;
    }

    ul li {
      margin-bottom: 10px;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    input, textarea, button {
      margin: 10px 0;
      padding: 10px;
      font-size: 16px;
      border: 1px solid #c8e6c9;
      border-radius: 5px;
    }

    input:focus, textarea:focus {
      outline: none;
      border-color: #66bb6a;
      box-shadow: 0 0 5px #a5d6a7;
    }

    button {
      background-color: #43a047;
      color: white;
      border: none;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #388e3c;
    }

    footer {
      background-color: #e8f5e9;
      text-align: center;
      padding: 20px;
      color: #2e7d32;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>معك - منصة العمل التطوعي</h1>
  </header>

  <nav>
    <a href="#home">الرئيسية</a>
    <a href="#about">عن معك</a>
    <a href="#goals">أهدافنا</a>
    <a href="#signup">سجل معنا</a>
    <a href="#contact">تواصل معنا</a>
  </nav>

  <section id="home">
    <h2>مرحبًا بك في معك</h2>
    <p>منصة تهدف لتعزيز روح التطوع وخدمة المجتمع بكل حب واهتمام.</p>
  </section>

  <section id="about">
    <h2>عن معك</h2>
    <p>"معك" هي مبادرة تطوعية تسعى لتجميع الجهود الشبابية لخدمة المجتمع في مجالات متعددة مثل التعليم، البيئة، والمساندة الاجتماعية.</p>
  </section>

  <section id="goals">
    <h2>أهدافنا</h2>
    <ul>
      <li>نشر ثقافة العمل التطوعي.</li>
      <li>بناء مجتمع مترابط ومتعاون.</li>
      <li>توفير فرص تطوع متنوعة ومؤثرة.</li>
    </ul>
  </section>

  <section id="signup">
    <h2>سجل معنا</h2>
    <form>
      <input type="text" placeholder="الاسم الكامل" required>
      <input type="email" placeholder="البريد الإلكتروني" required>
      <input type="text" placeholder="رقم الجوال" required>
      <textarea placeholder="ما المجالات التي تود التطوع فيها؟" rows="4" required></textarea>
      <button type="submit">إرسال</button>
    </form>
  </section>

  <section id="contact">
    <h2>تواصل معنا</h2>
    <p>لأي استفسار، يمكنك مراسلتنا عبر البريد الإلكتروني: <strong>info@maak.org</strong></p>
  </section>

  <footer>
    &copy; 2025 معك. جميع الحقوق محفوظة.
  </footer>

</body>
</html>
