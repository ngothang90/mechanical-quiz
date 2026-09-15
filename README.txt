MECHANICAL QUIZ V11 – 1,000 QUESTIONS

Important:
- This version intentionally uses questions_1000.json.
- Upload ALL files in this folder to GitHub Pages.
- The old questions.json / questions_530.json / questions_530.csv files are no longer used by the app.
- If those old files remain in GitHub, they do not affect the app because index.html now loads questions_1000.json?v=10.
- If you want a clean repository, delete the old question files after uploading V11.
- Firebase project/config and Firestore Rules are unchanged.

Question bank: 1,000 questions.
Topics:
1. Cơ khí cơ bản, Vật liệu & Bề mặt: 437
2. Đọc bản vẽ cơ khí & Drawing: 44
3. Dung sai kích thước & Tolerance: 103
4. GD&T / Dung sai hình học: 190
5. Gia công CNC, DFM & Process: 58
6. Đo kiểm & Inspection: 34
7. CAD / 3D Modeling & MBD / 3D PDF / PMI: 84
8. Gasbox / Gas System: 50

The app loads questions_1000.json with a cache-busting query parameter.


LƯU Ý FIREBASE: V11 nhúng trực tiếp Firebase Web Config vào index.html để tránh dùng nhầm static/firebase-config.js cũ. Nếu trình duyệt báo auth/api-key-not-valid, hãy kiểm tra Google Cloud Console > APIs & Services > Credentials > API key của Firebase Web app; nếu API key đang bị giới hạn, cho phép Identity Toolkit API và referrer https://ngothang90.github.io/* (hoặc tạm thời bỏ Application restrictions để test).
