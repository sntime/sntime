# Profile
![img_me](img/ThisMe.jpg)


## About Me 😀
สวัสดีครับ!
ผม นายศุภนิมิต นิลฉวี ชื่อเล่น ไทม์ เป็นนักศึกษาปีที่ 3 สาขาวิทยาการคอมพิวเตอร์ มหาวิทยาลัยเกษตรศาสตร์ วิทยาเขตศรีราชา
ผมสนใจในการพัฒนาเว็บไซต์และการออกแบบระบบที่ช่วยแก้ปัญหาในชีวิตประจำวัน กำลังศึกษาและมองหาโอกาสในการทำงานเป็น Frontend Developer

_________________________________________________________________
## 💡Key Skills
**Hard Skills**
- Languages: Python, C, C++, Java, HTML, CSS, JavaScript
- Frameworks & Libraries: React.js
- Tools: Git, VS Code, Figma, Tableau, PowerBI
  
**Soft Skills**
- การวิเคราะห์ปัญหา
- การทำงานเป็นทีม
- พร้อมเรียนรู้สิ่งใหม่
- บริหารจัดการเวลา
- ความสามารถในการปรับตัว

_________________________________________________________________
## 🌱 What I'm Learning
- ฝึกใช้ React.js 
- ศึกษาเกียวกับ TypeScript
- ศึกษา UX/UI Design เพื่อการพัฒนาเว็บให้เป็นมิตรกับผู้ใช้

_________________________________________________________________
## 📂 Projects While Studying
### 1. [Calculate taxes](https://onlinegdb.com/6bRlgFcal)
รายละเอียด: โปรแกรมภาษีส่วนบุคคลสำหรับผู้ดูแลระบบเพื่อจัดการผู้เสียภาษี โปรแกรมนี้พัฒนาโดยใช้ C++
- การคำนวณภาษี
  - ใช้ระบบภาษีแบบขั้นบันได คำนวณจากรายได้สุทธิ = รายได้ - รายจ่าย - ลดหย่อน
  - รองรับการลดหย่อนภาษีสูงสุด 100,000 บาท
- การจัดการไฟล์
  - อ่านและเขียนข้อมูลในไฟล์ Taxed.txt
  - เพิ่ม, ลบ, และค้นหารายการภาษีในไฟล์
- ฟังก์ชันของผู้ดูแลระบบ (Admin)
  - เข้าถึงได้เฉพาะการล็อกอิน (รหัสผ่านคือ 12345)
  - ผู้ดูแลสามารถดู, เพิ่ม, ลบ หรือค้นหารายการภาษีตาม ID ได้

### 2. [Tree (Character)](https://onlinegdb.com/6bfahBgCa)
รายละเอียด: โปรแกรมนี้ช่วยให้ผู้ใช้สามารถสร้าง Tree ชนิดต่างๆ ได้แก่ Binary Tree, Ternary Tree และ N-ary Tree โปรแกรมนี้พัฒนาโดยใช้ C
- Binary Tree
  ฟังก์ชัน:
  - สร้างโหนดใหม่
  - เพิ่มโหนดซ้าย (L) หรือขวา (R)
- Ternary Tree
  ฟังก์ชัน:
  - สร้างโหนดใหม่
  - เพิ่มโหนดในตำแหน่ง L, M, R
- N-ary Tree
  ฟังก์ชัน:
  - สร้างโหนดใหม่ (กำหนดโหนดมีลูกสูงสุดได้ 20 โหนด)
  - เพิ่มโหนดลูก
การทำงาน
- รับข้อมูลจากผู้ใช้ เช่น จำนวนโหนด ชื่อโหนด และตำแหน่งโหนดลูก
- แสดงผล Inorder, Preorder และ Postorder

### 3. [Tax System](https://drive.google.com/file/d/1VYVDTkMCrS4Lsqxy6spAqlrpqFgRIMxk/view?usp=sharing)
รายละเอียด: เป็นระบบที่ออกแบบขึ้นเพื่อช่วยให้ผู้ใช้งานสามารถทำธุรกรรมที่เกี่ยวข้องกับการเสียภาษีได้อย่างสะดวก รวดเร็ว และลดความยุ่งยาก โดยใช้เว็บไซต์ออนไลน์แทนวิธีการแบบดั้งเดิมที่ต้องเดินทางไปยังสำนักงานสรรพากร โดยเนื้อหาโปรเจคมีการออกแบบคร่าวๆมีดังนี้
- DFD (Data Flow Diagram):
  - มีการออกแบบ DFD Level 0 และ Level 1 เพื่อแสดงการไหลของข้อมูลระหว่างผู้ใช้งาน, ระบบ และฐานข้อมูลแสดงขั้นตอนหลัก เช่น การสมัครสมาชิก, คำนวณภาษี, การยื่นแบบ, และชำระภาษี
- Use Case Diagram:
  - แสดงบทบาทของผู้ใช้งาน (User) และเจ้าหน้าที่ (Admin)ครอบคลุมฟังก์ชัน เช่น การล็อกอิน, ยื่นแบบ, ตรวจสอบเอกสาร และการอนุมัติ
- Data Dictionary:
  - จัดเก็บข้อมูลสำคัญ เช่น ข้อมูลส่วนตัว, ข้อมูลด้านธนาคาร, คำถาม-คำตอบ, และข้อมูลการคำนวณภาษี
- Class Diagram:
  - แสดงโครงสร้างของระบบ เช่น User, TaxForm, Payment, และ Document
- UX/UI Design:
  - ออกแบบอินเทอร์เฟซให้ใช้งานง่าย ทั้งสำหรับผู้ใช้งานทั่วไปและเจ้าหน้าที่
  - [Figma](https://shorturl.asia/OUbDi)

### 4. [Storytelling การเกิดอุบัติเหตุในปี 63](https://public.tableau.com/app/profile/panupong.thongchoed/viz/Story_17289919097110/Story?fbclid=IwZXh0bgNhZW0CMTEAAR2QP72-R6LuQWD2dAqS1K8M3_MwJv9VWs5b1oUUWS4Q2oGv-BuuEHHSCsc_aem_u_v9JEU51fEjhxFeWCkwng)
รายละเอียด: การทำ Storytelling โดยใช้ Dashboard การเกิดอุบัติเหตุในปี 63
- จำนวนอุบัติเหตุในแต่ละเดือน
  - เปรียบเทียบจำนวนการเกิดอุบัติเหตุของลักษณะการเกิดเหตุในแต่ละเดือน
- อุบัติเหตุที่เกิดขึ้นในแต่ละจังหวัด
  - แสดงความหนาแน่นของการเกิดอุบัติเหตุในแต่ละพื้นที่ของประเทศไทย
- จำนวนผู้เสียชีวิตและผู้บาดเจ็บในแต่ละจังหวัด ปี 2020
  - เปรียบเทียบผู้บาดเจ็บและผู้เสียชีวิตในแต่ละจังหวัด
- ประเภทของรถที่เกิดอุบัติเหตุในกรุงเทพ
  - เปรียบเทียบจำนวนการเกิดอุบัติเหตุของรถแต่ละประเภทในกรุงเทพ

_________________________________________________________________
## 🤝 Let's Connect
- Line: 103456789000
- Email: suphanimit.time@gmail.com
