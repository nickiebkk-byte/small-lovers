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
