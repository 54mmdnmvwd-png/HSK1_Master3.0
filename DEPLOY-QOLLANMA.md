# HSK Master v3.0 — Deploy qo'llanmasi
*Ro'zmatova Sabrina Ashurmatovna 老师*

---

## 🔧 Kerakli narsalar (barchasi bepul)

| Narsa | Manzil | Narx |
|-------|--------|------|
| GitHub hisob | github.com | Bepul |
| Vercel hisob | vercel.com | Bepul |
| Node.js | nodejs.org | Bepul |

---

## 📁 1-QADAM — Loyihani tayyorlash

Kompyuterda yangi papka oching va fayllarni joylashtiring:

```
hsk-master/
├── src/
│   ├── App.jsx        ← hsk-master.jsx ni bu nom bilan saqlang
│   └── index.js       ← Quyidan copy qiling
├── public/
│   ├── index.html     ← Quyidan copy qiling
│   └── manifest.json  ← Quyidan copy qiling
└── package.json       ← Quyidan copy qiling
```

### src/index.js
```js
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';
ReactDOM.createRoot(document.getElementById('root')).render(<App />);
```

### public/index.html
```html
<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1"/>
  <meta name="theme-color" content="#0a0a1a"/>
  <meta name="apple-mobile-web-app-capable" content="yes"/>
  <meta name="apple-mobile-web-app-title" content="HSK Master"/>
  <link rel="manifest" href="/manifest.json"/>
  <title>HSK Master v3.0</title>
  <style>
    *{margin:0;padding:0;box-sizing:border-box}
    body{background:#0a0a1a;overflow-x:hidden}
  </style>
</head>
<body>
  <div id="root"></div>
</body>
</html>
```

### public/manifest.json
```json
{
  "short_name": "HSK Master",
  "name": "HSK Master — Xitoy tili v3.0",
  "icons": [
    {"src":"/icon-192.png","sizes":"192x192","type":"image/png"},
    {"src":"/icon-512.png","sizes":"512x512","type":"image/png"}
  ],
  "start_url": "/",
  "display": "standalone",
  "theme_color": "#0a0a1a",
  "background_color": "#0a0a1a"
}
```

### package.json
```json
{
  "name": "hsk-master",
  "version": "3.0.0",
  "private": true,
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build"
  },
  "browserslist": {
    "production": [">0.2%","not dead"],
    "development": ["last 1 chrome version"]
  }
}
```

---

## 🐙 2-QADAM — GitHub ga yuklash

**Terminal (CMD yoki PowerShell) oching:**

```bash
cd hsk-master
git init
git add .
git commit -m "HSK Master v3.0 initial"
```

**GitHub.com da:**
1. github.com ga kiring
2. "New repository" → nom: `hsk-master` → "Create repository"
3. Ko'rsatilgan buyruqlarni terminalda bajaring:

```bash
git remote add origin https://github.com/SIZNING_USERNAME/hsk-master.git
git branch -M main
git push -u origin main
```

✅ GitHub da fayllaringiz ko'rinadi.

---

## 🚀 3-QADAM — Vercel ga deploy

1. **vercel.com** ga kiring
2. "Continue with GitHub" — GitHub hisobingiz bilan kiring
3. **"New Project"** tugmasini bosing
4. `hsk-master` reponi ko'rasiz → **"Import"** bosing
5. Sozlamalarni o'zgartirmasdan **"Deploy"** bosing
6. ⏳ 2-3 daqiqa kutasiz...
7. ✅ **"Congratulations!"** — saytingiz tayyor!

**Manzil:** `hsk-master.vercel.app` (yoki shunga o'xshash)

---

## 📱 4-QADAM — Telefondan ishlatish

### Android (Chrome)
1. Chrome bilan `hsk-master.vercel.app` oching
2. Yuqori o'ng burchakdagi **⋮** menyuni bosing
3. **"Bosh ekranga qo'shish"** ni bosing
4. Tasdiqlang → Ilova bosh ekranda paydo bo'ladi ✅

### iPhone (Safari)
1. Safari bilan oching
2. Pastdagi **□↑ Share** tugmasini bosing
3. **"Add to Home Screen"** ni bosing
4. ✅

---

## 🌐 5-QADAM — O'z domain (ixtiyoriy)

`.uz` domain sotib olish: **nreg.uz** yoki **ismoil.uz**

Vercel da ulash:
1. Vercel → Project → **Settings** → **Domains**
2. `hskmaster.uz` kiriting → **Add**
3. DNS sozlamalar ko'rsatiladi — domain registratorida kiritasiz

---

## 👩‍🏫 FOUNDER KIRISHI

Login ekranida pastdagi **✦** belgisini bosing:
- PIN: **`sabrina2025`**
- Barcha 15 dars ochiq
- Email/parol shart emas

---

## 🔒 HIMOYA (allaqachon qo'yilgan)

- ❌ Nusxa olish (Ctrl+C) bloklangan
- ❌ O'ng klik bloklangan
- ❌ Matnni tanlash bloklangan
- ❌ F12 / DevTools bloklangan
- ❌ Ctrl+U (manba ko'rish) bloklangan

---

## 📊 XARAJATLAR

| Xizmat | Narx |
|--------|------|
| GitHub | Bepul |
| Vercel (hobby) | Bepul |
| Domain .uz | ~$10/yil |
| **Jami** | **Bepul** (domain olmasa) |

---

*HSK Master v3.0 — 15 dars · 321 so'z · 77 grammatika*
