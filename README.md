# QR พร้อมเพย์

เว็บแอปสร้าง QR Code พร้อมเพย์ สำหรับรับเงินผ่านมือถือ  
รองรับ iOS และ Android — ติดตั้งเป็น App ได้เลยโดยไม่ต้องผ่าน App Store

## ฟีเจอร์

- ✅ รองรับเบอร์มือถือ และเลขบัตรประชาชน
- ✅ ใส่จำนวนเงิน หรือปล่อยให้ผู้จ่ายกรอกเอง
- ✅ เพิ่มรายการสินค้า + คำนวณยอดรวมอัตโนมัติ
- ✅ บันทึก QR เป็นรูปภาพพร้อมรายละเอียด
- ✅ ติดตั้งบนมือถือเหมือน App (PWA)
- ✅ ใช้งาน offline ได้หลังจากเปิดครั้งแรก

## วิธีขึ้น GitHub Pages

1. สร้าง Repository ใหม่ (Public)
2. อัปโหลดไฟล์ทั้งหมดนี้ขึ้นไป
3. ไปที่ **Settings → Pages**
4. Source: เลือก `main` branch → `/ (root)`
5. กด Save → รอ 1-2 นาที
6. ได้ URL: `https://<username>.github.io/<repo-name>/`

## วิธีติดตั้งบนมือถือ

**iPhone (iOS):**
1. เปิด URL ใน Safari
2. กดปุ่ม Share (กล่องมีลูกศรขึ้น)
3. เลือก "Add to Home Screen"
4. กด Add

**Android:**
1. เปิด URL ใน Chrome
2. กด ⋮ (เมนู 3 จุด)
3. เลือก "Add to Home screen" หรือ "Install app"
4. กด Install

## ไฟล์ในโปรเจกต์

```
index.html      — หน้าแอปหลัก
manifest.json   — ข้อมูล PWA (ชื่อ, ไอคอน, สี)
sw.js           — Service Worker (cache + offline)
icon-192.png    — ไอคอน 192×192
icon-512.png    — ไอคอน 512×512
```
