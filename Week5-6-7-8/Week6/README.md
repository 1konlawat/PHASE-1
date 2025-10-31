# 🗓️ Week 6 — Feature Engineering

## 🎯 Goal / เป้าหมาย
- เรียนรู้การสร้างและปรับแต่งฟีเจอร์ให้เหมาะกับโมเดล  
- เข้าใจวิธีจัดการข้อมูล categorical / numerical  
- จัดการข้อมูลไม่สมดุล (imbalanced data)  

**เป้าหมายภาษาไทย:**  
สามารถปรับแต่งชุดข้อมูลให้เหมาะกับการเทรนโมเดลมากขึ้น เข้าใจเทคนิคการเข้ารหัส (encoding), การปรับขนาด (scaling), และการสร้างฟีเจอร์ใหม่

---

## 📚 Topics / หัวข้อเรียน
- **Feature Encoding (การเข้ารหัสข้อมูลหมวดหมู่)**  
  - One-Hot Encoding, Label Encoding, Target Encoding  
- **Scaling Numeric Features (การปรับขนาดข้อมูลเชิงตัวเลข)**  
  - StandardScaler, MinMaxScaler  
- **Feature Creation / Interaction Features**  
  - การสร้างฟีเจอร์ใหม่จากข้อมูลเดิม เช่น Age * Fare, Area = width × height  
- **Binning / Discretization**  
  - การแบ่งค่าต่อเนื่องออกเป็นกลุ่ม เช่น อายุเป็นช่วงวัย  
- **Handling Imbalanced Data (ข้อมูลไม่สมดุล)**  
  - ใช้ `SMOTE`, `class_weight='balanced'`  

**หัวข้อภาษาไทย:**  
เรียนรู้เทคนิคปรับแต่งฟีเจอร์ให้โมเดลเข้าใจข้อมูลดีขึ้น และแก้ปัญหาชุดข้อมูลที่มี class ไม่สมดุล

---

## 🛠️ Deliverable / ผลลัพธ์ที่ต้องทำ
- Notebook: Titanic / Telco Churn / House Prices  
  - สร้างชุดข้อมูลใหม่ด้วย Feature Engineering  
  - ทดลอง encoding หลายแบบ  
  - ทำ scaling และ handle imbalance  
  - Train + Evaluate โมเดลอีกครั้ง  
  - สรุปผลก่อน–หลัง Feature Engineering  
  - บันทึก notebook + README  

**ผลลัพธ์ภาษาไทย:**  
มี notebook ที่แสดงขั้นตอนการทำ Feature Engineering และเปรียบเทียบผลลัพธ์ก่อนและหลังปรับฟีเจอร์

---

## ✅ Tips / เคล็ดลับ
- Feature ดีช่วยให้โมเดลง่ายขึ้นแม้ไม่ซับซ้อน  
- อย่าทำ encoding โดยไม่เข้าใจประเภทของข้อมูล  
- ใช้การสร้างฟีเจอร์เพื่อเพิ่ม signal ให้โมเดล ไม่ใช่แค่เพิ่มจำนวน column  
- ทดลองทำ correlation heatmap ก่อนเลือกฟีเจอร์  
- อธิบาย insight แบบ non-tech เช่น:  
  > “เมื่อเพิ่มฟีเจอร์อายุเป็นช่วง (AgeGroup) ทำให้โมเดลเข้าใจกลุ่มผู้โดยสารได้ดีขึ้น”  

**เคล็ดลับภาษาไทย:**  
Feature Engineering คือหัวใจของงาน Data Science — โมเดลดีไม่เท่าข้อมูลดี  
