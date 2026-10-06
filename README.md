<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>مكتبة بغداد | كتب عربية</title>

    <meta name="description" content="مكتبة بغداد - مكتبة عربية للكتب والقراءة">

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, Tahoma, sans-serif;
            background: #f7f5f0;
            color: #222;
            line-height: 1.8;
        }

        header {
            background: #171717;
            color: white;
            padding: 18px 6%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .logo {
            font-size: 25px;
            font-weight: bold;
        }

        nav {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 15px;
        }

        nav a:hover {
            color: #d4af37;
        }

        .hero {
            background: linear-gradient(135deg, #222, #444);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        .hero h1 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 19px;
            color: #ddd;
            margin-bottom: 30px;
        }

        .search {
            max-width: 600px;
            margin: auto;
            display: flex;
        }

        .search input {
            width: 100%;
            padding: 15px;
            border: none;
            border-radius: 0 8px 8px 0;
            font-size: 16px;
            outline: none;
        }

        .search button {
            border: none;
            padding: 0 25px;
            background: #d4af37;
            color: #111;
            font-weight: bold;
            border-radius: 8px 0 0 8px;
            cursor: pointer;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            padding: 50px 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 35px;
        }

        .section-title h2 {
            font-size: 30px;
            margin-bottom: 8px;
        }

        .section-title p {
            color: #777;
        }

        .categories {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
            gap: 15px;
            margin-bottom: 60px;
        }

        .category {
            background: white;
            padding: 25px 15px;
            text-align: center;
            border-radius: 12px;
            box-shadow: 0 3px 15px rgba(0,0,0,0.06);
            text-decoration: none;
            color: #222;
            transition: 0.2s;
        }

        .category:hover {
            transform: translateY(-4px);
        }

        .category span {
            display: block;
            font-size: 30px;
            margin-bottom: 8px;
        }

        .books {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
            gap: 22px;
        }

        .book {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 3px 15px rgba(0,0,0,0.07);
        }

        .book-cover {
            height: 190px;
            background: #292929;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }

        .book-cover h3 {
            font-size: 22px;
        }

        .book-info {
            padding: 20px;
        }

        .book-info p {
            color: #777;
            margin: 5px 0 15px;
        }

        .book-button {
            display: inline-block;
            background: #222;
            color: white;
            text-decoration: none;
            padding: 8px 18px;
            border-radius: 6px;
        }

        .about {
            background: white;
            border-radius: 14px;
            padding: 35px;
            margin-top: 60px;
            text-align: center;
        }

        footer {
            background: #171717;
            color: #aaa;
            text-align: center;
            padding: 35px 20px;
            margin-top: 50px;
        }

        footer strong {
            color: white;
        }

        @media (max-width: 600px) {
            .hero h1 {
                font-size: 31px;
            }

            header {
                justify-content: center;
            }

            nav {
                justify-content: center;
            }

            .search input {
                font-size: 14px;
            }
        }
    </style>
</head>

<body>

<header>
    <div class="logo">📚 مكتبة بغداد</div>

    <nav>
        <a href="#">الرئيسية</a>
        <a href="#books">الكتب</a>
        <a href="#categories">التصنيفات</a>
        <a href="#about">عن المكتبة</a>
    </nav>
</header>

<section class="hero">

    <h1>مرحباً بك في مكتبة بغداد</h1>

    <p>
        مكتبة عربية رقمية للقراءة واكتشاف الكتب
    </p>

    <div class="search">
        <input type="text" placeholder="ابحث عن كتاب أو مؤلف...">
        <button>بحث</button>
    </div>

</section>

<main class="container">

    <section id="categories">

        <div class="section-title">
            <h2>التصنيفات</h2>
            <p>اكتشف الكتب حسب المجال الذي تفضله</p>
        </div>

        <div class="categories">

            <a class="category" href="#">
                <span>📖</span>
                الأدب
            </a>

            <a class="category" href="#">
                <span>🏛️</span>
                التاريخ
            </a>

            <a class="category" href="#">
                <span>🧠</span>
                الفكر والفلسفة
            </a>

            <a class="category" href="#">
                <span>🔬</span>
                العلوم
            </a>

            <a class="category" href="#">
                <span>✍️</span>
                الروايات
            </a>

            <a class="category" href="#">
                <span>🌍</span>
                الثقافة
            </a>

        </div>

    </section>


    <section id="books">

        <div class="section-title">
            <h2>كتب مختارة</h2>
            <p>مجموعة من الكتب الموجودة في المكتبة</p>
        </div>

        <div class="books">

            <article class="book">

                <div class="book-cover">
                    <h3>الأيام</h3>
                </div>

                <div class="book-info">
                    <h3>الأيام</h3>
                    <p>طه حسين</p>
                    <a class="book-button" href="#">
                        قراءة الكتاب
                    </a>
                </div>

            </article>


            <article class="book">

                <div class="book-cover">
                    <h3>حي بن يقظان</h3>
                </div>

                <div class="book-info">
                    <h3>حي بن يقظان</h3>
                    <p>ابن طفيل</p>
                    <a class="book-button" href="#">
                        قراءة الكتاب
                    </a>
                </div>

            </article>


            <article class="book">

                <div class="book-cover">
                    <h3>كليلة ودمنة</h3>
                </div>

                <div class="book-info">
                    <h3>كليلة ودمنة</h3>
                    <p>ابن المقفع</p>
                    <a class="book-button" href="#">
                        قراءة الكتاب
                    </a>
                </div>

            </article>


            <article class="book">

                <div class="book-cover">
                    <h3>رسائل الجاحظ</h3>
                </div>

                <div class="book-info">
                    <h3>رسائل الجاحظ</h3>
                    <p>الجاحظ</p>
                    <a class="book-button" href="#">
                        قراءة الكتاب
                    </a>
                </div>

            </article>

        </div>

    </section>


    <section id="about" class="about">

        <h2>عن مكتبة بغداد</h2>

        <p>
            مكتبة بغداد مشروع عربي رقمي يهدف إلى تسهيل الوصول
            إلى الكتب والمصادر العربية بطريقة بسيطة ومنظمة.
        </p>

    </section>

</main>


<footer>

    <p>
        © 2026 <strong>مكتبة بغداد</strong>
    </p>

    <p>
        جميع الحقوق محفوظة
    </p>

</footer>

</body>
</html>
