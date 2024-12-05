<!DOCTYPE html> 
<html lang="fa"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>خدمات کابینت‌سازی</title> 
    <style> 
        @font-face {
            font-family: 'IranSans';
            src: url('fonts/IRANSans.woff2') format('woff2'),
                 url('fonts/IRANSans.woff') format('woff'),
                 url('fonts/IRANSans.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        @keyframes fadeIn { 
            from { opacity: 0; } 
            to { opacity: 1; } 
        } 

        body { 
            font-family: 'IranSans', Arial, Helvetica, sans-serif; 
            direction: rtl; 
            text-align: right; 
            background-color: #f9f9f9; 
            margin: 0; 
            padding: 0; 
            animation: fadeIn 1s ease-in-out; 
        } 

        .container { 
            width: 85%; 
            margin: auto; 
            overflow: hidden; 
        } 

        header { 
            background: linear-gradient(90deg, #77aaff, #3366cc); 
            color: #fff; 
            padding: 20px 0; 
            text-align: center; 
            animation: fadeIn 2s ease-in-out; 
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); 
        } 

        header h1 { 
            font-size: 2.5rem; 
            margin: 0; 
        } 

        header nav ul { 
            padding: 0; 
            margin: 10px 0 0; 
            list-style: none; 
            display: flex; 
            justify-content: center; 
        } 

        header nav ul li { 
            margin: 0 15px; 
        } 

        header nav ul li a { 
            color: #fff; 
            text-decoration: none; 
            font-weight: bold; 
            padding: 5px 10px; 
            transition: background-color 0.3s ease, color 0.3s ease; 
        } 

        header nav ul li a:hover { 
            background-color: #fff; 
            color: #3366cc; 
            border-radius: 5px; 
        } 

        .showcase { 
            background: url('cabinet.jpg') no-repeat center center/cover; 
            color: #fff; 
            height: 400px; 
            text-align: center; 
            display: flex; 
            flex-direction: column; 
            justify-content: center; 
            animation: fadeIn 3s ease-in-out; 
        } 

        .showcase h1 { 
            font-size: 3rem; 
            margin: 0; 
        } 

        .showcase p { 
            font-size: 1.2rem; 
            margin-top: 10px; 
            color:bold
        } 

        .section { 
            padding: 30px 20px; 
            margin: 20px 0; 
            background: #fff; 
            border-radius: 10px; 
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05); 
            animation: fadeIn 1.5s ease-in-out; 
        } 

        .section h2 { 
            font-size: 1.8rem; 
            color: #3366cc; 
            margin-bottom: 20px; 
            border-bottom: 3px solid #77aaff; 
            display: inline-block; 
            padding-bottom: 5px; 
        } 

        footer { 
            background: linear-gradient(90deg, #3366cc, #77aaff); 
            color: #fff; 
            text-align: center; 
            padding: 15px; 
            font-size: 0.9rem; 
            margin-top: 20px; 
        } 

        .comment-box input, .comment-box textarea { 
            width: 100%; 
            padding: 12px; 
            margin: 15px 0; 
            border: 1px solid #ddd; 
            border-radius: 5px; 
            font-size: 1rem; 
        } 

        .comment-box button { 
            padding: 12px 20px; 
            background-color: #3366cc; 
            color: #fff; 
            border: none; 
            cursor: pointer; 
            border-radius: 5px; 
            font-size: 1rem; 
            transition: background-color 0.3s ease; 
        } 

        .comment-box button:hover { 
            background-color: #77aaff; 
        } 

        select { 
            padding: 10px; 
            margin: 10px 0; 
            font-size
            : 1rem; 
            border: 1px solid #ddd; 
            border-radius: 5px; 
        } 

        .testimonial { 
            border: 1px solid #ddd; 
            padding: 20px; 
            margin: 20px 0; 
            background: #fafafa; 
            border-radius: 10px; 
        } 

        .testimonial p { 
            margin: 0 0 5px; 
            font-style: italic; 
        } 
    </style> 
</head> 
<body> 
    <header> 
        <h1>خدمات کابینت‌سازی</h1> 
        <nav> 
            <ul> 
                <li><a href="#services">خدمات ما</a></li> 
                <li><a href="#contact">تماس با ما</a></li> 
                <li><a href="#testimonials">نظرات مشتریان</a></li> 
                <li><a href="#about">درباره ما</a></li> 
            </ul> 
        </nav> 
    </header> 
 
    <section class="showcase"> 
        <h1>کابینت‌سازی حرفه‌ای</h1> 
        <p>طراحی و اجرای کابینت‌های مدرن و کلاسیک با بالاترین کیفیت</p> 
    </section> 
 
    <section class="section" id="services"> 
        <h2>خدمات ما</h2> 
        <ul> 
            <li>طراحی سفارشی کابینت</li> 
            <li>ساخت کابینت</li> 
            <li>نصب و اجرا</li> 
            <li>تعمیر و بازسازی کابینت</li> 
        </ul> 
    </section> 

    <section class="section" id="location"> 
        <h2>مکان شما کجاست؟</h2> 
        <label for="city">شهر خود را انتخاب کنید:</label>
        <select id="city" name="city">
            <option value="تهران">تهران</option>
            <option value="ری">ری</option>
            <option value="کرج">کرج</option>
            <!-- سایر گزینه‌ها -->
        </select>
    </section> 

    <section class="section" id="contact"> 
        <h2>تماس با ما</h2> 
        <p>شماره تماس: ۰۹۱۲۳۴۵۶۷۸۹</p> 
        <p>آدرس: تهران، خیابان آزادی</p> 
        <p>ایمیل: example@mail.com</p> 
        <p>وبسایت: www.example.com</p> 
    </section> 

    <section class="section" id="testimonials"> 
        <h2>نظرات مشتریان</h2> 
        <div class="testimonial"> 
            <p>"کیفیت کار بسیار بالا و تحویل به موقع. بسیار راضی هستم!"</p> 
            <p>- محمد، تهران</p> 
        </div> 
        <div class="testimonial"> 
            <p>"طراحی‌های خلاقانه و اجرای حرفه‌ای. قطعاً توصیه می‌کنم."</p> 
            <p>- سارا، اصفهان</p> 
        </div> 
    </section> 

    <section class="section" id="about"> 
        <h2>درباره ما</h2> 
        <p>ما با بیش از ۱۰ سال تجربه، بهترین خدمات را ارائه می‌دهیم.</p> 
    </section> 

    <section class="section" id="comments"> 
        <h2>نظرات شما</h2> 
        <div class="comment-box"> 
            <input type="text" placeholder="نام شما"> 
            <textarea rows="4" placeholder="نظر شما"></textarea> 
            <button>ارسال</button> 
        </div> 
    </section> 

    <footer> 
        <p>کلیه حقوق محفوظ است ©️ 2024</p> 
    </footer> 
</body> 
