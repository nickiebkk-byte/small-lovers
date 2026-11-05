SMALL LOVERS V8 — ภาพถ่าย 10 สูตรกาแฟ + สติกเกอร์ CHIBI

- index.html เว็บแอป 48 สูตรเดิม ไม่เพิ่มหรือลบเมนู
- assets/drinks: ภาพทุกสูตร + ภาพกาแฟ 10 สูตรใหม่ ที่เชื่อมกับชื่อสูตรเดิม
- assets/source-images: ภาพต้นฉบับแนวตั้ง 10 ภาพ สำหรับใช้งานอื่น ๆ
- assets/stickers: ต้นฉบับสติกเกอร์ทั้งแผ่น + ไอคอน CHIBI แยก 27 PNG
- assets/pwa: Home Screen Icon สีดำเงาตามที่เลือก
- ภาพการ์ดและรายละเอียดใช้ object-fit: contain ไม่ครอปแก้ว
- แก้ cache service worker เพื่อให้เว็บโหลดไฟล์ใหม่
- ให้ deploy ทั้งโฟลเดอร์ โดยนำไฟล์ index.html, assets, sw.js, manifest.webmanifest, favicon.ico ไปไว้ที่ root เว็บไซต์

หมายเหตุ: สูตรอื่นบางสูตรยังใช้ SVG Illustration ไม่ใช่ภาพถ่าย (แยกไฟล์อยู่ใน assets/drinks)


V9: เพิ่มภาพเครื่องดื่มเฉพาะสูตร 17–30 อีก 14 ภาพ แบบดิจิทัลอิลลัสเตรชัน เห็นเต็มแก้ว ไม่ใส่ตัวหนังสือในรูป พร้อมตรวจเส้นทางรูปครบ 48 สูตร รายงานที่ IMAGE_AUDIT.txt

V10: ตรวจและเชื่อมภาพกับสูตรทั้ง 48 รายการใน index.html แล้ว (14 ภาพใหม่หมายเลข 17–30 อยู่ใน assets/drinks) ทั้งหน้ารายการและหน้ารายละเอียดเรียกผ่าน recipeImage(r); รีเฟรช service worker cache.
