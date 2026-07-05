# 🎵 نغم بوهيمي - Bohemian Music Player

تطبيق موسيقي بوهيمي متكامل بـ HTML/CSS/JS مع 3 صفحات SPA.

## ✨ المميزات

| الميزة | الوصف |
|--------|-------|
| 🎨 **3 صفحات** | اكتشف، المشغل، المكتبة في SPA واحدة |
| 🌓 **Dark/Light** | وضع داكن وفاتح مع حفظ التفضيل |
| 🎚️ **Waveform** | Canvas متحرك بتدرجات بوهيمية |
| 💿 **Vinyl Record** | قرص دوار مع تأثيرات ضوئية |
| 📋 **قائمة تشغيل** | 20 أغنية مع drag-drop وفرز |
| 🔍 **بحث وفلتر** | بحث حي + فرز متعدد |
| ✨ **Glassmorphism** | تصميم زجاجي مع خلفيات blob متحركة |
| 📱 **متجاوب** | يدعم الجوال والتابلت والديسكتوب |

## 🚀 التشغيل

افتح `index.html` في المتصفح مباشرة.

## 🛠️ التقنيات

- HTML5 + CSS3 + Vanilla JavaScript
- Canvas API للـ Waveform
- CSS Variables للـ Theming
- View Transitions API
- Drag & Drop API
- Glassmorphism + Blob Animations
- Google Fonts (Cormorant Garamond + Josefin Sans)

## 📦 النشر على Vercel

```bash
npm install -g vercel
vercel
```

## 🎵 الأغاني التجريبية

استخدم SoundHelix mp3 كأغاني تجريبية حقيقية.

## 📜 الترخيص

MIT - استخدم بحرية ✌️

---

## 🚀 النشر التلقائي على Vercel

### الطريقة 1: Vercel Dashboard (أسهل)

1. اذهب إلى https://vercel.com/new
2. استورد مشروع GitHub: `4zobir89-lab/nagham-bohimi`
3. الإعدادات الافتراضية تعمل مباشرة
4. اضغط **Deploy** 🎉

### الطريقة 2: Vercel CLI

```bash
npm i -g vercel
vercel login
vercel --prod
```

### الطريقة 3: GitHub Actions (تلقائي)

1. اذهب إلى https://vercel.com/account/tokens → أنشئ Token
2. اذهب إلى Settings → Secrets → أضف `VERCEL_TOKEN`
3. ربط المشروع على Vercel وجلب `ORG_ID` و `PROJECT_ID`
4. أضفهم كـ Secrets في GitHub
5. النشر تلقائي مع كل push إلى main 🚀
