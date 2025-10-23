# کۆکردنەوەی داتاسێتی دەنگی هەستەکان
# Kurdish Emotion Speech Dataset Collection App

ئەپڵیکەیشنێکی وێب بۆ کۆکردنەوەی داتاسێتی دەنگ لە زمانی کوردیدا بۆ ناسینەوەی هەستەکان.

## تایبەتمەندیەکان / Features

### 🎯 ئەرکەکان / Functionality
- ✅ داواکردنی ناوی سیانی بەکارهێنەر
- ✅ هەڵبژاردنی لە ٧ جۆری هەست (دڵخۆشی، خەمۆکی، تووڕەیی، هاوسەنگ، ترس، سەرسوڕمان، بێزاری)
- ✅ ٣ رستەی کوردی بۆ هەر هەستێک
- ✅ ٣ ریکۆرد بۆ هەر رستەیەک
- ✅ سنووری کات: ماکسیمۆم ٥ چرکە بۆ هەر ریکۆرد
- ✅ کۆنترۆڵی گوێگرتن و دووبارەکردنەوە
- ✅ داگرتنی داتا بە فۆرماتی JSON + WAV

### 🎨 دیزاین / Design
- ✅ ڕووکاری جوان و مۆدێرن
- ✅ پشتگیری RTL بۆ کوردی
- ✅ ڕێسپۆنسیڤ بۆ مۆبایل و دێسکتۆپ
- ✅ ئەنیمەیشن و ئەفێکتی جوان

## 🔧 چارەسەری کێشەی مایکڕۆفۆن لە مۆبایلدا

### کێشەکە:
```
Error accessing microphone: NotAllowedError: The request is not allowed by the user agent or the platform in the current context
```

### چارەسەرەکان:

#### 1️⃣ **خێراترین چارەسەر - HTTPS سێرڤەر:**

```bash
# بەکارهێنانی Python HTTPS سێرڤەر
python3 run_https_server.py
```

پاشان بچۆ بۆ:
- لە کۆمپیوتەر: `https://localhost:8443/emotion-dataset-app-mobile.html`
- لە مۆبایل: `https://[YOUR_IP]:8443/emotion-dataset-app-mobile.html`

#### 2️⃣ **هۆستینگی بەخۆڕایی:**

**GitHub Pages:**
1. فایلەکان upload بکە بۆ GitHub repository
2. GitHub Pages چالاک بکە
3. دەسەڵاتی پێدرا: `https://username.github.io/repo-name/`

