# FoodExpress - ระบบสั่งอาหารออนไลน์

เว็บไซต์สั่งอาหารออนไลน์ธีม Lineman/Grab พร้อมใช้งานทันที ไม่ต้องติดตั้งเพิ่ม!

## 🚀 วิธีเปิดใช้งาน (ง่ายมาก!)

1. **แตกไฟล์ zip**
2. **ดับเบิ้ลคลิก** ที่ไฟล์ `pages/login.html` หรือ `pages/index.html`
3. **เว็บไซต์จะเปิดในเบราว์เซอร์ทันที!**

❌ **ไม่ต้องติดตั้ง:**
- Node.js
- PHP Server
- Database
- Extension ใดๆ

✅ **ใช้เทคโนโลยี:**
- HTML5, CSS3, JavaScript
- Google Fonts
- localStorage

## 📁 โครงสร้างไฟล์

```
food-delivery-fixed/
├── css/
│   └── main.css          # CSS หลัก + Header/Footer styles
├── js/
│   └── main.js           # JavaScript functions ทั้งหมด
└── pages/
    ├── login.html        # เข้าสู่ระบบ
    ├── register.html     # สมัครสมาชิก
    ├── index.html        # หน้าแรก
    ├── menu.html         # เมนูอาหาร
    ├── cart.html         # ตะกร้าสินค้า
    ├── checkout.html     # ชำระเงิน
    ├── orders.html       # รายการสั่งซื้อ
    ├── tracking.html     # ติดตามสถานะ
    └── profile.html      # โปรไฟล์
```

## ✨ คุณสมบัติ

- ✅ ระบบล็อกอิน/สมัครสมาชิก
- ✅ เมนูอาหาร 12 รายการ
- ✅ ระบบตะกร้าสินค้า
- ✅ ชำระเงิน 3 วิธี
- ✅ ติดตามสถานะออเดอร์
- ✅ ประวัติการสั่งซื้อ
- ✅ จัดการโปรไฟล์
- ✅ Responsive Design

## 🎨 ออกแบบ

- โทนสีเหลือง-แดงแบบ Lineman/Grab
- Header & Footer ใช้ JavaScript inject
- CSS Variables ลดโค้ดซ้ำ
- Animations & Transitions

## 📱 รองรับเบราว์เซอร์

- Chrome (แนะนำ)
- Firefox
- Safari
- Edge

## 💡 เทคนิคพิเศษ

1. **Header/Footer**: ไม่ใช้ fetch() แต่ใช้ innerHTML injection แทน
2. **localStorage**: เก็บข้อมูล cart, orders, user
3. **Inline Styles**: บางหน้าใช้ inline styles เพื่อลดไฟล์
4. **Minified Code**: บางส่วนใช้ minified JavaScript

## 🔧 การแก้ปัญหา

**ปัญหา: Header/Footer ไม่แสดง**
- ตรวจสอบว่าไฟล์ main.js โหลดสำเร็จ
- เปิด Console (F12) ดู error

**ปัญหา: ข้อมูลหายหมด**
- localStorage จะ clear เมื่อล้าง browser cache
- ข้อมูลเฉพาะเบราว์เซอร์นั้นๆ

## 📞 การใช้งาน Live Server (ถ้าต้องการพัฒนาต่อ)

1. ติดตั้ง VS Code Extension: "Live Server"
2. คลิกขวาที่ไฟล์ HTML → Open with Live Server
3. แก้ไขโค้ด → Auto reload

## 🌟 ทดลองใช้งาน

1. เปิด `pages/login.html`
2. กรอกอีเมลและรหัสผ่านอะไรก็ได้
3. เข้าสู่ระบบ → เริ่มสั่งอาหาร!

---

**สร้างโดย:** FoodExpress Team 🍜
**ปี:** 2026
**License:** Free to use
