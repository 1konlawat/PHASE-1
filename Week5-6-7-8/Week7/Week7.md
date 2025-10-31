# 🗓️ Week 7 — Explainability (การอธิบายโมเดล)

## 🎯 Goal / เป้าหมาย
- เข้าใจวิธีอธิบายการทำงานของโมเดล Machine Learning  
- วิเคราะห์ว่า feature ใดมีอิทธิพลต่อผลลัพธ์มากที่สุด  
- สามารถใช้ SHAP และ Permutation Importance เพื่ออธิบายผลโมเดล  

**เป้าหมายภาษาไทย:**  
เข้าใจ “เหตุผล” ที่อยู่เบื้องหลังการพยากรณ์ของโมเดล สามารถอธิบายได้ว่าโมเดลใช้ข้อมูลใดในการตัดสินใจ

---

## 📚 Topics / หัวข้อเรียน
- **Feature Importance**  
  > วิเคราะห์ว่าฟีเจอร์ไหนมีผลมากที่สุดต่อโมเดล (Tree-based models จะมี built-in importance)  
- **Permutation Importance**  
  > วัดความสำคัญของฟีเจอร์โดยดูผลเมื่อสลับค่าข้อมูล  
- **SHAP Values (SHapley Additive exPlanations)**  
  > อธิบายการคำนวณการพยากรณ์ในระดับรายแถว (per-sample explanation)  
- **Visualization for Explainability**  
  - Bar plots (feature importance)  
  - SHAP summary plot, dependence plot  

**หัวข้อภาษาไทย:**  
เรียนรู้การอธิบายผลลัพธ์ของโมเดล ทั้งแบบภาพรวม (global) และรายกรณี (local) เพื่อให้เข้าใจการตัดสินใจของโมเดล

---

## 🛠️ Deliverable / ผลลัพธ์ที่ต้องทำ
- Notebook: ใช้โมเดลจาก Week 5 หรือ Week 6  
  - แสดง Feature Importance  
  - ทำ Permutation Importance  
  - ใช้ SHAP อธิบายผลรายตัวอย่าง  
  - Visualize ด้วย plot ต่าง ๆ  
  - เขียน README อธิบาย insight  

**ผลลัพธ์ภาษาไทย:**  
มี notebook ที่อธิบายว่าโมเดลให้ความสำคัญกับฟีเจอร์ใดมากที่สุด พร้อมภาพประกอบและคำอธิบายเข้าใจง่าย

---

## ✅ Tips / เคล็ดลับ
- SHAP สามารถใช้ได้กับหลายโมเดล เช่น XGBoost, RandomForest  
- Permutation Importance เหมาะกับการเปรียบเทียบฟีเจอร์ที่มีหลายประเภท  
- ใช้ Visualization เพื่อสื่อสารกับคนไม่ใช่สายเทคนิค เช่น ผู้บริหาร / ลูกค้า  
- อธิบาย insight แบบ non-tech เช่น:  
  > “รายได้และประวัติการชำระเงินเป็นปัจจัยสำคัญที่สุดที่ทำให้ลูกค้าเลิกใช้บริการ”  

**เคล็ดลับภาษาไทย:**  
อย่าแค่ดูว่าโมเดล “แม่น” แค่ไหน — ต้องรู้ด้วยว่ามัน “คิดอย่างไร”  
นี่คือสิ่งที่แยก “Data Scientist” ออกจาก “Model Builder”
