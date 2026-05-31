<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع ضحى لعد ساعات الدراسة</title>
    <style>
        /* المتغيرات الأساسية للمظهر الافتراضي (الوردي) */
        :root {
            --bg-gradient: linear-gradient(135deg, #ffe5ec, #f0fff4);
            --container-bg: rgba(255, 255, 255, 0.9);
            --header-bg: rgba(255, 255, 255, 0.8);
            --sidebar-bg: #ffffff;
            --primary-color: #ff85a2;
            --soft-color: #fbb1bd;
            --light-color: #ffe5ec;
            --dark-purple: #6c5ce7;
            --text-color: #4a4a4a;
            --white: #ffffff;
            --border-color: rgba(255, 255, 255, 0.5);
        }

        /* الأنماط الأخرى المضافة مسبقاً */
        [data-theme="dark"] {
            --bg-gradient: linear-gradient(135deg, #1e1e2f, #11111b);
            --container-bg: rgba(30, 30, 46, 0.95);
            --header-bg: rgba(22, 22, 37, 0.8);
            --sidebar-bg: #1e1e2f;
            --primary-color: #bb86fc;
            --soft-color: #9965df;
            --light-color: #372948;
            --dark-purple: #e1b1ff;
            --text-color: #f5f5f5;
            --white: #161625;
            --border-color: rgba(255, 255, 255, 0.1);
        }
        [data-theme="blue"] {
            --bg-gradient: linear-gradient(135deg, #e0f2fe, #f0fdf4);
            --container-bg: rgba(255, 255, 255, 0.9);
            --header-bg: rgba(255, 255, 255, 0.8);
            --sidebar-bg: #ffffff;
            --primary-color: #38bdf8;
            --soft-color: #7dd3fc;
            --light-color: #e0f2fe;
            --dark-purple: #0369a1;
            --text-color: #334155;
            --white: #ffffff;
            --border-color: rgba(56, 189, 248, 0.2);
        }
        [data-theme="white-minimal"] {
            --bg-gradient: linear-gradient(135deg, #f8fafc, #f1f5f9);
            --container-bg: #ffffff;
            --header-bg: #ffffff;
            --sidebar-bg: #ffffff;
            --primary-color: #64748b;
            --soft-color: #94a3b8;
            --light-color: #f1f5f9;
            --dark-purple: #0f172a;
            --text-color: #334155;
            --white: #ffffff;
            --border-color: #e2e8f0;
        }
        [data-theme="lavender"] {
            --bg-gradient: linear-gradient(135deg, #ebdcf9, #f1f5f9);
            --container-bg: rgba(255, 255, 255, 0.9);
            --header-bg: rgba(255, 255, 255, 0.8);
            --sidebar-bg: #ffffff;
            --primary-color: #b19ffb;
            --soft-color: #d6bfff;
            --light-color: #f3e8ff;
            --dark-purple: #5b21b6;
            --text-color: #4c1d95;
            --white: #ffffff;
            --border-color: rgba(177, 159, 251, 0.2);
        }
        [data-theme="peach"] {
            --bg-gradient: linear-gradient(135deg, #ffedd5, #fee2e2);
            --container-bg: rgba(255, 255, 255, 0.9);
            --header-bg: rgba(255, 255, 255, 0.8);
            --sidebar-bg: #ffffff;
            --primary-color: #fb923c;
            --soft-color: #fdba74;
            --light-color: #ffedd5;
            --dark-purple: #9a3412;
            --text-color: #431407;
            --white: #ffffff;
            --border-color: rgba(251, 146, 60, 0.2);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: background 0.3s, color 0.3s, border-color 0.3s;
        }

        body {
            background: var(--bg-gradient);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            color: var(--text-color);
            position: relative;
            overflow-x: hidden;
        }

        header {
            width: 100%;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: var(--header-bg);
            backdrop-filter: blur(5px);
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            z-index: 10;
        }

        header h1 {
            color: var(--primary-color);
            font-size: 24px;
        }

        .menu-btn {
            background: none;
            border: none;
            cursor: pointer;
            display: flex;
            flex-direction: column;
            gap: 6px;
            z-index: 1001;
            padding: 5px;
        }

        .menu-btn span {
            display: block;
            width: 30px;
            height: 3px;
            background-color: var(--primary-color);
            border-radius: 3px;
        }

        .sidebar {
            position: fixed;
            top: 0;
            right: -320px;
            width: 320px;
            height: 100%;
            background-color: var(--sidebar-bg);
            box-shadow: -5px 0 15px rgba(0,0,0,0.1);
            transition: 0.4s ease;
            z-index: 1000;
            padding: 80px 15px 20px 15px;
            display: flex;
            flex-direction: column;
            gap: 12px;
            overflow-y: auto;
            border-top-left-radius: 20px;
            border-bottom-left-radius: 20px;
        }

        .sidebar.open { right: 0; }

        .sidebar-nav-btn {
            background-color: var(--light-color);
            color: var(--dark-purple);
            padding: 14px;
            font-size: 15px;
            font-weight: bold;
            border: 1px solid var(--soft-color);
            border-radius: 12px;
            cursor: pointer;
            text-align: right;
        }

        .sidebar-nav-btn:hover {
            background-color: var(--soft-color);
            transform: scale(1.02);
            transition: 0.2s;
        }

        .history-title-section {
            color: var(--dark-purple);
            font-size: 17px;
            font-weight: bold;
            border-bottom: 2px solid var(--light-color);
            padding-bottom: 6px;
            margin-top: 10px;
        }

        .history-list {
            list-style: none;
            max-height: 220px;
            overflow-y: auto;
        }

        .history-list li {
            background-color: var(--light-color);
            padding: 10px;
            border-radius: 10px;
            margin-bottom: 8px;
            font-size: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: var(--text-color);
        }

        .history-info { display: flex; flex-direction: column; gap: 4px; }
        .history-subject { font-weight: bold; color: var(--dark-purple); }

        .delete-btn {
            background: none;
            border: none;
            color: #e03131;
            cursor: pointer;
            font-size: 15px;
            padding: 3px;
        }

        /* تصميم كرت هالو كيتي وأنيميشن الطفو والتحرك المستمر والتفاعل */
        .hellokitty-container {
            margin: 15px 0 5px 0;
            cursor: pointer;
            display: inline-block;
        }

        .hellokitty-img {
            width: 75px;
            height: auto;
            user-select: none;
        }

        /* --- إعدادات وتوزيع شخصيات هالو كيتي الـ 10 الكثيرة والمتناسقة --- */
        .kitty-decoration {
            position: fixed;
            width: 55px;
            height: auto;
            cursor: pointer;
            z-index: 5;
            user-select: none;
        }

        /* تأثير مرور الفأرة (Mouse-over) الفريد والمميز لكل الشخصيات */
        .kitty-decoration:hover {
            transform: scale(1.25) rotate(12deg) !important;
            transition: transform 0.2s ease-in-out;
            filter: drop-shadow(0 5px 10px rgba(255, 133, 162, 0.5));
        }

        /* أنيميشن طفو محسن، ناعم ودائري لمنع الالتصاق والملل البصري */
        @keyframes kittyFloat1 { 0%, 100% { transform: translateY(0) translateX(0); } 50% { transform: translateY(-15px) translateX(6px); } }
        @keyframes kittyFloat2 { 0%, 100% { transform: translateY(0) translateX(0); } 50% { transform: translateY(12px) translateX(-8px); } }
        @keyframes kittyFloat3 { 0%, 100% { transform: translateY(0) translateX(0); } 50% { transform: translateY(-10px) translateX(-6px); } }
        @keyframes kittyFloat4 { 0%, 100% { transform: translateY(0) translateX(0); } 50% { transform: translateY(14px) translateX(5px); } }

        /* توزيع مدروس بـ النسبة المئوية لتغطية الشاشة بالكامل بدون تداخل */
        .k1  { top: 12%; right: 4%;  animation: kittyFloat1 4.5s ease-in-out infinite; }
        .k2  { top: 32%; left: 3%;   animation: kittyFloat2 5s ease-in-out infinite; }
        .k3  { bottom: 10%; right: 5%; animation: kittyFloat3 4s ease-in-out infinite; }
        .k4  { bottom: 35%; left: 4%;  animation: kittyFloat4 5.5s ease-in-out infinite; }
        .k5  { top: 52%; right: 3%;  animation: kittyFloat2 4.2s ease-in-out infinite; }
        .k6  { top: 15%; left: 6%;   animation: kittyFloat1 4.8s ease-in-out infinite; }
        .k7  { bottom: 58%; left: 2%;  animation: kittyFloat3 5.2s ease-in-out infinite; }
        .k8  { top: 72%; right: 4%;  animation: kittyFloat4 4.6s ease-in-out infinite; }
        .k9  { bottom: 3%; left: 14%;  animation: kittyFloat1 4s ease-in-out infinite; }
        .k10 { bottom: 2%; right: 16%; animation: kittyFloat3 4.7s ease-in-out infinite; }

        /* أنيميشن القفز والدوران الممتع عند الضغط المباشر */
        @keyframes kittyJump {
            0% { transform: translateY(0) rotate(0deg) scale(1); }
            30% { transform: translateY(-35px) rotate(-20deg) scale(1.2); }
            60% { transform: translateY(-15px) rotate(360deg) scale(1.1); }
            100% { transform: translateY(0) rotate(360deg) scale(1); }
        }

        .kitty-active {
            animation: kittyJump 0.75s cubic-bezier(0.25, 1, 0.5, 1) !important;
        }

        /* واجهات العرض الكاملة */
        .full-page-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: var(--sidebar-bg);
            z-index: 2000;
            display: flex;
            flex-direction: column;
            padding: 30px;
            transform: translateY(100%);
            transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1);
            overflow-y: auto;
        }

        .full-page-overlay.show { transform: translateY(0); }
        .overlay-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid var(--light-color);
            padding-bottom: 15px;
            margin-bottom: 25px;
        }
        .overlay-header h2 { color: var(--dark-purple); font-size: 22px; }
        .close-overlay-btn {
            background: var(--light-color);
            border: none;
            color: var(--dark-purple);
            font-size: 20px;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            cursor: pointer;
            display: flex; justify-content: center; align-items: center;
        }

        /* كروت الإحصائيات وبطاقات البيانات */
        .stats-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-bottom: 25px;
        }
        .stat-card {
            background-color: var(--light-color);
            padding: 15px;
            border-radius: 15px;
            text-align: center;
            border: 1px solid var(--soft-color);
        }
        .stat-card h4 { color: var(--dark-purple); font-size: 15px; margin-bottom: 5px; }
        .stat-card p { font-size: 22px; font-weight: bold; color: var(--primary-color); }

        .monthly-subjects-list {
            list-style: none;
            background-color: var(--light-color);
            padding: 15px;
            border-radius: 15px;
        }
        .monthly-subjects-list li {
            padding: 8px 0;
            border-bottom: 1px dashed var(--soft-color);
            font-weight: bold;
            display: flex;
            justify-content: space-between;
        }
        .monthly-subjects-list li:last-child { border-bottom: none; }

        .themes-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(130px, 1fr));
            gap: 15px;
        }
        .theme-card {
            padding: 20px; border-radius: 15px; cursor: pointer; text-align: center; font-weight: bold; font-size: 14px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);
        }
        .theme-card.active { border: 3px solid var(--dark-purple); }

        /* الحاوية الرئيسية للمؤقت */
        .container {
            background-color: var(--container-bg);
            padding: 25px;
            border-radius: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.04);
            width: 90%;
            max-width: 450px;
            text-align: center;
            margin-top: 15px;
            border: 2px solid var(--border-color);
            z-index: 10;
        }

        .subject-container { margin-bottom: 15px; text-align: right; }
        .subject-container label { display: block; font-size: 13px; color: var(--dark-purple); font-weight: bold; margin-bottom: 6px; }
        .subject-input { width: 100%; padding: 10px; border: 2px solid var(--soft-color); background-color: var(--sidebar-bg); color: var(--text-color); border-radius: 12px; font-size: 14px; outline: none; }

        .tabs { display: flex; background-color: var(--light-color); border-radius: 15px; padding: 4px; margin-bottom: 20px; }
        .tab-btn { flex: 1; padding: 10px; border: none; background: none; font-weight: bold; color: var(--primary-color); cursor: pointer; border-radius: 10px; }
        .tab-btn.active { background-color: var(--primary-color); color: var(--white); }

        .display { font-size: 46px; font-weight: bold; color: var(--dark-purple); margin: 15px 0; font-family: monospace; letter-spacing: 2px; }

        .inputs-container { display: flex; justify-content: center; gap: 10px; margin-bottom: 15px; }
        .input-group { display: flex; flex-direction: column; align-items: center; }
        .input-group label { font-size: 11px; color: var(--text-color); opacity: 0.7; margin-bottom: 4px; }
        .input-group input { width: 65px; padding: 8px; border: 2px solid var(--soft-color); background-color: var(--sidebar-bg); color: var(--text-color); border-radius: 10px; text-align: center; font-size: 14px; outline: none; }

        .controls { display: flex; justify-content: center; gap: 12px; margin-top: 15px; }
        .btn { padding: 12px 25px; border: none; border-radius: 15px; font-size: 15px; font-weight: bold; cursor: pointer; box-shadow: 0 4px 10px rgba(0,0,0,0.05); transition: transform 0.1s; }
        .btn:active { transform: scale(0.95); }

        .btn-start { background-color: #8ce99a; color: #2b8a3e; }
        .btn-pause { background-color: #ffe066; color: #fcc419; display: none; }
        .btn-stop { background-color: #ffa8a8; color: #e03131; }

        /* حاوية التسجيل اليدوي المنسي */
        .manual-log-container {
            margin-top: 25px;
            padding-top: 15px;
            border-top: 2px dashed var(--light-color);
            text-align: right;
        }
        .manual-log-title { font-size: 13px; color: var(--dark-purple); font-weight: bold; margin-bottom: 10px; display: block;}
        .manual-inputs { display: flex; gap: 8px; align-items: center; margin-bottom: 10px; }
        .manual-inputs input[type="text"] { flex: 2; padding: 8px; border: 2px solid var(--soft-color); background-color: var(--sidebar-bg); color: var(--text-color); border-radius: 10px; font-size: 13px; outline: none; }
        .manual-inputs input[type="number"] { flex: 1; padding: 8px; border: 2px solid var(--soft-color); background-color: var(--sidebar-bg); color: var(--text-color); border-radius: 10px; font-size: 13px; text-align: center; outline: none; }
        .btn-manual-save { width: 100%; padding: 8px; background-color: var(--primary-color); color: white; border: none; border-radius: 10px; font-weight: bold; cursor: pointer; font-size: 13px; }

        .toast-notification { position: fixed; bottom: -100px; left: 50%; transform: translateX(-50%); background-color: var(--primary-color); color: white; padding: 15px 30px; border-radius: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); transition: 0.5s ease; z-index: 3000; font-weight: bold; }
        .toast-notification.show { bottom: 30px; }
    
/* === FIXES ADDED === */
/* منع خروج العناصر خارج الشاشة وتحسين الاستجابة */
html,body{max-width:100%;overflow-x:hidden;}
img{max-width:100%;height:auto;}
.container,.sidebar,.full-page-overlay{max-width:100%;}
@media (max-width:768px){
 .container{width:95%;padding:18px;}
 .display{font-size:34px;}
 .controls,.manual-inputs,.inputs-container{flex-wrap:wrap;}
 .sidebar{width:min(90vw,320px);}
 .kitty-decoration{width:38px;opacity:.75;}
}
/* إصلاح الوضع الداكن */
[data-theme="dark"] .btn-start{color:#fff;}
[data-theme="dark"] .btn-stop{color:#fff;}
[data-theme="dark"] .btn-pause{color:#111;}
[data-theme="dark"] input,
[data-theme="dark"] .subject-input{
 background:#22243a!important;
 color:#fff!important;
}
/* إصلاح مشكلة Hello Kitty */
.kitty-decoration{
 object-fit:contain;
 image-rendering:auto;
}



/* تصغير الصندوق الرئيسي قليلاً */
.container{
    max-width:400px !important;
}

/* توزيع ديناميكي لهالو كيتي حسب حجم الشاشة */
.kitty-decoration{
    width:clamp(32px,4vw,55px);
}

@media (max-width:768px){
    .kitty-decoration:nth-child(n+7){
        display:none;
    }
}

@media (max-width:480px){
    .kitty-decoration:nth-child(n+5){
        display:none;
    }
}


/* ===== تحسين ظهور Hello Kitty في الوضع الليلي ===== */
.kitty-decoration,
.hellokitty-img{
 opacity:1;
 object-fit:contain;
}

[data-theme="dark"] .kitty-decoration,
[data-theme="dark"] .hellokitty-img{
 opacity:1 !important;
 filter:drop-shadow(0 0 8px rgba(255,255,255,.9))
        drop-shadow(0 0 15px rgba(255,182,193,.7));
}


/* إصلاح حقول التسجيل اليدوي على الهواتف */
.manual-inputs {
    display:flex;
    flex-wrap:wrap;
    gap:8px;
    margin-bottom:10px;
}

.manual-inputs input[type="text"]{
    flex:2 1 220px;
}

.manual-inputs input[type="number"]{
    flex:1 1 100px;
}

@media (max-width:480px){

    .manual-inputs{
        display:grid !important;
        grid-template-columns:1fr 1fr;
        gap:8px;
    }

    #manualSubject{
        grid-column:1 / -1;
    }

    .manual-inputs input[type="number"]{
        width:100%;
    }
}

</style>
</head>
<body>

    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k1" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k2" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k3" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k4" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k5" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k6" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k7" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k8" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k9" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">
    <img src="https://img.icons8.com/color/144/hello-kitty.png" class="kitty-decoration k10" alt="Hello Kitty Decor" onclick="animateDecorationKitty(this)">

    <header>
        <h1>موقع ضحى للدراسة ✨</h1>
        <button class="menu-btn" onclick="toggleSidebar()" aria-label="القائمة">
            <span></span><span></span><span></span>
        </button>
    </header>

    <div class="sidebar" id="sidebar">
        <button class="sidebar-nav-btn" onclick="openOverlay('statsOverlay')">📊 تقرير وإحصائيات الدراسة</button>
        <button class="sidebar-nav-btn" onclick="openOverlay('settingsOverlay')">⚙️ إعدادات الموقع</button>
        <button class="sidebar-nav-btn" onclick="openOverlay('aboutOverlay')">🌸 حول الموقع</button>

        <div class="history-title-section">📜 سجل ساعات الدراسة</div>
        <ul class="history-list" id="historyList"></ul>
    </div>

    <div class="full-page-overlay" id="statsOverlay">
        <div class="overlay-header">
            <h2>📊 بيانات وإحصائيات إنجازكِ</h2>
            <button class="close-overlay-btn" onclick="closeOverlay('statsOverlay')">✕</button>
        </div>
        <div class="overlay-body">
            <div class="stats-container">
                <div class="stat-card">
                    <h4>قريتي اليوم ⏱️</h4>
                    <p id="statsToday">0 ساعة</p>
                </div>
                <div class="stat-card">
                    <h4>قريتي هذا الأسبوع 📅</h4>
                    <p id="statsWeek">0 ساعة</p>
                </div>
                <div class="stat-card">
                    <h4>قريتي هذا الشهر 🌙</h4>
                    <p id="statsMonth">0 ساعة</p>
                </div>
            </div>
            
            <h3 style="color: var(--dark-purple); margin-bottom: 10px;">📚 المواد اللي قريتيهم هذا الشهر بالظبط:</h3>
            <ul class="monthly-subjects-list" id="monthlySubjectsList"></ul>
        </div>
    </div>

    <div class="full-page-overlay" id="settingsOverlay">
        <div class="overlay-header">
            <h2>⚙️ إعدادات الموقع والتخصيص</h2>
            <button class="close-overlay-btn" onclick="closeOverlay('settingsOverlay')">✕</button>
        </div>
        <div class="overlay-body">
            <h3 style="margin-bottom: 15px; color: var(--dark-purple);">✨ اختاري شكل وألوان موقعكِ المفضل:</h3>
            <div class="themes-grid">
                <div class="theme-card theme-pink" id="theme-default" onclick="setTheme('default')">الوردي اللطيف</div>
                <div class="theme-card theme-dark" id="theme-dark" onclick="setTheme('dark')">الوضع الداكن 🌙</div>
                <div class="theme-card theme-blue" id="theme-blue" onclick="setTheme('blue')">الأزرق الهادئ</div>
                <div class="theme-card theme-white" id="theme-white-minimal" onclick="setTheme('white-minimal')">الأبيض النقي</div>
                <div class="theme-card theme-lavender" id="theme-lavender" onclick="setTheme('lavender')">الخزامى ✨</div>
                <div class="theme-card theme-peach" id="theme-peach" onclick="setTheme('peach')">الخوخ اللطيف</div>
            </div>
        </div>
    </div>

    <div class="full-page-overlay" id="aboutOverlay">
        <div class="overlay-header">
            <h2>🌸 حول الموقع</h2>
            <button class="close-overlay-btn" onclick="closeOverlay('aboutOverlay')">✕</button>
        </div>
        <div class="overlay-body" style="text-align: center;">
            <h3 style="color: var(--primary-color); margin-bottom: 20px; font-size: 22px;">موقع ضحى لعد ساعات الدراسة 📖 ✨</h3>
            <p>هو مساحتكِ اللطيفة والخاصة المصممة خصيصاً لتنظيم أوقات دراستكِ بكل ذكاء وسهولة وعرض تقارير دورية كاملة.</p>
        </div>
    </div>

    <div class="container">
        <div class="hellokitty-container" onclick="animateKitty()">
            <img src="https://img.icons8.com/color/144/hello-kitty.png" class="hellokitty-img" alt="Hello Kitty" id="kittyImg">
        </div>

        <div class="subject-container">
            <label for="subjectInput">📝 شني بتقري بالظبط توة?</label>
            <input type="text" id="subjectInput" class="subject-input" placeholder="مثال: رياضيات، إنجليزي، فيزياء...">
        </div>

        <div class="tabs">
            <button class="tab-btn active" id="tabNormal" onclick="switchMode('normal')">عداد عادي</button>
            <button class="tab-btn" id="tabCountdown" onclick="switchMode('countdown')">عداد عكسي</button>
        </div>

        <div class="inputs-container" id="inputsContainer" style="display: none;">
            <div class="input-group"><label>ساعات</label><input type="number" id="inputHours" min="0" max="23" placeholder="ساعات"></div>
            <div class="input-group"><label>دقائق</label><input type="number" id="inputMinutes" min="0" max="59" placeholder="دقائق"></div>
            <div class="input-group"><label>ثواني</label><input type="number" id="inputSeconds" min="0" max="59" placeholder="ثواني"></div>
        </div>

        <div class="display" id="display">00:00:00</div>

        <div class="controls">
            <button class="btn btn-start" id="btnStart" onclick="startTimer()">ابدأ</button>
            <button class="btn btn-pause" id="btnPause" onclick="pauseTimer()">توقف مؤقت</button>
            <button class="btn btn-stop" id="btnStop" onclick="stopTimer()">إنهاء وحفظ</button>
        </div>

        <div class="manual-log-container">
            <span class="manual-log-title">🕒 نسيتي تسجلي وقت قريتيه؟ ضيفيه هنا يدوياً:</span>
            <div class="manual-inputs">
                <input type="text" id="manualSubject" placeholder="المادة المنسية...">
                <input type="number" id="manualHours" placeholder="ساعة" min="0">
                <input type="number" id="manualMinutes" placeholder="دقيقة" min="0" max="59">
            </div>
            <button class="btn-manual-save" onclick="saveManualLog()">تسجيل يدوي فوراً</button>
        </div>
    </div>

    <div class="toast-notification" id="toast">🔔 اقترب الوقت من النهاية! همّي يا بطلة!</div>

    <script>
        let mode = 'normal';
        let timerInterval = null;
        let totalSeconds = 0;
        let isRunning = false;
        let warned = false;
        let initialCountdownSeconds = 0;

        const display = document.getElementById('display');
        const btnStart = document.getElementById('btnStart');
        const btnPause = document.getElementById('btnPause');
        const inputsContainer = document.getElementById('inputsContainer');
        const historyList = document.getElementById('historyList');
        const toast = document.getElementById('toast');
        const subjectInput = document.getElementById('subjectInput');

        document.addEventListener('DOMContentLoaded', () => {
            loadHistory();
            calculateStats();
            const savedTheme = localStorage.getItem('studyTheme') || 'default';
            setTheme(savedTheme);
        });

        function toggleSidebar() { document.getElementById('sidebar').classList.toggle('open'); }
        function openOverlay(id) { document.getElementById(id).classList.add('show'); toggleSidebar(); }
        function closeOverlay(id) { document.getElementById(id).classList.remove('show'); }

        // حركة أنيميشن هالو كيتي الرئيسية عند الضغط
        function animateKitty() {
            const kitty = document.getElementById('kittyImg');
            kitty.classList.add('kitty-active');
            setTimeout(() => { kitty.classList.remove('kitty-active'); }, 750);
        }

        // حركة أنيميشن مميزة لهالو كيتي الزينة عند الضغط عليها
        function animateDecorationKitty(element) {
            element.classList.add('kitty-active');
            setTimeout(() => { element.classList.remove('kitty-active'); }, 750);
        }

        function setTheme(themeName) {
            if (themeName === 'default') document.body.removeAttribute('data-theme');
            else document.body.setAttribute('data-theme', themeName);
            localStorage.setItem('studyTheme', themeName);
            document.querySelectorAll('.theme-card').forEach(card => card.classList.remove('active'));
            const activeCard = document.getElementById(`theme-${themeName}`);
            if (activeCard) activeCard.classList.add('active');
        }

        function switchMode(selectedMode) {
            if (isRunning) { alert("يرجى إنهاء الجلسة الحالية أولاً قبل تغيير النمط!"); return; }
            mode = selectedMode;
            resetVariables();
            if (mode === 'normal') {
                document.getElementById('tabNormal').classList.add('active');
                document.getElementById('tabCountdown').classList.remove('active');
                inputsContainer.style.display = 'none';
                display.textContent = "00:00:00";
            } else {
                document.getElementById('tabCountdown').classList.add('active');
                document.getElementById('tabNormal').classList.remove('active');
                inputsContainer.style.display = 'flex';
                updateDisplayFromInputs();
            }
        }

        function updateDisplayFromInputs() {
            let h = parseInt(document.getElementById('inputHours').value) || 0;
            let m = parseInt(document.getElementById('inputMinutes').value) || 0;
            let s = parseInt(document.getElementById('inputSeconds').value) || 0;
            totalSeconds = (h * 3600) + (m * 60) + s;
            initialCountdownSeconds = totalSeconds;
            formatAndDisplay();
        }

        document.querySelectorAll('.input-group input').forEach(input => {
            input.addEventListener('input', () => { if (mode === 'countdown' && !isRunning) updateDisplayFromInputs(); });
        });

        function formatAndDisplay() {
            let hrs = Math.floor(totalSeconds / 3600);
            let mins = Math.floor((totalSeconds % 3600) / 60);
            let secs = totalSeconds % 60;
            display.textContent = (hrs < 10 ? "0" : "") + hrs + ":" + (mins < 10 ? "0" : "") + mins + ":" + (secs < 10 ? "0" : "") + secs;
        }

        function startTimer() {
            if (isRunning) return;
            if (mode === 'countdown' && timerInterval === null) {
                updateDisplayFromInputs();
                if (totalSeconds <= 0) { alert("الرجاء تحديد وقت أكبر من الصفر!"); return; }
            }
            isRunning = true;
            btnStart.style.display = 'none';
            btnPause.style.display = 'block';

            timerInterval = setInterval(() => {
                if (mode === 'normal') {
                    totalSeconds++;
                    formatAndDisplay();
                } else {
                    if (totalSeconds > 0) {
                        totalSeconds--;
                        formatAndDisplay();
                        if (totalSeconds <= 10 && totalSeconds > 0 && !warned) { showToast(); warned = true; }
                    } else {
                        clearInterval(timerInterval);
                        playSweetChime();
                        alert("🎉 مبروك يا ضحى! انتهى وقت الدراسة المحدّد بنجاح!");
                        let currentSubject = subjectInput.value.trim() || "مادة عامة";
                        saveSession(currentSubject, initialCountdownSeconds);
                        resetVariables();
                    }
                }
            }, 1000);
        }

        function pauseTimer() {
            clearInterval(timerInterval);
            isRunning = false;
            btnStart.style.display = 'block';
            btnPause.style.display = 'none';
        }

        function stopTimer() {
            if (mode === 'normal' && totalSeconds === 0) { resetVariables(); return; }

            clearInterval(timerInterval);
            let currentSubject = subjectInput.value.trim() || "مادة عامة";
            
            if (mode === 'normal') {
                saveSession(currentSubject, totalSeconds);
            } else {
                saveSession(currentSubject, initialCountdownSeconds);
            }

            resetVariables();
            if (mode === 'countdown') updateDisplayFromInputs();
            subjectInput.value = "";
        }

        function saveManualLog() {
            let mSub = document.getElementById('manualSubject').value.trim() || "مادة عامة";
            let mHrs = parseInt(document.getElementById('manualHours').value) || 0;
            let mMins = parseInt(document.getElementById('manualMinutes').value) || 0;
            let calculatedSeconds = (mHrs * 3600) + (mMins * 60);

            if (calculatedSeconds <= 0) { alert("الرجاء إدخال وقت صحيح لحفظ الحصة المنسية!"); return; }

            saveSession(mSub, calculatedSeconds);
            
            document.getElementById('manualSubject').value = "";
            document.getElementById('manualHours').value = "";
            document.getElementById('manualMinutes').value = "";
            alert("✨ تم تسجيل الحصة المنسية بنجاح وإضافتها للإحصائيات!");
        }

        function resetVariables() {
            clearInterval(timerInterval);
            timerInterval = null;
            isRunning = false;
            totalSeconds = 0;
            warned = false;
            btnStart.style.display = 'block';
            btnPause.style.display = 'none';
            if (mode === 'normal') display.textContent = "00:00:00";
        }

        function saveSession(subject, durationInSeconds) {
            if (durationInSeconds <= 0) return;

            const now = new Date();
            const timeLabel = now.toLocaleTimeString('ar', {
                hour: 'numeric',
                minute: '2-digit',
                hour12: true
            });
            
            const sessionData = {
                id: Date.now().toString(),
                subject: subject,
                seconds: durationInSeconds,
                date: now.toISOString(),
                timeStr: timeLabel
            };

            let history = JSON.parse(localStorage.getItem('studyHistory')) || [];
            history.push(sessionData);
            localStorage.setItem('studyHistory', JSON.stringify(history));

            renderHistoryItem(sessionData);
            calculateStats();
        }

        function calculateStats() {
            let history = JSON.parse(localStorage.getItem('studyHistory')) || [];
            const now = new Date();

            let todaySecs = 0, weekSecs = 0, monthSecs = 0;
            let monthlySubjects = {};

            const startOfToday = new Date(now.getFullYear(), now.getMonth(), now.getDate());
            const startOfWeek = new Date(now);
            startOfWeek.setDate(now.getDate() - now.getDay());
            startOfWeek.setHours(0,0,0,0);
            const startOfMonth = new Date(now.getFullYear(), now.getMonth(), 1);

            history.forEach(item => {
                const itemDate = new Date(item.date);
                if(isNaN(itemDate.getTime())) return;

                if (itemDate >= startOfToday) todaySecs += item.seconds;
                if (itemDate >= startOfWeek) weekSecs += item.seconds;
                if (itemDate >= startOfMonth) {
                    monthSecs += item.seconds;
                    if (monthlySubjects[item.subject]) {
                        monthlySubjects[item.subject] += item.seconds;
                    } else {
                        monthlySubjects[item.subject] = item.seconds;
                    }
                }
            });

            document.getElementById('statsToday').textContent = formatHoursText(todaySecs);
            document.getElementById('statsWeek').textContent = formatHoursText(weekSecs);
            document.getElementById('statsMonth').textContent = formatHoursText(monthSecs);

            const monthlyListHTML = document.getElementById('monthlySubjectsList');
            monthlyListHTML.innerHTML = "";
            const subjectsKeys = Object.keys(monthlySubjects);
            if (subjectsKeys.length === 0) {
                monthlyListHTML.innerHTML = "<li style='font-size:13px; color:#999; border:none;'>لا توجد مواد مسجلة لهذا الشهر بعد.</li>";
            } else {
                subjectsKeys.forEach(sub => {
                    const li = document.createElement('li');
                    li.innerHTML = `<span>📚 ${sub}</span> <span>${formatHoursText(monthlySubjects[sub])}</span>`;
                    monthlyListHTML.appendChild(li);
                });
            }
        }

        function formatHoursText(totalSecs) {
            let hrs = Math.floor(totalSecs / 3600);
            let mins = Math.floor((totalSecs % 3600) / 60);
            if (hrs === 0 && mins === 0) return "0 دقيقة";
            return `${hrs} ساعة و ${mins} دقيقة`;
        }

        function loadHistory() {
            historyList.innerHTML = "";
            let history = JSON.parse(localStorage.getItem('studyHistory')) || [];
            history.forEach(session => renderHistoryItem(session));
        }

        function renderHistoryItem(session) {
            const li = document.createElement('li');
            li.setAttribute('data-id', session.id);
            let h = Math.floor(session.seconds / 3600);
            let m = Math.floor((session.seconds % 3600) / 60);
            let durationStr = `${h}س:${m}د`;

            li.innerHTML = `
                <div class="history-info">
                    <span class="history-subject">📚 ${session.subject}</span>
                    <span style="font-size: 11px; opacity: 0.8;">⏱️ ${durationStr} | الحصة ${session.timeStr}</span>
                </div>
                <button class="delete-btn" onclick="deleteHistoryItem('${session.id}')" title="حذف">🗑️</button>
            `;
            historyList.appendChild(li);
        }

        function deleteHistoryItem(id) {
            if(confirm("هل أنتِ متأكدة من حذف هذا السجل؟")) {
                let history = JSON.parse(localStorage.getItem('studyHistory')) || [];
                history = history.filter(item => item.id !== id);
                localStorage.setItem('studyHistory', JSON.stringify(history));
                const itemToRemove = historyList.querySelector(`[data-id="${id}"]`);
                if(itemToRemove) itemToRemove.remove();
                calculateStats();
            }
        }

        function showToast() { toast.classList.add('show'); setTimeout(() => { toast.classList.remove('show'); }, 4000); }

        function playSweetChime() {
            const context = new (window.AudioContext || window.webkitAudioContext)();
            let osc1 = context.createOscillator(); let gain1 = context.createGain();
            osc1.type = 'sine'; osc1.frequency.setValueAtTime(523.25, context.currentTime);
            gain1.gain.setValueAtTime(0.3, context.currentTime); gain1.gain.exponentialRampToValueAtTime(0.01, context.currentTime + 0.4);
            osc1.connect(gain1); gain1.connect(context.destination); osc1.start(); osc1.stop(context.currentTime + 0.4);
            setTimeout(() => {
                let osc2 = context.createOscillator(); let gain2 = context.createGain();
                osc2.type = 'sine'; osc2.frequency.setValueAtTime(659.25, context.currentTime);
                gain2.gain.setValueAtTime(0.3, context.currentTime); gain2.gain.exponentialRampToValueAtTime(0.01, context.currentTime + 0.6);
                osc2.connect(gain2); gain2.connect(context.destination); osc2.start(); osc2.stop(context.currentTime + 0.6);
            }, 150);
        }
    
// === FIXES ADDED ===
// تحسين الأداء: إيقاف بعض الزينة على الشاشات الصغيرة
document.addEventListener('DOMContentLoaded',()=>{
 if(window.innerWidth<480){
   document.querySelectorAll('.kitty-decoration').forEach((e,i)=>{
      if(i>4) e.style.display='none';
   });
 }
});

// حماية من الصور المعطوبة التي تظهر كنقاط/أشكال
document.querySelectorAll('.kitty-decoration,.hellokitty-img').forEach(img=>{
 img.addEventListener('error',()=>{
   img.style.display='none';
 });
});


/* منع تداخل شخصيات هالو كيتي */
function repositionKitties(){
 const kitties=document.querySelectorAll('.kitty-decoration');
 const positions=[
 ['8%','5%'],['25%','3%'],['45%','6%'],['65%','4%'],['82%','8%'],
 ['12%','85%'],['32%','88%'],['55%','84%'],['75%','87%'],['90%','80%']
 ];
 kitties.forEach((k,i)=>{
   k.style.top=positions[i][0];
   k.style.left=positions[i][1];
   k.style.right='auto';
   k.style.bottom='auto';
 });
}
window.addEventListener('load',repositionKitties);
window.addEventListener('resize',repositionKitties);

</script>
</body>
</html>
