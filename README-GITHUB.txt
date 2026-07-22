วิธีนำเว็บไซต์ขึ้น GitHub Pages
===============================

1. สร้าง Repository ใหม่ใน GitHub
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์ GitHub-Coaching-Web ไปไว้ที่หน้าหลักของ Repository
   สำคัญ: ต้องอัปโหลดครบทุกไฟล์ และต้องมีไฟล์ index.html อยู่ที่หน้าหลัก
3. เปิดหน้า Settings ของ Repository
4. เลือก Pages
5. ในหัวข้อ Build and deployment เลือก Source: Deploy from a branch
6. เลือก Branch: main และ Folder: / (root)
7. กด Save แล้วรอประมาณ 1–3 นาที
8. GitHub จะแสดงลิงก์เว็บไซต์ในหน้า Pages

ไฟล์ที่ต้องมี
-------------
index.html
coaching-easy-100.html
coaching-classic.html
feedback-practice.html
questions.js
questions-extra.js
feedback-scenarios.js

ข้อควรระวัง
-----------
- ห้ามเปลี่ยนชื่อไฟล์ เพราะหน้าเว็บเชื่อมโยงกันด้วยชื่อเหล่านี้
- GitHub แยกตัวอักษรพิมพ์เล็กและพิมพ์ใหญ่
- หากแก้ไฟล์แล้วหน้าเว็บยังเหมือนเดิม ให้รอ GitHub Pages อัปเดตและรีเฟรชหน้าเว็บ
- ให้เปิดเว็บไซต์ผ่าน URL ของ GitHub Pages ไม่ใช่ URL ของหน้า Repository
