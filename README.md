# Single-port panel (VLESS / Trojan over WebSocket)

یک پنل تک‌پورتی برای هاست‌های رایگان Node.js (Pterodactyl). بدون هیچ وابستگی npm.

## راه‌اندازی
1. یک سرور **Node.js** بساز (Node 18 یا بالاتر، ترجیحاً 20).
2. در **File Manager** این‌ها را آپلود کن: `index.js`، `package.json`، `package-lock.json` و پوشه‌ی `assets/`.
3. فایل استارت: `index.js` (دستور استارت: `node index.js`).
4. سرور را Start کن. پورت از `SERVER_PORT` خوانده می‌شود؛ لازم نیست تنظیمش کنی.
5. آدرس `http://<server-ip>:<port>/panel` را باز کن (برای وارد کردن رمز بهتر است `https://` را بزنی و هشدار گواهی خودامضا را تایید کنی) و رمز پنل را بساز.
