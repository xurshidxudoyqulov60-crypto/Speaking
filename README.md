# SpeakFlow — English Speaking, Listening, Reading, Vocabulary & Flashcards

Minimalist va qulay ingliz tili amaliyoti veb-ilovasi. Foydalanuvchilar o'qish tezligini nazorat qilish, eshitish qobiliyatini sinash, yangi so'zlarni o'rganish, flashcards orqali takrorlash hamda xuddi xalqaro imtihonlardek (IELTS / CEFR) matn o'qish va tushunish testlarini topshirishlari mumkin.

---

## 🚀 Asosiy imkoniyatlar

### 1. 🎙️ Speaking (Nutq va O'qish)
- **10 ta mavzu x 3 ta daraja (A1, A2, B1)** — jami 30 ta sifatli matn.
- **Silliq avto-skroll** — o'qish tezligini (px/s) slayder yordamida o'zingizga moslash.
- **Ovozli tayyorgarlik va teskari sanoq** — boshlashdan oldin tabiiy ovoz bilan ogohlantirish.
- **Tinchlantiruvchi Minecraft fon musiqalari** — 6 ta klassik sokin saundtrek (ovozni boshqarish, o'tkazish, o'chirish).

### 2. 🎧 Listening & Quiz (Eshitish va Tushunish)
- **18 yoshli tabiiy qiz ovozi** — Web Speech API asosidagi mayin, ravon ingliz tili talaffuzi (`pitch: 1.20`, `rate: 0.91`).
- **Ovoz tezligi nazorati** — 0.8x, 1.0x va 1.2x.
- **Ovoz tembri (Tone)** — Soft, Natural, Lively.
- **Transkript** — matnni audio bilan birga ko'rish yoki yashirish imkoniyati.
- **Interaktiv testlar** — har bir matn uchun 3 tadan, jami 90 ta savol, tezkor tekshiruv va tushuntirishlar.

### 3. 📚 Reading Exam (Imtihon formatidagi o'qish va tushunish testi)
- **Xalqaro imtihonlar (IELTS / CEFR) formati**:
  - **Paragraflar ko'rsatkichi (`[¶ 1]`)**: Matndagi har bir gapni marker bilan belgilash (Highlight).
  - **Matn shriftini kattalashtirish / kichiklashtirish (`A-` / `A+`)**.
  - **5 daqiqalik imtihon teskari taymeri** (`05:00`), to'xtatish (Pause) va davom ettirish.
- **Haqiqiy imtihon savol turlari**:
  - `Multiple Choice (A, B, C, D)` — faktik va asosiy mazmun savollari.
  - `True / False / Not Given` — IELTS standarti bo'yicha matnga moslikni aniqlash.
  - `Inference & Purpose` — muallif maqsadi va yashirin ma'noni tushunish.
  - `Vocabulary in Context` — so'zlarning kontekstdagi ma'nosini aniqlash.
- **Interaktiv navigatsiya pulti** (`[1] [2] [3]`): Savollar orasida erkin sakrash va belgilangan javoblarni kuzatish.
- **Diagnostik tahlil va natijalar**:
  - CEFR daraja va IELTS ekvivalent balli (masalan, *C1 Mastery IELTS 8.5–9.0*).
  - Har bir savol bo'yicha sizning javobingiz, to'g'ri javob, **Matndagi dalil (Text Evidence)** va o'zbekcha to'liq izoh.

### 4. 📖 Vocabulary (Lug'at va Ro'yxat)
- **180 ta muhim so'z va iboralar** — har bir mavzu va daraja uchun saralangan.
- **Har bir so'z uchun**:
  - So'z turkumi (*noun, verb, adjective, phrase*).
  - Alohida audio talaffuz (🔊 O'qish).
  - O'zbekcha aniq tarjimasi.
  - Misol gap (Example) va uning audio talaffuzi.
  - Misolning o'zbekcha tarjimasi.
- **Flashcard yashirish/ko'rsatish** — yodlashni tekshirish uchun tarjimalarni xiralashtirish (blur / tap-to-reveal).
- **Jonli qidiruv** — so'z yoki tarjimani bir zumda filtrlash.

### 5. 🃏 Flashcards (Kartochkalar orqali takrorlash)
- **Silliq 3D Flip Card** — kartani bosganda yoki Space/Enter tugmasida 3D aylanadi.
- **Old tomon (Front)**: Katta inglizcha so'z, so'z turkumi va avtomatik/alohida audio talaffuz (🔊).
- **Orqa tomon (Back)**: O'zbekcha aniq tarjima, misol gap va uning tarjimasi hamda audio talaffuzi.
- **Xotira va takrorlash nazorati**:
  - `🔄 Qaytarish` — so'zni o'rganishda qoldiradi va qayta takrorlash uchun navbat oxiriga qo'shadi.
  - `✅ Yodladim` — so'zni o'zlashtirilgan deb belgilaydi va hisoblagichga qo'shadi.
- **Progress va Statistika** — jonli progress-bar, jami, yodlangan va o'rganilayotgan kartalar soni.
- **Tasodifiy aralashtirish (🔀 Shuffle)** — kartalarni aralashtirib mashq qilish.
- **Klaviatura orqali qulay boshqaruv** (`Space`, `Enter`, `←`, `→`, `↓`, `↑`).

---

## 🛠️ O'rnatish va Ishga tushirish

1. Reponi yuklab oling yoki klon qiling:
   ```bash
   git clone https://github.com/xurshidxudoyqulov60-crypto/Speaking.git
   cd Speaking
   ```
2. Mahalliy serverda ishga tushirish (Localhost):
   ```bash
   npm start
   # yoki
   node server.js
   ```
3. Brauzerda oching:
   👉 **http://localhost:3000**

---

## 📁 Loyiha tuzilmasi

```text
├── index.html          # Asosiy veb-ilova (Speaking, Listening, Reading, Vocabulary, Flashcards)
├── Speak Up.html       # Zaxira nusxa
├── server.js           # Tezkor zero-dependency localhost HTTP serveri (Audio range qo'llab-quvvatlaydi)
├── package.json        # Loyiha konfiguratsiyasi
├── assets/
│   └── audio/          # Mahalliy Minecraft fon musiqalari (.mp3)
└── README.md           # Loyiha qo'llanmasi
```
