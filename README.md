# 92 Club Android App

WebView app — Railway site ko Android app me open karta hai.

## Setup (sirf ek baar)

1. `app/src/main/res/values/strings.xml` me apni Railway URL daalo:
   ```xml
   <string name="site_url">https://TUMHARI-URL.up.railway.app</string>
   ```

2. Ye saari files **public GitHub repo** me push karo.

3. GitHub → **Actions** tab → "Build 92 Club APK" → **Run workflow**
   - Ya seedha `main` branch me koi bhi file change karo — APK automatically build hogi!

4. APK **Releases** me milegi naam se: `92club.apk`
   Direct download link:
   ```
   https://github.com/USERNAME/REPO/releases/latest/download/92club.apk
   ```

5. Ye link Railway Variable `APK_URL` me daalo (agar app me download button chahiye).

## Auto-build kab hota hai?
- Har baar jab `main` branch me **koi bhi file push** hoti hai
- Ya manually Actions > Run workflow se
