# ক্রিকেট স্কোরার + লাইভ ওভারলে / Cricket Scorer + Live Overlay

লোকাল ক্রিকেট ম্যাচের লাইভ স্কোরিং অ্যাপ। একটা ফোনে স্কোর করুন, Prism Live-এ ওভারলে দেখান।
A live scoring app for local cricket. Score on one phone, show the overlay in Prism Live.

## GitHub Pages-এ পাবলিশ / Publish on GitHub Pages
1. github.com এ নতুন repository খুলুন (Public), যেমন `cricket-scorer`
2. এই ফোল্ডারের সব ফাইল (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-*.png`, `.nojekyll`) আপলোড করুন
3. Settings → Pages → Source: **Deploy from a branch** → Branch: **main**, folder: **/(root)** → Save
4. ১-২ মিনিট পর লিংক পাবেন: `https://<আপনার-username>.github.io/cricket-scorer/`

## Prism Live ওভারলে লিংক / Overlay link
1. firebase.google.com → Realtime Database বানান, Rules এ `".read": true, ".write": true`
2. অ্যাপে "ওভারলে লিংক" কার্ডে Database URL বসিয়ে Save চাপুন
3. **📋 ওভারলে লিংক কপি** চাপুন, লিংকটা Prism Live-এর Web/Browser source-এ বসান

## APK
GitHub Pages লিংকটা pwabuilder.com-এ দিয়ে Android প্যাকেজ (APK/AAB) বানান।
