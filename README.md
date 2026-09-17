# ตรวจก่อนส่ง (COD Risk Shield)
> ระบบเครือข่าย AI ตรวจสอบความเสี่ยงลูกค้าเก็บเงินปลายทาง (COD) และป้องกันพัสดุตีกลับสำหรับร้านค้าออนไลน์

โครงการส่งเข้าแข่งขัน: **NTT DATA Digital Innovation Challenge**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-เข้าใช้งานได้ทันที-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white)](https://3towson.github.io/cod-risk-shield/)

🌐 **Live Demo Website:** [https://3towson.github.io/cod-risk-shield/](https://3towson.github.io/cod-risk-shield/)  
📂 **GitHub Repository:** [https://github.com/3towson/cod-risk-shield](https://github.com/3towson/cod-risk-shield)

---

## ปัญหาที่พบ (Pain Point)
* ผู้ประกอบการและร้านค้าออนไลน์ (E-Commerce) ประสบปัญหาการจัดส่งสินค้าแบบเก็บเงินปลายทาง (Cash on Delivery: COD) แล้วลูกค้า "ปฏิเสธรับสินค้าหน้าบ้าน", "ปิดเครื่องหนีขนส่ง", หรือ "สั่งเล่น"
* ร้านค้าต้องแบกรับต้นทุนค่าจัดส่งไป-กลับ ค่าบรรจุภัณฑ์ และค่าเสียโอกาสสินค้าค้างในระบบขนส่งเฉลี่ย 50–150 บาทต่อชิ้น
* ร้านค้าต่างคนต่างขาย ไม่มีฐานข้อมูลความเสี่ยงร่วมกันเพื่อป้องกันความเสียหายซ้ำ

---

## โซลูชันและฟังก์ชันเด่น (Key Features)

1. **AI Order & Chat Extractor (ตัวช่วยอ่านแชทอัจฉริยะ):**
   * วางข้อความออเดอร์ หรือแชทการพูดคุยกับลูกค้า/ขนส่ง ระบบ AI (NLP Engine) จะสกัด ชื่อ, เบอร์โทรศัพท์, ยอดเงิน, แพลตฟอร์ม และ สาเหตุที่ปฏิเสธ ให้อัตโนมัติใน 1 วินาที
2. **Crowdsourced Risk Database (เครือข่ายข้อมูลความเสี่ยงร่วม):**
   * ตรวจสอบประวัติการปฏิเสธรับสินค้าแบบ Real-time พร้อมแสดงระดับความเสี่ยง (ปลอดภัย / เฝ้าระวัง / เสี่ยงสูง)
   * แสดงสถิติจำนวนครั้งที่เคยปฏิเสธ ยอดความเสียหายสะสม และช่องทางที่เคยพบ
3. **Smart Store Recommendation:**
   * ให้คำแนะนำเชิงปฏิบัติการแก่ร้านค้า (เช่น ขอโอนมัดจำค่าส่ง ฿50-100 หรือโทรคอนเฟิร์มก่อนแพ็ก)
4. **PDPA Compliant (มาตรฐานการปกป้องข้อมูลส่วนบุคคล):**
   * จัดเก็บเฉพาะข้อมูลจำเป็นและสถิติประวัติความเสี่ยงเพื่อความปลอดภัยของข้อมูลตามมาตรฐาน PDPA

---

## สถาปัตยกรรมและเทคโนโลยี (Tech Stack)
* **Frontend:** Pure HTML5, Modern CSS3 (Dark/Light Theme, Responsive Mobile-first), Vanilla JavaScript (ES6+)
* **Performance:** 100% Client-side Execution, Zero Dependency, Ultra-fast Load Time (< 100ms)
* **Storage:** LocalStorage Demo Persistence (จดจำข้อมูลที่รายงานใหม่ได้แบบ Real-time)

---

## วิธีเปิดทดสอบใช้งาน (How to Run)
1. ดับเบิ้ลคลิกเปิดไฟล์ `index.html` ผ่านเว็บเบราว์เซอร์ใดก็ได้ (Chrome, Edge, Safari, Firefox)
2. หรือเข้าชม Live Demo ผ่าน GitHub Pages / Vercel
