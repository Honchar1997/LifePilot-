<!DOCTYPE html>
<html lang="he">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LifePilot - האפליקציה לחיים חכמים</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5fdf7;
      color: #333;
      direction: rtl;
    }
    header {
      background-color: #34a853;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #d7f5e2;
      padding: 10px;
      gap: 15px;
    }
    nav a {
      text-decoration: none;
      color: #0d5725;
      font-weight: bold;
    }
    section {
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #218838;
    }
    .features, .team, .downloads, .faq, .contact, .developer, .blog {
      margin-top: 40px;
    }
    footer {
      background-color: #34a853;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
    .app-buttons img, .screenshots img {
      width: 150px;
      margin: 10px;
    }
    .screenshots {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }
    iframe {
      width: 100%;
      height: 315px;
      border: none;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>LifePilot</h1>
  <p>האפליקציה שתעזור לך לנהל את החיים שלך בצורה חכמה, רגועה ויעילה</p>
</header>

<nav>
  <a href="#about">מה זה LifePilot?</a>
  <a href="#features">יתרונות</a>
  <a href="#downloads">הורדות</a>
  <a href="#team">עלינו</a>
  <a href="#blog">בלוג</a>
  <a href="#contact">צור קשר</a>
  <a href="#developer">למפתחים</a>
</nav>

<section id="home">
  <h2>הכרת האפליקציה</h2>
  <iframe src="https://www.youtube.com/watch?v=iDbdXTMnOmE&ab_channel=TED-Ed" allowfullscreen></iframe>
</section>

<section id="features" class="features">
  <h2>היתרונות של LifePilot</h2>
  <ul>
    <li>🕒 חוסך זמן יקר</li>
    <li>🧠 משפר סדר אישי וארגוני</li>
    <li>🤝 מסנכרן את החיים שלך עם המשפחה, העבודה והזמן הפנוי</li>
    <li>📆 תכנון יומי, שבועי וחודשי בלחיצת כפתור</li>
    <li>🔔 תזכורות חכמות מבוססות הקשר</li>
  </ul>
</section>

<section id="about">
  <h2>מה זה LifePilot?</h2>
  <p>LifePilot היא אפליקציה חכמה לניהול החיים האישיים, המשפחתיים והמקצועיים שלך. אנחנו מאמינים שכל אחד ואחת יכולים לנהל את הזמן והחיים בצורה חכמה יותר – עם הכלים הנכונים.</p>
  <p>האפליקציה מיועדת להורים עסוקים, יזמים, סטודנטים, חיילים, וכל מי שמרגיש שהוא "רץ" אחרי הזמן – במקום לנהל אותו.</p>
  <div class="screenshots">
    <img src="https://via.placeholder.com/200x400?text=מסך+ראשי">
    <img src="https://via.placeholder.com/200x400?text=תכנון+שבועי">
    <img src="https://via.placeholder.com/200x400?text=תזכורות">
  </div>
</section>

<section id="downloads" class="downloads">
  <h2>הורידו את האפליקציה</h2>
  <p>התחילו את המסע שלכם לניהול חיים חכם:</p>
  <div class="app-buttons">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Available_on_the_App_Store_%28black%29_SVG.svg" alt="App Store">
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play">
  </div>
</section>

<section id="team" class="team">
  <h2>מי אנחנו?</h2>
  <p>LifePilot נולדה מתוך צורך אמיתי של יזמים ישראלים, אנשי צבא, הורים ומנהלים – ליצור מערכת שתאפשר תיאום טוב יותר בין החיים האישיים, המשפחתיים והמקצועיים. אנחנו צוות של מפתחים, מעצבים ואנשי תוכן, שמאמינים שלכל אדם מגיעה תחושת שליטה וסדר.</p>
  <p>אנחנו לא רק מפתחים אפליקציה – אלא מפתחים דרך חיים חדשה.</p>
</section>

<section id="blog" class="blog">
  <h2>בלוג וטיפים</h2>
  <ul>
    <li>10 טיפים לניהול זמן יעיל</li>
    <li>איך מתכננים יום עבודה חכם עם ילדים בבית</li>
    <li>שיטות GTD למתחילים</li>
  </ul>
</section>

<section id="contact" class="contact">
  <h2>צור קשר</h2>
  <p>רוצים לשאול שאלה, לשתף פעולה או לקבל עזרה? מלאו את הטופס ונחזור אליכם:</p>
  <form>
    <label>שם:</label><br>
    <input type="text" name="name"><br>
    <label>אימייל:</label><br>
    <input type="email" name="email"><br>
    <label>הודעה:</label><br>
    <textarea name="message"></textarea><br>
    <button type="submit">שלח</button>
  </form>
</section>

<section id="developer" class="developer">
  <h2>למפתחים</h2>
  <p>יש לנו API פתוח המאפשר חיבורי צד שלישי – כולל יומנים חכמים, וואטסאפ ועוד. תיעוד מלא יפורסם כאן בקרוב.</p>
</section>

<footer>
  <p>© 2025 LifePilot | כל הזכויות שמורות</p>
  <p><a href="#" style="color: white; text-decoration: underline;">מדיניות פרטיות</a> | <a href="#" style="color: white; text-decoration: underline;">תנאי שימוש</a></p>
</footer>

</body>
</html>
