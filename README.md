# HR Hospital

หน้าเข้าสู่แบบสำรวจสถานพยาบาลประกันสังคมสำหรับพนักงาน รองรับมือถือ แท็บเล็ต และคอมพิวเตอร์

หน้าเว็บนี้มีเพียงลิงก์ไปยัง Google Apps Script ไม่รับหรือเก็บคำตอบบน GitHub ไม่มีฐานข้อมูลพนักงานหรือข้อมูลรับรองใน repository

เว็บไซต์: https://itskb-room.github.io/hrhospital/

## เผยแพร่

GitHub Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save

หากเปลี่ยน deployment URL ของ Apps Script ให้แก้ `href` ของปุ่มใน `index.html` หากอัปเดตโค้ดด้วย deployment เดิม ไม่ต้องเปลี่ยนลิงก์

สิทธิ์เข้าถึงแบบสอบถามและ Google Sheets ต้องกำหนดใน Google แยกต่างหาก การมีหน้า GitHub Pages ไม่ได้เพิ่มการยืนยันตัวตนหรือเปลี่ยนสิทธิ์ Apps Script
