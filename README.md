# ระบบแจ้งรายชื่อผู้ประสานงาน เทศบาลนครเชียงราย

ไฟล์:
- index.html : หน้าให้หน่วยงานกรอกข้อมูล
- admin.html : หน้า Admin Login และดูข้อมูล
- config.js : ตั้งค่า Supabase URL และ anon/publishable key
- supabase.sql : SQL สำหรับสร้างตารางและ RLS

วิธีติดตั้ง:
1. สร้าง Supabase Project
2. เปิด SQL Editor และรันไฟล์ supabase.sql
3. แก้ config.js ใส่ Project URL และ anon/publishable key
4. ใน Supabase Authentication สร้าง User สำหรับ Admin
5. เปิดผ่าน web server หรือ deploy ไปยัง Vercel/Netlify/static hosting

คำเตือน:
ห้ามใส่ Supabase service_role key ใน config.js หรือไฟล์ HTML
