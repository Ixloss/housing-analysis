# housing-analysis
# Melbourne Housing Data Analysis & Cleaning

Bu loyihada Melburn shahridagi uylarning narxlari va ularga tegishli ma'lumotlar tahlil qilingan hamda pandas kutubxonasi yordamida tozalash (Data Cleaning) ishlari olib borilgan.

## 🚀 Loyiha Haqida

Ma'lumotlar to'plamidagi yetishmayotgan qiymatlar (NaN) bilan ishlash, ma'lumotlarni tahlil qilish va yakuniy natijalarni turli formatlarda saqlash usullari ko'rsatilgan. 

### 🛠 Bajarilgan Amallar (Data Cleaning Steps)
1. Ma'lumotlar o'lchami va strukturasi: len() va .shape yordamida qatorlar soni aniqlandi. .info() va .describe() orqali statistik tahlil qilindi.
2. Missing Values (NaN): Har bir ustundagi NaN qiymatlar soni va ularning umumiy ma'lumotga nisbatan foiz ulushi hisoblab chiqildi.
3. Ustunlarni filtrlash: Eng ko'p NaN qatnashgan ustun (BuildingArea) aniqlanib, undagi bo'sh qatorlar olib tashlandi.
4. Minimal yo'qotish: Eng kam NaN qatnashgan ustun (Car) bo'yicha tozalash o'tkazildi va o'zgarishlar asl df da saqlab qolindi.

## 📦 Saqlangan Fayllar formatlari

Loyiha yakunida tozalangan ma'lumotlar quyidagi formatlarda saqlangan va ushbu repository-ga yuklangan:
* 📄 **melb_data.csv** - Indekslarsiz toza CSV formatdagi ma'lumotlar.
* 💾 **yakuniy_malumotlar.h5** - Tezkor yuklanish va yuqori unumdorlik uchun HDF5 formatida saqlangan ma'lumotlar bazasi.

## 💻 Ishga tushirish (Requirements)

Ushbu loyihani o'z kompyuteringizda ishga tushirish uchun quyidagi kutubxonalar o'rnatilgan bo'lishi kerak:

`bash
pip install pandas tables
