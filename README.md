# Kompyuter Tarmoqlari — Interaktiv Mobil Ilova (Android APK)

Ushbu repozitoriy "Kompyuter tarmoqlari" fanining 12 ta nazariy, 12 ta amaliy va 8 ta Cisco Packet Tracer laboratoriya mashg'ulotlaridan iborat to'liq interaktiv mobil ilovasini o'z ichiga oladi.

## APK Faylni Avtomatik Yig'ish (GitHub Actions)

1. **GitHub da yangi repozitoriy yarating**:
   - `github.com` saytida **New repository** tugmasini bosing (masalan: `kompyuter-tarmoqlari-app`).
   - Repozitoriy holatini **Public** qilib belgilang.

2. **Fayllarni yuklang**:
   - Ushbu `.zip` arxiv ichidagi barcha fayllarni (ayniqsa `.github/workflows/main.yml`, `package.json`, `capacitor.config.json` va `www/index.html`) repozitoriyingizga yuklang (`git push` yoki veb-interfeys orqali).

3. **APK ni yuklab olish**:
   - Repozitoriyingizdagi **Actions** bo'limiga o'ting.
   - **Build Android APK** jarayoni avtomatik ishga tushadi (taxminan 2-4 daqiqa davom etadi).
   - Jarayon tugagach, **Artifacts** bo'limidan **KompyuterTarmoqlari-APK** faylini yuklab oling va Android telefoningizga o'rnating!
