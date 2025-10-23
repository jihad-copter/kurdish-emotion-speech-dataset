# GitHub Pages Setup Guide
# ڕێنمایی دامەزراندنی GitHub Pages

## خێرا و ئاسان: GitHub Pages بۆ ئەپڵیکەیشنی دەنگی کوردی

### 1️⃣ دروستکردنی Repository

1. **بچۆ بۆ GitHub.com**
   - ساین ئین بکە یان ئەکاونتی نوێ دروستبکە

2. **Repository نوێ دروستبکە:**
   ```
   Repository name: kurdish-emotion-speech-dataset
   Description: Kurdish Emotion Speech Dataset Collection App
   Public ✅ (پێویستە بۆ GitHub Pages free)
   Add README file ✅
   ```

3. **Repository دروستبکە**

### 2️⃣ فایلەکان زیادبکە

بەم ڕێگەیە فایلەکان upload بکە:

#### Upload بە Web Interface:
1. لە repository دا، **"Add file" > "Upload files"** کلیک بکە
2. فایلەکان drag & drop بکە:
   - `index.html` (main app file)
   - `README.md`
   - `run_https_server.py` (optional, بۆ local development)

#### یان بە Git Commands:
```bash
git clone https://github.com/YOUR_USERNAME/kurdish-emotion-speech-dataset.git
cd kurdish-emotion-speech-dataset

# فایلەکان copy بکە
cp /path/to/emotion-dataset-app-mobile.html index.html
cp /path/to/README.md .
cp /path/to/run_https_server.py .

# Git دا add بکە
git add .
git commit -m "Add Kurdish emotion speech dataset app"
git push origin main
```

### 3️⃣ GitHub Pages چالاکبکە

1. **بچۆ بۆ Repository Settings**
   - Repository دا → "Settings" tab

2. **Pages بدۆزەرەوە**
   - لە left sidebar دا "Pages" کلیک بکە

3. **Source هەڵبژێرە**
   ```
   Source: Deploy from a branch
   Branch: main / (root)
   ```

4. **Save کلیک بکە**

### 4️⃣ دەسەڵاتی پێدان

دوای چەند خولەک، ئەپڵیکەیشنەکەت لێرە بەردەست دەبێت:
```
https://YOUR_USERNAME.github.io/kurdish-emotion-speech-dataset/
```

## ✅ سوودەکانی GitHub Pages:

### 🔒 **HTTPS خۆکار:**
- هیچ SSL certificate دامەزراندنی پێویست نییە
- خۆکارانە `https://` پێدەدرێت
- هەموو بڕاوزەرەکان trust دەکەن

### 📱 **کاری مۆبایل:**
- مایکڕۆفۆن بە تەواوی کاردەکات
- هیچ "NotAllowedError" نابێت
- لە هەموو مۆبایلەکانەوە دەستگەیشتن

### 🌐 **دەستگەیشتنی گشتی:**
- لە هەر شوێنێکەوە، هەر کاتێک
- لینک ئاسان بۆ هاوبەشکردن
- بەخۆڕایی بۆ هەمیشە

### 🔄 **گونجاندنی ئاسان:**
- فایل نوێبکەرەوە، خۆکارانە deploy دەبێت
- Version control بە Git
- Backup خۆکار

## 📝 نموونەی لینکەکان:

### Demo Sites نموونە:
```
Repository: github.com/username/kurdish-emotion-speech-dataset
Live App: https://username.github.io/kurdish-emotion-speech-dataset/

نموونە:
Repository: github.com/john/kurdish-emotion-speech-dataset  
Live App: https://john.github.io/kurdish-emotion-speech-dataset/
```

### دڵنیایی لە کارکردن:
1. لە کۆمپیوتەرەوە سایتەکە بکەرەوە
2. لە مۆبایلەوە تاقی بکەرەوە
3. مۆڵەتی مایکڕۆفۆن بدە
4. ریکۆرد تاقی بکەرەوە

## 🔧 خوێندنەوەی Git Commands:

### یەکەمجار Setup:
```bash
# Repository clone بکە
git clone https://github.com/YOUR_USERNAME/kurdish-emotion-speech-dataset.git
cd kurdish-emotion-speech-dataset

# فایلی main app زیادبکە
# emotion-dataset-app-mobile.html بە index.html ناو بگۆڕە
cp emotion-dataset-app-mobile.html index.html

# کۆمیت بکە
git add index.html
git commit -m "Add Kurdish emotion speech dataset collection app"
git push origin main
```

### گۆڕانکاری نوێ:
```bash
# گۆڕانکاریەکان زیادبکە
git add .
git commit -m "Update app with new features"
git push origin main

# دوای چەند خولەک لە live site دا دەبینیت
```

## 🎯 ئاکامی کۆتایی:

دوای ئەم هەنگاوانە:
1. ✅ ئەپڵیکەیشنەکەت لە `https://` کاردەکات
2. ✅ مایکڕۆفۆن لە مۆبایل کاردەکات  
3. ✅ هەموو کەسێک دەستگەیشتنی هەیە
4. ✅ بەخۆڕایی hosting
5. ✅ گونجاندنی ئاسان

## 📞 یارمەتی:

ئەگەر کێشەت هەیە:
1. GitHub Pages status چەک بکە لە repository settings
2. Browser cache clear بکە
3. دڵنیابە repository public بێت
4. چەند خولەک چاوەڕێ بکە بۆ deployment
