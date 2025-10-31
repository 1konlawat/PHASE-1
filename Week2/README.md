# 🗓️ Week 2 — Cross-Validation + Metrics

## 🎯 Goal / เป้าหมาย
- เข้าใจแนวคิด Cross-Validation (CV)  
- ประเมินโมเดลด้วย metric ที่หลากหลาย เช่น Accuracy, Precision, Recall, F1, ROC-AUC  
- เริ่มปรับแต่งโมเดลให้ผลลัพธ์เสถียร  

**เป้าหมายภาษาไทย:**  
เข้าใจการแบ่งข้อมูลหลายรอบ (CV) เพื่อตรวจสอบโมเดลอย่างแม่นยำ และเรียนรู้วิธีประเมินโมเดลด้วยตัวชี้วัดต่าง ๆ

---

## 📚 Topics / หัวข้อเรียน
- **Cross-Validation (CV)**  
  > K-Fold CV, Stratified CV  
  > ช่วยให้ประเมินโมเดลได้แม่นยำขึ้น ลด bias จากการแบ่งข้อมูลครั้งเดียว  
- **Evaluation Metrics / ตัวชี้วัดประเมินโมเดล**  
  - Accuracy: ความถูกต้องโดยรวม  
  - Precision: ความแม่นยำของ class ที่สนใจ  
  - Recall: การจับ class ที่สนใจได้ครบ  
  - F1 Score: ค่าเฉลี่ย Precision + Recall  
  - ROC-AUC: การวัด performance โมเดล classification  

**หัวข้อภาษาไทย:**  
ฝึกประเมินโมเดลด้วย metrics ต่าง ๆ และเข้าใจว่าค่าแต่ละตัวบอกอะไรเกี่ยวกับโมเดล

---

## 🛠️ Deliverable / ผลลัพธ์ที่ต้องทำ
- Notebook: Titanic หรือ Telco Churn dataset  
  - สร้างโมเดลเบื้องต้น  
  - ทำ K-Fold Cross-Validation  
  - ประเมินผลด้วย Accuracy / Precision / Recall / F1 / ROC-AUC  
  - บันทึก notebook + README  

**ผลลัพธ์ภาษาไทย:**  
มี notebook ที่ทำ CV และประเมินโมเดลครบทุกตัวชี้วัด พร้อมสรุปผลใน README

---

## ✅ Tips / เคล็ดลับ
- CV คือวิธีลดการ bias จาก train/test split เดียว  
- ใช้ `cross_val_score` / `StratifiedKFold` ใน sklearn  
- สร้างตารางสรุป metric ของแต่ละ fold → จะเห็นโมเดลเสถียรกว่าการใช้ train/test split เดียว  
- อธิบายผลให้ non-tech เข้าใจ เช่น:  
  > “โมเดลจับลูกค้าที่ churn ได้ 80% และแม่นยำ 75%”  

**เคล็ดลับภาษาไทย:**  
อย่ามองแต่ตัวเลข metric ให้เข้าใจว่าแต่ละตัวช่วยตอบคำถามอะไร เช่น Precision คือความแม่นยำ, Recall คือความครบถ้วน