**Netlify:**
1. بچۆ بۆ [netlify.com](https://netlify.com)
2. فایلەکان drag & drop بکە
3. خۆکارانە HTTPS پێدەدرێت

**Vercel:**
1. بچۆ بۆ [vercel.com](https://vercel.com)
2. پڕۆژەکە deploy بکە
3. خۆکارانە HTTPS پێدەدرێت

#### 3️⃣ **چارەسەری بڕاوزەر:**

**Chrome:**
1. بچۆ بۆ: `chrome://flags/`
2. گەڕان بۆ: `Insecure origins treated as secure`
3. Enable بکە
4. بڕاوزەر restart بکە

**Firefox:**
1. بچۆ بۆ: `about:config`
2. گەڕان بۆ: `media.devices.insecure.enabled`
3. `true` بکە

## 📱 بەکارهێنان لە مۆبایلدا

### 1. دڵنیایی لە HTTPS:
- تەنها لە HTTPS سایتەکان مایکڕۆفۆن کاردەکات
- `http://` کارناکات، پێویستە `https://` بێت

### 2. مۆڵەتی مایکڕۆفۆن:
- کاتێک داوا دەکرێت، "Allow" یان "مۆڵەت" کلیک بکە
- لە Settings ی بڕاوزەر، مۆڵەتی مایکڕۆفۆن بدە

### 3. بڕاوزەری پێشنیارکراو:
- Chrome (Android)
- Safari (iOS)
- Firefox Mobile

## 📁 ساختاری فایلەکان

```
📁 emotion-dataset-app/
├── 📄 emotion-dataset-app.html          # ڤێرژنی بنەڕەتی
├── 📄 emotion-dataset-app-mobile.html   # ڤێرژنی بهێزتر بۆ مۆبایل
├── 🐍 run_https_server.py              # HTTPS سێرڤەر
├── 📄 README.md                        # ڕێنمایی
└── 📁 downloads/                       # شوێنی داگرتنی فایلەکان
    ├── 🎵 participant_emotion_sentence_record.wav
    └── 📄 participant_emotion_metadata.json
```

## 🎤 ڕێنمایی ریکۆردکردن

### بۆ بەکارهێنەران:
1. **ناوی سیانی بنووسە**
2. **هەستێک هەڵبژێرە** لە ٧ هەستەکە
3. **رستەکە بخوێنەوە** بە شێوەیەک کە هەستەکە دەربڕێت
4. **٣ جار ریکۆرد بکە** بۆ هەر رستەیەک
5. **گوێبگرە** و دڵنیابە لە کوالیتی
6. **داتاکان دابگرە** لە کۆتاییدا

### بۆ کۆکەرەوەی داتا:
- هەر ریکۆردێک ناسنامەیەکی یەکجارەکی هەیە
- metadata ی تەواو لە JSON فایلدا پاشەکەوت دەکرێت
- فایلە دەنگیەکان بە فۆرماتی WAV پاشەکەوت دەکرێن
- ڕێکخستنی سیستماتیک بۆ ئەنالیز

## 🛠️ خوراکی تەکنیکی

### پێداویستیەکان:
- بڕاوزەری مۆدێرن بە پشتگیری Web Audio API
- دەسەڵاتی مایکڕۆفۆن
- HTTPS connection (بۆ مۆبایل)
- JavaScript چالاکبووی

### پشتگیری بڕاوزەر:
- ✅ Chrome 65+ (Desktop & Mobile)
- ✅ Firefox 60+ (Desktop & Mobile)
- ✅ Safari 11+ (Desktop & Mobile)
- ✅ Edge 79+
- ❌ Internet Explorer (پشتگیری ناکات)

### تەکنۆلۆژیەکان:
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Audio:** Web Audio API, MediaRecorder API
- **Storage:** Browser localStorage, Blob API
- **UI:** Responsive CSS Grid & Flexbox

## 📊 فۆرماتی داتا

### JSON Metadata:
```json
{
  "participant": "ناوی بەکارهێنەر",
  "emotion": "happy",
  "recordings": [
    {
      "filename": "participant_happy_sentence0_record0.wav",
      "emotion": "happy",
      "sentence": "ڕۆژێکی زۆر زۆر خۆشحاڵە!",
      "sentenceIndex": 0,
      "recordingIndex": 0,
      "timestamp": "2024-01-01T12:00:00.000Z"
    }
  ],
  "metadata": {
    "totalRecordings": 9,
    "timestamp": "2024-01-01T12:00:00.000Z",
    "language": "ku"
  }
}
```

### Audio Files:
- **فۆرمات:** WAV (Web Audio API standard)
- **کوالیتی:** 44.1kHz, Mono
- **مەودا:** ماکسیمۆم ٥ چرکە
- **ناسناندن:** `participant_emotion_sentenceX_recordY.wav`

## 🔒 ئاسایشی داتا

- هیچ داتایەک ناردە سێرڤەر نادرێت
- هەموو پرۆسەکردن لە بڕاوزەردا ڕوودەدات
- بەکارهێنەر کۆنترۆڵی تەواوی لەسەر داتاکانی هەیە
- داگرتنی ڕاستەخۆ بۆ دەستگای بەکارهێنەر

## 🆘 چارەسەری کێشەکان

### کێشەی باو و چارەسەرەکان:

#### "مایکڕۆفۆن ناکات"
```
✅ دڵنیابە لە HTTPS
✅ مۆڵەتی مایکڕۆفۆن بدە
✅ مایکڕۆفۆن تاقی بکەرەوە
```

#### "ریکۆرد پاشەکەوت ناکرێت"
```
✅ بڕاوزەری تازە بەکاربهێنە
✅ Storage ی بڕاوزەر clear بکە
✅ JavaScript چالاک بکە
```

#### "فایل داگیرا ناکرێت"
```
✅ Pop-up blocker disable بکە
✅ Download ی automatic مۆڵەت بدە
✅ بڕاوزەری جیاواز تاقی بکەرەوە
```

#### "دەنگ بەرز نییە"
```
✅ ئاستی دەنگی دەستگا چەک بکە
✅ نزیک لە مایکڕۆفۆن بدوێ
✅ کەلەپەی دەوری کەم بکەرەوە
```

## 📞 پشتگیری

کێشەت هەیە؟ ئەم شوێنانە چەک بکە:

1. **Browser Console:** F12 → Console بۆ error messages
2. **Network Tab:** بۆ چەکردنی HTTPS connection
3. **Application Tab:** بۆ چەکردنی permissions

## 🔄 گونجاندن

ئەپڵیکەیشنەکە ئاسان گۆڕانی لێدەکرێت:

### زیادکردنی هەستی نوێ:
```javascript
const emotions = {
    // هەستەکانی پێشووتر...
    newEmotion: {
        name: 'ناوی هەست',
        sentences: [
            'رستەی یەک',
            'رستەی دوو',
            'رستەی سێ'
        ]
    }
};
```

### گۆڕینی رستەکان:
لە ناو ئۆبجێکتی `emotions` رستەکان بگۆڕە.

### گۆڕینی دیزاین:
CSS ی ناو `<style>` تاگ گۆڕە.

## 📄 مۆڵەتنامە

ئەم پڕۆژەیە بە مەبەستی خوێندن و توێژینەوە دروستکراوە.
بەکارهێنان و گۆڕینی بەخۆڕایی مۆڵەتی هەیە.

---

**پێشنیار:** بۆ بەرهەمی باشتر، ئەپڵیکەیشنەکە لە سایتێکی HTTPS host بکە.
