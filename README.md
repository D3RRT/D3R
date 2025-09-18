<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>D3R | ذعـر</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    .section {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
  </style>
</head>
<body class="bg-gradient-to-br from-purple-700 to-purple-900 text-white">  <!-- ترحيب -->  <section id="welcome" class="section text-center p-6">
    <h1 class="text-5xl font-extrabold mb-6" id="typed"></h1>
  </section>  <!-- ديسكورد -->  <section id="discord" class="section text-center p-6">
    <h2 class="text-4xl font-bold mb-6">🚀 سيرفر ديسكورد الرسمي</h2>
    <a href="https://discord.gg/kqzyxRHf" target="_blank" class="bg-purple-600 text-2xl px-8 py-4 rounded-2xl shadow-lg hover:bg-purple-500 transition">D3R COMMUNITY</a>
    <p class="mt-6 text-2xl">حياكم الله تلاقو فيه كل شيء وهو اهم شيء للمصممين: صور، لقطات، كليبات وحسابات شباب الغرب والعصابات</p>
  </section>  <!-- تواصل اجتماعي -->  <section id="socials" class="section text-center p-6 grid grid-cols-1 gap-6 max-w-md mx-auto">
    <a href="https://www.tiktok.com/@d3r_rt?_t=ZS-8zp3zK6nFa6&_r=1" target="_blank" class="flex items-center justify-between bg-white text-black p-6 rounded-2xl shadow-lg hover:scale-105 transition">
      <span class="text-2xl font-bold">TikTok</span><i class="fab fa-tiktok text-4xl"></i>
    </a>
    <a href="https://x.com/D3R_1RT?t=w6xly6PrGMkbIIAOecRLAg&s=09" target="_blank" class="flex items-center justify-between bg-black text-white p-6 rounded-2xl shadow-lg hover:scale-105 transition">
      <span class="text-2xl font-bold">X (Twitter)</span><i class="fab fa-twitter text-4xl"></i>
    </a>
    <a href="https://youtube.com/@d3r_rt?si=0C77T-nLQEuI9H7I" target="_blank" class="flex items-center justify-between bg-red-600 text-white p-6 rounded-2xl shadow-lg hover:scale-105 transition">
      <span class="text-2xl font-bold">YouTube</span><i class="fab fa-youtube text-4xl"></i>
    </a>
    <a href="https://www.snapchat.com/add/d3r_1rt?share_id=kXMC33Ov7UM&locale=ar-DZ-u-nu-latn" target="_blank" class="flex items-center justify-between bg-yellow-400 text-black p-6 rounded-2xl shadow-lg hover:scale-105 transition">
      <span class="text-2xl font-bold">Snapchat</span><i class="fab fa-snapchat-ghost text-4xl"></i>
    </a>
    <a href="https://www.instagram.com/d3r.rt1?igsh=bXR4YXp1eGtlemlk" target="_blank" class="flex items-center justify-between bg-pink-600 text-white p-6 rounded-2xl shadow-lg hover:scale-105 transition">
      <span class="text-2xl font-bold">Instagram</span><i class="fab fa-instagram text-4xl"></i>
    </a>
  </section>  <!-- تلغرام -->  <section id="telegram" class="section text-center p-6">
    <h2 class="text-3xl font-bold mb-4">📢 مجتمع تلقرام</h2>
    <a href="https://t.me/+rxN6redgNdpiMjFk" target="_blank" class="bg-blue-500 text-2xl px-8 py-4 rounded-2xl shadow-lg hover:bg-blue-400 transition">ادخل هنا</a>
    <p class="mt-4 text-2xl">فيه لقطات وصور واحداث - حياكم الله</p>
  </section>  <!-- عني -->  <section id="about" class="section text-center p-6">
    <p class="text-3xl">أنا <span class="font-bold">مصمم رسبكت</span> عندي اكثر من <span class="text-yellow-300 font-bold">10,000 متابع</span> في تيك توك 🎥</p>
    <p class="mt-4 text-3xl">هدفي اصير <span class="text-green-300 font-bold">ستريمر في رسبكت</span> على كيك 🎮 واسمي هناك <span class="font-bold">D3R_1</span></p>
  </section>  <!-- النهاية -->  <section id="end" class="section text-center p-6">
    <p class="text-3xl">شكرا لزيارتكم 💜 أتمنى دخولكم لسيرفري في ديسكورد لأنه بيفيد المصممين جدا</p>
    <p class="mt-4 text-3xl">إلى لقاء 👋</p>
    <p class="mt-8 text-lg">حقوقي: <span class="font-bold">ذعـر | D3R</span></p>
  </section>  <!-- زر الصعود والهبوط -->  <div class="fixed bottom-6 right-6 flex flex-col space-y-4">
    <a href="#welcome" class="bg-purple-600 p-4 rounded-full shadow-lg hover:bg-purple-500 transition">⬆️</a>
    <a href="#end" class="bg-purple-600 p-4 rounded-full shadow-lg hover:bg-purple-500 transition">⬇️</a>
  </div>  <script>
    document.addEventListener("DOMContentLoaded", function() {
      var typed = new Typed("#typed", {
        strings: ["✨ مرحبا 👋", "✨ مرحبا بكم في موقع رسمي ل D3R | ذعـر", "✨ جميع مواقع التواصل الاجتماعي هنا"],
        typeSpeed: 80,
        backSpeed: 40,
        backDelay: 1000,
        loop: true
      });
    });
  </script></body>
</html>
