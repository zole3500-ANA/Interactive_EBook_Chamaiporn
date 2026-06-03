# 📖 Interactive E-Book Chamaiporn (แบบเสนอชื่อนักส่งเสริมสหกรณ์ดีเด่น ปี 2569)

ระบบ E-Book แบบโต้ตอบได้ (Interactive E-Book) แสดงผลเอกสารเสนอชื่อเพื่อพิจารณาคัดเลือกข้าราชการพลเรือนดีเด่น ประจำปี พ.ศ. 2569 ประเภทนักส่งเสริมสหกรณ์ดีเด่น ของ **นางสาวชไมพร มาตย์คำมี** สำนักงานสหกรณ์จังหวัดกาฬสินธุ์

---

## 🌐 ลิงก์สำหรับเข้าใช้งานระบบ (Live E-Book Link)
เมื่อเปิดใช้งาน GitHub Pages แล้ว คุณจะสามารถเข้าชมเอกสาร e-book แบบออนไลน์ได้ทันทีที่:
👉 **[https://zole3500-ana.github.io/Interactive_EBook_Chamaiporn/](https://zole3500-ana.github.io/Interactive_EBook_Chamaiporn/)**

---

## ✨ คุณสมบัติเด่น (Features)
*   **3D Page Flipping Effect**: เอฟเฟกต์เปิดหน้าหนังสือเสมือนจริงแบบ 3D
*   **Vector Zoom (High-Res)**: ระบบซูมขยายเอกสารแบบคมชัดสูง ไม่แตกเบลอ
*   **Text Search Engine**: ค้นหาคำศัพท์ในหน้าเอกสารทั้งหมดได้ในตัว
*   **Responsive Design**: รองรับการใช้งานเต็มรูปแบบบนมือถือ, แท็บเล็ต และคอมพิวเตอร์
*   **Theme Selection**: ปรับเปลี่ยนสีพื้นหลังได้ 4 โทนสีตามใจชอบ (Midnight Slate, Walnut, Royal Emerald, Clean Alabaster)
*   **Autoplay**: ระบบเล่นเปิดหน้าอัตโนมัติ
*   **Page Sound Effect**: เสียงจำลองการพลิกหน้ากระดาษ
*   **Original PDF Download**: ดาวน์โหลดเอกสาร PDF ต้นฉบับจากตัว E-Book ได้ทันที

---

## 🛠️ วิธีการเปิดใช้งานบน GitHub Pages (How to Enable GitHub Pages)

เพื่อให้ผู้ใช้อื่นสามารถเปิดอ่าน E-Book นี้ผ่านลิงก์ได้โดยตรง ให้ทำตามขั้นตอนดังนี้:

1.  ไปที่หน้า Repository ของคุณบน GitHub: [https://github.com/zole3500-ANA/Interactive_EBook_Chamaiporn](https://github.com/zole3500-ANA/Interactive_EBook_Chamaiporn)
2.  คลิกที่แถบ **Settings** (ตั้งค่า) ด้านบน
3.  ในเมนูด้านซ้าย เลือกหัวข้อ **Pages** (ภายใต้ส่วน *Code and automation*)
4.  ในส่วน **Build and deployment**:
    *   **Source**: เลือก `Deploy from a branch`
    *   **Branch**: เลือกสาขา `main` (หรือ branch ที่ใช้งาน) และโฟลเดอร์เป็น `/ (root)`
    *   คลิกปุ่ม **Save**
5.  รอประมาณ 1-2 นาที GitHub จะทำการสร้างลิงก์เว็บไซต์ให้คุณ ซึ่งสามารถเข้าใช้งานได้ทาง:
    `https://zole3500-ana.github.io/Interactive_EBook_Chamaiporn/`

---

## 📂 โครงสร้างไฟล์ในโปรเจกต์ (Project Structure)
*   [index.html](file:///d:/Gravity%2002/index.html) (หรือ [Interactive_EBook_Chamaiporn.html](file:///d:/Gravity%2002/Interactive_EBook_Chamaiporn.html)) - หน้าหลักของระบบ E-Book
*   [pdf_data.js](file:///d:/Gravity%2002/pdf_data.js) - ไฟล์ข้อมูล PDF ที่ถูกเข้ารหัสแบบ Base64 เพื่อให้ระบบสามารถรันแบบออฟไลน์และออนไลน์ได้รวดเร็วโดยไม่ต้องดาวน์โหลด PDF ใหม่ทั้งหมด
*   `690602แบบเสนอชื่อนักส่งเสริมดีเด่น ปี69 ชไมพร .pdf` - ไฟล์ PDF ต้นฉบับ
*   `sound.mp3` - ไฟล์เสียงเอฟเฟกต์สำหรับเปลี่ยนหน้า (ระบบใช้ Web Audio API สังเคราะห์เสียงเสริมด้วยเพื่อความเร็วสูงสุด)

---

## ⌨️ ปุ่มลัดคีย์บอร์ด (Keyboard Shortcuts)
*   `➡` / `Spacebar` : หน้าถัดไป
*   `⬅` : หน้าก่อนหน้า
*   `Home` : กลับไปหน้าแรกสุด
*   `End` : ไปยังหน้าสุดท้ายสุด
*   `Double Click / Scroll Wheel` : ซูมขยายหน้าเอกสาร
