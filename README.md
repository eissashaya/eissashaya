<title>عيسى إبراهيم شايع | Eissa Ibrahim Shaya</title> <style> * { margin: 0; padding: 0; box-sizing: border-box; }
body { background: linear-gradient(145deg, #f7f9fc 0%, #e9edf2 100%); font-family: 'Segoe UI', Roboto, system-ui, -apple-system, sans-serif; padding: 40px 20px; display: flex; justify-content: center; align-items: center; min-height: 100vh; }

  .card {
        max-width: 1100px;
        width: 100%;
        background: rgba(255,255,255,0.85);
        backdrop-filter: blur(4px);
        -webkit-backdrop-filter: blur(4px);
        border-radius: 48px;
        padding: 35px 30px 45px;
        box-shadow: 0 25px 50px -12px rgba(0,0,0,0.25), 0 4px 18px 0 rgba(0,0,0,0.08);
        transition: all 0.3s ease;
        border: 1px solid rgba(255,255,255,0.6);
    }

    /* تنسيق عام */
.text-center {
        text-align: center;
    }
    .flex-center {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        gap: 12px;
    }
    .mt-20 { margin-top: 20px; }
    .mt-30 { margin-top: 30px; }
    .mb-20 { margin-bottom: 20px; }
    .mb-10 { margin-bottom: 10px; }
    .gap-8 { gap: 8px; }
    .gap-16 { gap: 16px; }
    .separator {
        width: 80px;
        height: 3px;
        background: linear-gradient(90deg, #1E90FF, #00b4d8, #1E90FF);
        border-radius: 12px;
        margin: 20px auto 25px;
    }

    /* العناوين */
  h1 {
        font-size: 2.6rem;
        font-weight: 700;
        letter-spacing: -0.5px;
        color: #0b1a2e;
    }
    h1 span {
        color: #1E90FF;
        background: linear-gradient(135deg, #1E90FF, #0077b6);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }
    h3 {
        font-size: 1.7rem;
        font-weight: 600;
        color: #1a2a3a;
        margin-bottom: 10px;
        letter-spacing: -0.3px;
    }

    /* الوصف */
.description {
        font-size: 1.1rem;
        line-height: 1.7;
        color: #1f2a3a;
        background: rgba(30, 144, 255, 0.04);
        padding: 18px 25px;
        border-radius: 60px;
        display: inline-block;
        backdrop-filter: blur(2px);
        border: 1px solid rgba(30, 144, 255, 0.15);
        margin-top: 6px;
    }
    .description i {
        margin: 0 4px;
        color: #1E90FF;
    }

    /* أيقونات المهارات */
  .skill-icons {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        gap: 14px 20px;
        margin: 8px 0 5px;
    }
    .skill-icons img {
        width: 48px;
        height: 48px;
        transition: transform 0.2s ease, filter 0.2s;
        filter: drop-shadow(0 4px 6px rgba(0,0,0,0.05));
    }
    .skill-icons img:hover {
        transform: scale(1.12) translateY(-4px);
        filter: drop-shadow(0 8px 12px rgba(30, 144, 255, 0.25));
    }

    /* بطاقات الإحصائيات */
 .stats-grid {
      display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: stretch;
        gap: 25px 30px;
        margin-top: 15px;
    }
    .stats-grid img {
        border-radius: 18px;
        box-shadow: 0 8px 24px rgba(0,0,0,0.10);
        transition: 0.25s ease;
        background: #ffffffcc;
        padding: 6px 4px;
        max-width: 100%;
        height: auto;
        border: 1px solid rgba(255,255,255,0.7);
    }
    .stats-grid img:hover {
        transform: scale(1.02);
        box-shadow: 0 12px 32px rgba(0, 40, 80, 0.18);
    }

    /* أزرار التواصل */
 .social-links {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        gap: 10px 16px;
        margin-top: 8px;
    }
    .social-links a {
        display: inline-block;
        transition: 0.2s ease;
        border-radius: 60px;
        background: rgba(255,255,255,0.6);
        padding: 4px 6px;
        backdrop-filter: blur(2px);
        box-shadow: 0 2px 8px rgba(0,0,0,0.02);
    }
    .social-links a:hover {
        transform: translateY(-6px) scale(1.03);
        background: #ffffff;
        box-shadow: 0 12px 24px -8px rgba(30, 144, 255, 0.25);
    }
    .social-links img {
        width: 48px;
        height: 48px;
        border-radius: 30px;
    }

    /* النصوص العربية والإنجليزية */
.bio-text {
        max-width: 750px;
        margin: 15px auto 8px;
        padding: 0 10px;
    }
    .bio-text p {
        font-size: 1.05rem;
        line-height: 1.8;
        color: #1f2a3a;
        background: rgba(255,255,255,0.5);
        padding: 18px 24px;
        border-radius: 40px;
        backdrop-filter: blur(2px);
        border: 1px solid rgba(255,255,255,0.8);
        box-shadow: 0 2px 8px rgba(0,0,0,0.02);
        text-align: right;
    }
    .bio-text p:last-of-type {
        text-align: left;
        direction: ltr;
    }
    .bio-text strong {
        color: #1E90FF;
        font-weight: 600;
    }

.profile-gif {
        border-radius: 28px;
        max-width: 100%;
        width: 440px;
        box-shadow: 0 12px 30px rgba(0,0,0,0.12);
        margin-top: 18px;
        border: 2px solid rgba(255,255,255,0.7);
        transition: 0.3s;
    }
    .profile-gif:hover {
        transform: scale(1.01);
        box-shadow: 0 18px 40px rgba(0, 40, 80, 0.18);
    }

    /* شارات */
.badge-group {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 14px 24px;
        margin: 16px 0 6px;
    }
    .badge-group img {
        border-radius: 40px;
        transition: 0.2s;
    }
    .badge-group img:hover {
        transform: scale(1.04);
        opacity: 0.9;
    }

hr {
        border: none;
        border-top: 2px dashed rgba(30, 144, 255, 0.2);
        width: 70%;
        margin: 30px auto;
    }

    /* توافق مع الشاشات الصغيرة */
 @media (max-width: 640px) {
        .card { padding: 25px 16px; }
        h1 { font-size: 2.0rem; }
        h3 { font-size: 1.4rem; }
        .description { font-size: 0.95rem; padding: 14px 18px; }
        .skill-icons img { width: 40px; height: 40px; }
        .social-links img { width: 42px; height: 42px; }
        .bio-text p { font-size: 0.95rem; padding: 14px 16px; }
        .profile-gif { width: 100%; }
    }
</style>
<!-- رأس الصفحة: الاسم مع GIF -->
<div class="text-center">
    <h1>
        👋 مرحبًا، أنا <span>عيسى إبراهيم شايع</span> 
        <span style="display: inline-block; background: #eef5ff; padding: 0 8px; border-radius: 60px; margin-right: 6px;">
            Eissa Ibrahim Shaya
        </span>
        <img src="https://github.com/eissashaya/eissashaya/blob/main/IMG_20240708_031113_033.jpg" 
             alt="profile avatar" 
             style="width: 44px; height: 44px; border-radius: 60px; border: 2px solid #1E90FF; margin-right: 8px; vertical-align: middle;">
    </h1>
    
    <!-- GIF خلفية متحركة (بنفس الرابط) -->
 <img src="https://media.giphy.com/media/26BRuo6sLetdllPAQ/giphy.gif" 
         alt="animated banner" 
         style="width: 100%; max-height: 160px; object-fit: cover; border-radius: 28px; margin: 12px 0 8px; box-shadow: 0 8px 20px rgba(0,0,0,0.06);">
</div>

<!-- الوصف المهني -->
<div class="text-center mt-20">
    <div class="description">
        <i class="fas fa-code"></i> 
        <strong>💻 مبرمج تطبيقات</strong> باستخدام 
        <img src="https://img.icons8.com/color/20/flutter.png" alt="Flutter" style="vertical-align: middle;"> Flutter &nbsp;|&nbsp;
        <img src="https://img.icons8.com/color/20/python.png" alt="Python" style="vertical-align: middle;"> Python &nbsp;|&nbsp;
        <img src="https://img.icons8.com/color/20/dart.png" alt="Dart" style="vertical-align: middle;"> Dart 
        <br>
        <i class="fas fa-globe"></i> 
        <strong>🌐 مصمم مواقع</strong> باستخدام 
        <img src="https://img.icons8.com/color/20/html-5.png" alt="HTML" style="vertical-align: middle;"> HTML, 
        <img src="https://img.icons8.com/color/20/html-5.png" alt="HTML5" style="vertical-align: middle;"> HTML5, 
        <img src="https://img.icons8.com/color/20/css3.png" alt="CSS" style="vertical-align: middle;"> CSS, 
        <img src="https://img.icons8.com/color/20/css3.png" alt="CSS3" style="vertical-align: middle;"> CSS3, 
        <img src="https://img.icons8.com/color/20/javascript.png" alt="JavaScript" style="vertical-align: middle;"> JavaScript, 
        <img src="https://img.icons8.com/color/20/bootstrap.png" alt="Bootstrap" style="vertical-align: middle;"> Bootstrap, 
        <img src="https://img.icons8.com/color/20/php.png" alt="PHP" style="vertical-align: middle;"> PHP 
        <br>
        <i class="fas fa-cogs"></i> 
        <strong>⚙️ مهارات برمجية إضافية:</strong> 
        <img src="https://img.icons8.com/color/20/c-plus-plus-logo.png" alt="C++" style="vertical-align: middle;"> C++ &nbsp;|&nbsp;
        <img src="https://img.icons8.com/color/20/java-coffee-cup-logo.png" alt="Java" style="vertical-align: middle;"> Java
    </div>
</div>

<!-- المهارات التقنية (أيقونات كبيرة) -->
<div class="text-center mt-30">
    <h3>✨ المهارات التقنية ✨</h3>
    <div class="skill-icons">
        <img src="https://img.icons8.com/color/48/flutter.png" alt="Flutter" title="Flutter">
        <img src="https://img.icons8.com/color/48/python.png" alt="Python" title="Python">
        <img src="https://img.icons8.com/color/48/dart.png" alt="Dart" title="Dart">
        <img src="https://img.icons8.com/color/48/html-5.png" alt="HTML" title="HTML">
        <img src="https://img.icons8.com/color/48/css3.png" alt="CSS" title="CSS">
        <img src="https://img.icons8.com/color/48/javascript.png" alt="JavaScript" title="JavaScript">
        <img src="https://img.icons8.com/color/48/bootstrap.png" alt="Bootstrap" title="Bootstrap">
        <img src="https://img.icons8.com/color/48/php.png" alt="PHP" title="PHP">
        <img src="https://img.icons8.com/color/48/firebase.png" alt="Firebase" title="Firebase">
        <img src="https://img.icons8.com/color/48/git.png" alt="Git" title="Git">
        <img src="https://img.icons8.com/color/48/c-plus-plus-logo.png" alt="C++" title="C++">
        <img src="https://img.icons8.com/color/48/java-coffee-cup-logo.png" alt="Java" title="Java">
    </div>
</div>

<div class="separator"></div>

<!-- إحصائيات GitHub -->
<div class="text-center mt-20">
    <h3>📊 إحصائيات GitHub الخاصة بي</h3>
    <div class="stats-grid">
        <img src="https://github-readme-stats.vercel.app/api?username=eissashaya&show_icons=true&theme=radical" 
             alt="GitHub Stats" width="400">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=eissashaya&layout=compact&theme=radical" 
             alt="Top Languages" width="400">
    </div>
</div>

<!-- عدد الزيارات والمتابعين -->
<div class="text-center mt-30">
    <h3>📈 عدد زيارات الصفحة والمتابعين</h3>
    <div class="badge-group">
        <img src="https://komarev.com/ghpvc/?username=eissashaya&style=flat-square&color=blue" alt="Profile Views">
        <img src="https://img.shields.io/github/followers/eissashaya?style=social" alt="Followers">
        <img src="https://img.shields.io/github/stars/eissashaya?style=social" alt="GitHub Stars">
    </div>
</div>

<hr>

<!-- عني (عربي + إنجليزي) -->
<div class="text-center">
    <h3>🧑‍💻 عنّي | About Me</h3>
    <div class="bio-text">
        <p dir="rtl">
            👨‍💻 مبرمج تطبيقات محترف متخصص في 
            <strong>Flutter</strong>، <strong>Python</strong>، <strong>Dart</strong>،
            مع خبرة في تصميم مواقع باستخدام 
            <strong>HTML, CSS, JavaScript, Bootstrap, PHP</strong>.<br><br>
            💼 أعمل باستمرار على تحسين مهاراتي وأبحث عن فرص عمل وتعاون جديدة.<br><br>
            🌟 أحب العمل الحر والمشاريع المتنوعة التي تطور من قدراتي.<br><br>
            🚀 متحمس لتعلم كل جديد في عالم البرمجة وتطوير البرمجيات.
        </p>
        <p dir="ltr" style="text-align: left; direction: ltr; margin-top: 12px;">
            👨‍💻 A professional application developer specialized in 
            <strong>Flutter</strong>, <strong>Python</strong>, <strong>Dart</strong>, 
            with experience in web design using 
            <strong>HTML, CSS, JavaScript, Bootstrap, PHP</strong>.<br><br>
            💼 I am constantly working on improving my skills and looking for new job and collaboration opportunities.<br><br>
            🌟 I enjoy freelancing and diverse projects that enhance my abilities.<br><br>
            🚀 Passionate about learning everything new in the world of programming and software development.
        </p>
    </div>

    <!-- صورة GIF متحركة إضافية -->
 <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" 
         alt="coding animation" 
         class="profile-gif">
</div>

<hr>

<!-- تواصل معي -->
<div class="text-center mt-20">
    <h3>📬 تواصل معي</h3>
    <div class="social-links">
        <a href="https://github.com/eissashaya" title="GitHub"><img src="https://img.icons8.com/fluent/48/000000/github.png" alt="GitHub"></a>
        <a href="https://www.linkedin.com/in/eissa-ibrahim-shaya" title="LinkedIn"><img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn"></a>
        <a href="https://www.facebook.com/profile.php?id=100031199948943&mibextid=JRoKGi" title="Facebook"><img src="https://img.icons8.com/fluent/48/000000/facebook-new.png" alt="Facebook"></a>
        <a href="#" title="Telegram"><img src="https://img.icons8.com/fluent/48/000000/telegram-app.png" alt="Telegram"></a>
        <a href="https://www.instagram.com/v_b.j/?utm_source=qr&r=nametag" title="Instagram"><img src="https://img.icons8.com/fluent/48/000000/instagram-new.png" alt="Instagram"></a>
        <a href="https://wa.me/967776295164" title="WhatsApp"><img src="https://img.icons8.com/fluent/48/000000/whatsapp.png" alt="WhatsApp"></a>
        <a href="mailto:eissa.shaya@example.com" title="Email"><img src="https://img.icons8.com/fluent/48/000000/email.png" alt="Email"></a>
    </div>
    <div style="margin-top: 16px; color: #3a4a5a; font-size: 0.9rem; opacity: 0.7;">
        <i class="fas fa-code"></i> صنع بـ ❤️ بواسطة عيسى إبراهيم شايع
    </div>
</div>
