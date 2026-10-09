# MaktabTolovDemo

Jetpack Compose asosidagi Android demo ilova. Haqiqiy backend, SMS va Payme talab qilmaydi.

## Sinov imkoniyatlari
- Demo rejimida telefon raqami bilan kirish (SMS-kod yuborilmaydi).
- Namunaviy o‘quvchilar ro‘yxati.
- Demo to‘lov va demo chek yaratish.
- Chekni ulashish va to‘lovlar tarixini ko‘rish.
- Kirish holati va cheklarni qurilmaning SharedPreferences xotirasida saqlash.

## Android Studio’da ishga tushirish
1. ZIP arxivni oching.
2. Android Studio’da `MaktabTolovDemo` papkasini **Open** qiling.
3. Gradle sync tugashini kuting.
4. JDK 17 tanlanganini tekshiring.
5. Android SDK Platform 35 o‘rnatilgan bo‘lsin (yoki SDK Manager orqali o‘rnating).
6. Emulator yoki Android telefon tanlab, **Run** tugmasini bosing.
7. Telefon maydoniga masalan `+998901234567` kiriting va **Demo rejimida kirish** ni bosing.

## APK yig‘ish
Android Studio: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
APK odatda `app/build/outputs/apk/debug/app-debug.apk` manzilida yaratiladi.

## Muhim xavfsizlik/mahsulot eslatmasi
Bu faqat namoyish uchun. O‘quvchi ma’lumotlari namunaviy, SMS tasdiqlash yo‘q, backend yo‘q, Payme yo‘q va haqiqiy pul yechilmaydi. Ishlab chiqarish uchun autentifikatsiya, maktab bazasi, backend orqali buyurtma va serverdan tekshiriladigan Payme callbacklari, maxfiy kalitlarni serverda saqlash, maxfiylik siyosati va audit zarur.
