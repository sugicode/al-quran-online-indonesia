# ✨📖✨ Aplikasi Ngaji Online Indonesia ✨📖✨

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Tahoma&pause=1000&width=435&lines=Yuk+Kita+Murottal+Qur'an)]


📖 “Mendekatkan Al-Qur’an dalam genggaman Anda”

## ✨ Fitur
➡️ Akses Al-Qur’an dimana saja & kapan saja

➡️ Lengkap dengan terjemahan & tafsir

➡️ Fitur pencarian ayat, bookmark, & audio tilawah

## 🔗 API Al-Quran 
Host: `https://api.alquran.cloud/v1/surah`

```
GET audio /ayah/${ayahNumber}/ar.alafasy)
GET surah lengkap & terjemahan surah/${surahNumber}/editions/quran-uthmani,id.indonesian)
```
### 📝 Parameter 
| Language id | Name | Format |
|----------|------|--------------|
| "language": "id", | "name": "Abu Rida", | "format": "text", |


### ✅ Format Response 
```json
{
  "code": 200,
  "status": "OK",
  "data": [
    {
      "number": 1,
      "name": "سُورَةُ ٱلْفَاتِحَةِ",
      "englishName": "Al-Faatiha",
      "englishNameTranslation": "The Opening",
      "numberOfAyahs": 7,
      "revelationType": "Meccan"
    },
    {
      "number": 2,
      "name": "سُورَةُ البَقَرَةِ",
      "englishName": "Al-Baqara",
      "englishNameTranslation": "The Cow",
      "numberOfAyahs": 286,
      "revelationType": "Medinan"
    },
    {
      "number": 3,
      "name": "سُورَةُ آلِ عِمۡرَانَ",
      "englishName": "Aal-i-Imraan",
      "englishNameTranslation": "The Family of Imraan",
      "numberOfAyahs": 200,
      "revelationType": "Medinan"
    },
```

Made with ❤️ by [SugiCode]

