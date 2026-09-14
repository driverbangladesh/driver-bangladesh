# Driver Bangladesh — APK তৈরি

এই প্রজেক্টটি Flutter দিয়ে তৈরি। Android SDK/Flutter স্থানীয়ভাবে না থাকলেও GitHub Actions দিয়ে APK বানানো যাবে।

## ফোন দিয়ে APK বানানোর নিয়ম
1. GitHub-এ একটি নতুন repository তৈরি করুন।
2. এই ZIP-এর সব ফাইল repository-তে Upload files দিয়ে আপলোড করুন।
3. Branch হিসেবে `main` রাখুন।
4. আপলোড শেষ হলে **Actions** ট্যাব খুলুন।
5. `Build Driver Bangladesh APK` workflow নির্বাচন করুন।
6. `Run workflow` চাপুন (অথবা নতুন push হলে এটি নিজে থেকেই চলবে)।
7. কাজ শেষ হলে workflow run-এর নিচে **Artifacts** থেকে `driver-bangladesh-apk` ডাউনলোড করুন।
8. ZIP খুলে `app-release.apk` ফোনে ইনস্টল করুন।

প্রথমবার GitHub-এ আপলোড করার সময় ZIP ফাইলটি নিজে আপলোড না করে ZIP-এর ভেতরের ফাইলগুলো repository-তে আপলোড করতে হবে।
