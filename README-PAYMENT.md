# راهنمای خرید درون برنامه — بازی پنج‌خان

این راهنما مخصوص فعال کردن مرحلهٔ پنجم بازی است.

## ۱. شناسه محصول
- نام محصول: Level 5
- Product ID: `panjkhan.level5`

## ۲. Expo / React Native
- نصب:
  ```bash
  npm install
  expo install expo-in-app-purchases
  npm install @react-native-async-storage/async-storage
  ```
- استفاده:
  - کد نمونه `InAppPurchaseExample.js` را در پروژه قرار دهید.
  - متن فارسی نمایش خرید:
    > «با حمایت کوچک شما از سازنده و ترویج فرهنگ کهن ایران، بازی ادامه می‌یابد — از همراهی‌تان سپاسگزاریم.»

- تست:
  - Expo Go سریع برای تست روی گوشی
  - بعد از خرید موفق، مرحلهٔ پنجم باز می‌شود.