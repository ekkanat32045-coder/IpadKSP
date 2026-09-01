# KSP iPad Service & Device Center (Production Ready)
ระบบบริหารจัดการครุภัณฑ์และศูนย์บริการ iPad โรงเรียนกระสังพิทยาคม สพม.บุรีรัมย์

---

## 1. วิธีติดตั้งฐานข้อมูลบน Supabase
1. เข้าไปที่ [Supabase Dashboard](https://supabase.com/dashboard)
2. ไปที่เมนู **SQL Editor**
3. คัดลอกโค้ด SQL จาก **PART 2** วางแล้วกด **Run** เพื่อสร้างตารางและสร้าง User เริ่มต้น

---

## 2. วิธีตั้งค่า API Keys ใน `index.html`
เปิดไฟล์ `index.html` แล้วระบุค่า URL และ Key ของ Supabase:

```javascript
const SUPABASE_URL = "[https://your-project-id.supabase.co](https://your-project-id.supabase.co)";
const SUPABASE_ANON_KEY = "your-anon-public-key";