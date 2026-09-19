# dekiru_nihongo

# 🇯🇵 Yaponcha → O'zbekcha lug'at · Test · Dokkai platformasi

Yapon tilini o'rganuvchilar va JLPT N2 imtihoniga tayyorlanuvchilar uchun interaktiv lug'at va test platformasi.

---

## 🌟 Asosiy imkoniyatlar

- 📚 **2 ta to'liq bo'lim:**
  - **できる日本語 (Dekiru Nihongo):** 1190+ so'z (1–15 darslar).
  - **20日で合格N2:** 1028+ so'z (20 kunlik to'liq dastur).
- 🔍 **Tezkor qidiruv va filtrlash:** Kanji, kana (o'qilishi), romaji va o'zbekcha tarjimalar bo'yicha real-vaqtda qidirish.
- 🎴 **Kartochka (Flashcard) rejimi:** So'zlarni yodlash uchun interaktiv fleshkartalar.
- 📝 **Test (Quiz) rejimi:** 
  - 20 kunlik to'liq test dasturi (1080+ savol).
  - 漢字 (Kanji), 語彙 (Lug'at boyligi), 文法 (Grammatika) va 読解 (Dokkai) bo'limlari.
  - Har bir savol uchun batafsil izoh va to'g'ri/xato tahlili.
- ⚡ **Nol qaramlik (Zero-dependency):** Butun platforma bitta mustaqil `index.html` faylida mujassamlangan bo'lib, offline rejimda ham to'liq ishlaydi.

---

## 🚀 Ishga tushirish (Local)

Saytni kompyuterda ishga tushirish uchun quyidagi usullardan birini tanlashingiz mumkin:

### 1-usul: Oddiy ochish
Fayllar orasidagi `index.html` faylini istalgan brauzerda (Chrome, Safari, Firefox) ikki marta bosib ochish kifoya.

### 2-usul: Mahalliy server orqali
```bash
# Python 3 orqali
python3 -m http.server 8080

# Brauzerda ochish:
# http://localhost:8080/
```

---

## 🌐 GitHub Pages orqali Live Demo

Ushbu loyihani GitHub Pages orqali bir necha soniyada online qilish mumkin:
1. Repositoriya sozlamalariga kiring: **Settings** → **Pages**
2. **Branch** bo'limida `main` branchini va `/ (root)` papkasini tanlang
3. **Save** tugmasini bosing
4. Saytingiz quyidagi manzilda ishga tushadi:
   `https://Farhodoff.github.io/dekiru_nihongo/`

---

## 📂 Fayllar strukturasi

```text
dekiru_nihongo/
├── index.html          # Asosiy veb-platforma (HTML, CSS, JS, barcha ma'lumotlar)
├── sozlar-dekiru.csv   # Dekiru Nihongo so'zlar bazasi (CSV)
├── sozlar-n2.csv       # N2 so'zlar bazasi (CSV)
├── README.md           # Loyiha qo'llanmasi
└── .gitignore
```
