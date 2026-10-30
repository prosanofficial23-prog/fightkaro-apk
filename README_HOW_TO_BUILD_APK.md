# 🎮 FightKaro - Sansad Showdown (Official APK Project Package)

Yeh package aapki website **https://fightkaro.com/** ko 100% professional native Android Game APK me compile karne ke liye taiyar kiya gaya hai. Isme status bar, navigation bar aur browser UI completely hidden hai (Immersive Sticky Mode), hardware acceleration 60FPS ke liye enabled hai, aur touch lag zero hai!

---

## 🚀 Option 1: 1-Click Instant WebAPK (Bina Kisi Software Ke, 5 Seconds Me)
Agar aapko apne phone me bina computer ke instant APK install karni hai:
1. Apne Android phone me Google Chrome ya Brave browser kholein.
2. Link open karein: `https://fightkaro.com/`
3. Browser menu (3 dots) par tap karein -> **"Install App"** ya **"Add to Home Screen"** chunein.
4. Android isko background me direct **WebAPK** me convert kar deta hai jo phone ke App Drawer me real game app ki tarah dikhai deti hai!

---

## 💻 Option 2: Android Studio se Direct .APK File Banayein (Recommended for Play Store / Direct Distribution)
1. Is zip file ko apne computer me extract (unzip) karein.
2. **Android Studio** open karein -> **Open an Existing Project** par click karein aur is folder ko select karein.
3. Gradle sync complete hone ke baad:
   - Menu bar me jayein: **Build** -> **Build Bundle(s) / APK(s)** -> **Build APK(s)**
4. 2 minute me aapka `app-debug.apk` file taiyar ho jayega!
5. Path: `app/build/outputs/apk/debug/app-debug.apk`

---

## ⚡ Option 3: Terminal / Command Line (1 Command Build)
Agar aapke paas Mac/Linux/Windows me Gradle installed hai:
```bash
cd FightKaro
./gradlew assembleRelease
```

---

## ☁️ Option 4: Free Cloud Build (GitHub Actions)
Is project ko apne GitHub account me push kar dijiye.
Isme `.github/workflows/build-apk.yml` file pehle se configured hai.
GitHub automatically cloud me aapke liye APK build karke "Artifacts" section me download link de dega!

Enjoy the game! 🥊🔥
