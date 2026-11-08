# dekiru_nihongo

# 🇯🇵 Yaponcha → O'zbekcha lug'at · Test · Dokkai platformasi

Yapon tilini o'rganuvchilar va JLPT N2 imtihoniga tayyorlanuvchilar uchun interaktiv lug'at va test platformasi (PWA & Dark Theme).

---

## 🌟 Asosiy imkoniyatlar

- 📚 **5 ta to'liq bo'lim (3376 ta leksika va iboralar):**
  - **できる日本語 (Dekiru Nihongo):** 1190+ so'z (1–15 darslar).
  - **20日で合格N2:** 1028+ so'z (20 kunlik to'liq dastur).
  - **JLPT N1 & IT ビジネス:** 250 ta oliy darajadagi leksika va rasmiy iboralar — 複合動詞 (murakkab fe'llar), 四字熟語 (4-kanji iboralari), IT arxitektura va biznes atamalari, nozik ravishlar (副詞) hamda N1 rasmiy grammatik konstruksiyalari (7 ta ixtisoslashgan bo'lim).
  - **MUST:** 784 ta amaliy va biznes leksikasi, IT/PM terminlari, tizim loyihalash, intervyu va kompaniya shartlari (6 ta kichik bo'lim).
  - **Digital Knowledge & Rasmiy Hujjatlar:** 122 ta maxsus leksika va jonli iboralar — Digital Knowledge kompaniyasi intervyusi, Excel mahorat testi (STDEVP, VLOOKUP, 偏差値), 面接直前チートシート (1 daqiqalik o'zini tanishtirish, 30s 志望動機, kutilmagan vaziyatlar), 成果報告書, エントリーシート (ES), スキルチェックシート va 21 ta savolnoma hujjatlari bo'yicha to'liq yaponcha-o'zbekcha lug'at (8 ta bo'lim).
- 🎯 **面接 (Intervyu) Maxsus Tayyorgarlik Sahifasi:**
  - 21 ta rasmiy anketaviy savol (`質問事項`), ES va texnik suhbatlar uchun mukammal yaponcha javoblar (`模範回答`).
  - 🔊 **Ovozli talaffuz (ja-JP TTS):** Savol va javoblarni toza yaponcha nutq orqali eshitish.
  - 💡 **Suhbat strategiyasi (面接のポイント):** Intervyuerning asl maqsadi va to'g'ri urg'u berish uslubi.
  - 👁️ **Mashq / O'zini sinash rejimi:** Javobni yashirib (blur), mustaqil gapirib ko'rish va tekshirish.
  - 🔑 **Kalit iboralar (Keywords):** Har bir savol bo'yicha professional yaponcha terminlar kartochkalari.
- 🔍 **Tezkor qidiruv va filtrlash:** Kanji, kana (o'qilishi), romaji va o'zbekcha tarjimalar bo'yicha real-vaqtda qidirish.
- 🎴 **Kartochka (Flashcard) rejimi:** So'zlarni yodlash uchun interaktiv fleshkartalar.
- 📝 **Test (Quiz) & Dokkai (読解 · 文章の文法) rejimi:** 
  - 20 kunlik to'liq test dasturi (1180+ savol).
  - 漢字 (Kanji), 語彙 (Lug'at boyligi), 文法 (Grammatika) bo'limlari.
  - 📖 **読解 (Dokkai / 問題9):** 『日本語能力試験 20日で合格N2』kitobidagi barcha 20 kunlik original adabiy va publitsistik matnlar (100 ta savol, 50–54). Rasmiy kalit asosida to'liq tekshirish va har bir savol uchun batafsil o'zbekcha tahliliy izohlar.
  - Har bir savol uchun batafsil izoh va to'g'ri/xato tahlili.
- 🌙 **Dark Theme (Tun rejimi):** Yuqori kontrastli, ko'zga qulay zamonaviy qorong'i dizayn. Tizim rejimiga avtomatik moslashadi yoki toolbar'dagi 🌙/☀️ tugmasi orqali o'zgartiriladi (tanlov brauzerda eslab qolinadi).
- 📲 **PWA (Progressive Web App):** MacBook va telefonlarga mustaqil dastur ko'rinishida o'rnatiladi (Dock yoki Bosh ekranga qo'shiladi).
- ✈️ **100% Oflayn rejim (Zero-dependency):** Service Worker yordamida barcha ma'lumotlar keshlanadi. Internet butunlay o'chiq bo'lganda ham barcha testlarni ishlash, so'zlarni qidirish va o'rganish mumkin.

---

## 📲 MacBook va Telefonga dastur sifatida o'rnatish (PWA)

### 💻 MacBook (Google Chrome & Microsoft Edge):
1. Saytni oching (masalan, `http://localhost:8080/` yoki GitHub Pages).
2. Sayt toolbar'idagi **«O'rnatish»** tugmasini yoki brauzer manzil qatoridagi **⊕ (O'rnatish)** belgisini bosing.
3. Dastur Mac'ingizning **Launchpad** va **Dock** qismida alohida ilova sifatida paydo bo'ladi.

### 🍎 MacBook (Safari — macOS Sonoma 14+):
1. Safari orqali saytni oching.
2. Yuqori menyudan: **Fayl (File)** → **«Dokka qo'shish...» (Add to Dock...)** ni bosing.

### 📱 iPhone / iPad (Safari):
1. Saytni Safari brauzerida oching.
2. Pastdagi **«Ulashish» (Share ⎋)** tugmasini bosing.
3. **«Bosh ekranga qo'shish» (Add to Home Screen)** ni tanlang.

### 🤖 Android (Google Chrome):
1. Chrome menyusidagi (uch nuqta ⋮) **«Ilovani o'rnatish»** yoki **«Bosh ekranga qo'shish»** ni bosing.

---

## 🚀 Ishga tushirish (Local)

Saytni kompyuterda ishga tushirish uchun quyidagi usullardan birini tanlashingiz mumkin:

### 1-usul: Mahalliy server orqali (PWA va Service Worker to'liq ishlashi uchun tavsiya etiladi)
```bash
# Python 3 orqali
python3 -m http.server 8080

# Brauzerda ochish:
# http://localhost:8080/
```

### 2-usul: Oddiy ochish
Fayllar orasidagi `index.html` faylini ikki marta bosib ochish kifoya (Service Worker ishlashi uchun `http://` yoki `https://` protokoli kerak bo'ladi).

---

## 🌐 GitHub Pages orqali Live Demo

Ushbu loyihani GitHub Pages orqali bir necha soniyada online qilish mumkin:
1. Repositoriya sozlamalariga kiring: **Settings** → **Pages**
2. **Branch** bo'limida `main` branchini va `/ (root)` papkasini tanlang
3. **Save** tugmasini bosing
4. Saytingiz quyidagi manzilda ishga tushadi:
   `https://Farhodoff.github.io/dekiru_nihongo/` (HTTPS protokoli sababli PWA va offline funksiyalari avtomatik to'liq faollashadi).

---

## 📂 Fayllar strukturasi

```text
dekiru_nihongo/
├── index.html              # Asosiy veb-platforma (HTML, Dark/Light CSS, JS, lug'at va testlar)
├── manifest.webmanifest   # PWA konfiguratsiya fayli
├── sw.js                  # Service Worker (100% oflayn keshlovchi mexanizm)
├── icons/                 # PWA piktogrammalari (192x192, 512x512, SVG, Apple touch)
├── sozlar-dekiru.csv       # Dekiru Nihongo so'zlar bazasi (CSV)
├── sozlar-n2.csv           # N2 so'zlar bazasi (CSV)
├── sozlar-n1.csv           # N1 & IT biznes so'zlar bazasi (CSV)
├── sozlar-must.csv         # MUST so'zlar bazasi (CSV)
├── sozlar-dk.csv           # Digital Knowledge & IT intervyu so'zlar bazasi (CSV)
├── README.md               # Loyiha qo'llanmasi
└── .gitignore
```
