<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>D3R | ذعـر</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body class="bg-gradient-to-br from-purple-700 to-purple-900 text-white min-h-screen flex flex-col items-center justify-center text-center p-6">  <h1 id="welcome" class="text-3xl md:text-5xl font-bold mb-6"></h1>  <div id="discord" class="hidden mt-6">
    <h2 class="text-2xl font-semibold mb-2">سيرفر ديسكورد الرسمي</h2>
    <a href="https://discord.gg/kqzyxRHf" target="_blank" class="bg-purple-600 px-6 py-3 rounded-2xl shadow-lg hover:bg-purple-500 transition">D3R COMMUNITY</a>
    <p class="mt-3 text-lg">حياكم الله تلاقو فيه كل شيء وهو اهم شيء للمصممين: صور، لقطات، كليبات وحسابات شباب الغرب والعصابات</p>
  </div>  <div id="socials" class="hidden mt-10 space-y-4">
    <a href="https://www.tiktok.com/@d3r_rt?_t=ZS-8zp3zK6nFa6&_r=1" target="_blank" class="flex items-center justify-center space-x-2 bg-white text-black p-3 rounded-2xl shadow-lg hover:scale-105 transition">
      <i class="fab fa-tiktok text-2xl"></i><span>TikTok</span>
    </a>
    <a href="https://x.com/D3R_1RT?t=w6xly6PrGMkbIIAOecRLAg&s=09" target="_blank" class="flex items-center justify-center space-x-2 bg-black text-white p-3 rounded-2xl shadow-lg hover:scale-105 transition">
      <i class="fab fa-twitter text-2xl"></i><span>X (Twitter)</span>
    </a>
    <a href="https://youtube.com/@d3r_rt?si=0C77T-nLQEuI9H7I" target="_blank" class="flex items-center justify-center space-x-2 bg-red-600 text-white p-3 rounded-2xl shadow-lg hover:scale-105 transition">
      <i class="fab fa-youtube text-2xl"></i><span>YouTube</span>
    </a>
    <a href="https://www.snapchat.com/add/d3r_1rt?share_id=kXMC33Ov7UM&locale=ar-DZ-u-nu-latn" target="_blank" class="flex items-center justify-center space-x-2 bg-yellow-400 text-black p-3 rounded-2xl shadow-lg hover:scale-105 transition">
      <i class="fab fa-snapchat-ghost text-2xl"></i><span>Snapchat</span>
    </a>
    <a href="https://www.instagram.com/d3r.rt1?igsh=bXR4YXp1eGtlemlk" target="_blank" class="flex items-center justify-center space-x-2 bg-pink-600 text-white p-3 rounded-2xl shadow-lg hover:scale-105 transition">
      <i class="fab fa-instagram text-2xl"></i><span>Instagram</span>
    </a>
  </div>  <div id="telegram" class="hidden mt-10">
    <h2 class="text-xl font-semibold mb-2">مجتمع تلقرام</h2>
    <a href="https://t.me/+rxN6redgNdpiMjFk" target="_blank" class="bg-blue-500 px-6 py-3 rounded-2xl shadow-lg hover:bg-blue-400 transition">ادخل هنا</a>
    <p class="mt-2">فيه لقطات وصور واحداث - حياكم الله</p>
  </div>  <div id="about" class="hidden mt-10 text-lg">
    <p>أنا <span class="font-bold">مصمم رسبكت</span> عندي اكثر من <span class="text-yellow-300">10,000 متابع</span> في تيك توك 🎥</p>
    <p>هدفي اصير <span class="text-green-300">ستريمر في رسبكت</span> على كيك 🎮 واسمي هناك <span class="font-bold">D3R_1</span></p>
  </div>  <div id="end" class="hidden mt-10">
    <p class="text-lg">شكرا لزيارتكم 💜 أتمنى دخولكم لسيرفري في ديسكورد لأنه بيفيد المصممين جدا</p>
    <p class="mt-2">إلى لقاء 👋</p>
    <a href="#welcome" class="mt-4 inline-block bg-purple-700 px-4 py-2 rounded-lg shadow hover:bg-purple-600 transition">🔝 العودة للأعلى</a>
    <p class="mt-6 text-sm">حقوقي: <span class="font-bold">ذعـر | D3R</span></p>
  </div>  <script>
    document.addEventListener("DOMContentLoaded", function() {
      var typed = new Typed("#welcome", {
        strings: ["مرحبا 👋", "مرحبا بكم في موقع رسمي ل D3R | ذعـر", "جميع مواقع التواصل الاجتماعي هنا"],
        typeSpeed: 70,
        backSpeed: 40,
        backDelay: 1500,
        loop: false,
        onComplete: function() {
          document.getElementById("discord").classList.remove("hidden");
          setTimeout(() => document.getElementById("socials").classList.remove("hidden"), 1500);
          setTimeout(() => document.getElementById("telegram").classList.remove("hidden"), 3000);
          setTimeout(() => document.getElementById("about").classList.remove("hidden"), 4500);
          setTimeout(() => document.getElementById("end").classList.remove("hidden"), 6000);
        }
      });
    });
  </script></body>
</html>
