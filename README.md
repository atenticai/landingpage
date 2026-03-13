# AirClean Pro — Landing Page

## Work Report

### เวลาที่ใช้จริง
| ขั้นตอน | เวลา |
|---|---|
| วิเคราะห์ Brief + วางโครงสร้าง | 30 นาที |
| ออกแบบ Layout + เขียน HTML/CSS | 3 ชั่วโมง |
| JavaScript (Form, Countdown, Tracking) | 1 ชั่วโมง |
| Refactor CSS + แก้ bug | 1.5 ชั่วโมง |
| QA Mobile + PageSpeed Optimization | 1 ชั่วโมง |
| **รวม** | **~7 ชั่วโมง** |

---

### ทำไมถึงวาง Layout แบบนี้เพื่อปิดการขาย?

#### 1. Hero Section — ตีปัญหาก่อนเสนอทางออก
วางข้อความ "แอร์ไม่เย็น กลิ่นอับ หยุดทนได้แล้ว" ไว้บนสุด  
เพราะลูกค้าค้นหาเมื่อ **มีปัญหาอยู่แล้ว** — ต้องสะท้อนความเจ็บปวดก่อนพูดถึงสินค้า  
CTA "จองคิวฟรีเลย" อยู่ครึ่งหน้าบน ลดแรงเสียดทานด้วย "ไม่มีค่าจอง"

#### 2. Trust Signals — วางทันทีหลัง Hero
Stats bar (4,200 ลูกค้า / 4.9★ / รับประกัน 30 วัน / 97% On-time) อยู่ under fold แรก  
เพราะหลังจากลูกค้า relate กับปัญหาแล้ว สิ่งถัดไปที่สมองถาม = "แล้วเชื่อถือได้แค่ไหน?"

#### 3. Service Highlights — ตัดข้อโต้แย้ง
3 จุดเด่น (น้ำยา Medical Grade / ช่างตรวจประวัติ / ตรงเวลา) เป็น objection handler  
แต่ละจุดแก้ความกังวลที่พบบ่อย: กลัวสารเคมี / กลัวคนแปลกหน้าเข้าบ้าน / กลัวรอนาน

#### 4. Social Proof → Pricing
รีวิวมาก่อนราคา — เพราะถ้าเห็นราคาก่อนยังไม่มี social proof มักรู้สึกว่าแพง  
หลังอ่านรีวิวแล้ว ราคาเดิมกลายเป็น "คุ้ม"

#### 5. Urgency + Final CTA
Countdown timer + "เหลือ 7 คิวสุดท้าย" กระตุ้น FOMO  
วางไว้ท้ายสุดก่อน form เพราะลูกค้าที่เลื่อนมาถึงตรงนี้ = intent สูงสุด

---

### Technical Stack
- **HTML/CSS/JS** — Pure vanilla, zero framework dependency  
- **Performance** — CSS/JS แยกไฟล์ + minified, preload hints, defer script  
- **Tracking** — Google Tag Manager + gtag Conversion events  
- **Mobile-First** — Breakpoints: 1024 / 900 / 768 / 640 / 480 / 360px  
- **Hosting** — GitHub Pages ready

---

### File Structure
```
/
├── index.html          (41 KB)
├── assets/
│   ├── style.min.css   (42 KB)
│   └── main.min.js     (7 KB)
├── cookie-policy.html
├── privacy-policy.html
└── terms.html
```

### Deliverables
- [x] Landing Page (index.html)
- [ ] URL (pending GitHub Pages deploy)
- [ ] PageSpeed Screenshot (pending deploy)
- [x] Work Report (this file)
