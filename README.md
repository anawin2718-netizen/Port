# พอร์ตโฟลิโอ นักศึกษา BU (One-page)

- `index.html` — โครงหน้าเว็บและสไตล์
- `data.json` — เนื้อหาทั้งหมด (แก้ชื่อ ลิงก์ ผลงาน ได้ที่นี่ไฟล์เดียว)
- `assets/bu-campus.jpg` — ใส่ภาพตึก BU ของคุณเอง (ถ้ายังไม่ใส่ จะแสดงภาพวาดตึกสำรองให้)

## ขึ้น GitHub Pages
1. อัปโหลดไฟล์ทั้งหมดขึ้น repository
2. Settings → Pages → Branch: `main` / root → Save
3. เปิดลิงก์ `https://<ชื่อผู้ใช้>.github.io/<ชื่อ repo>/`

## ทดสอบในเครื่อง
เปิด `index.html` ได้เลย (ใช้ข้อมูลสำรองในไฟล์) แต่ถ้าแก้ `data.json` แล้วอยากเห็นผล
ให้รัน `python3 -m http.server` แล้วเปิด http://localhost:8000
