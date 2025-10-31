# 🗓️ Week 4 — Tree-based Models

## 🎯 Goal / เป้าหมาย
- เข้าใจการทำงานของ Decision Tree และ Random Forest  
- เรียนรู้การป้องกัน Overfitting และการใช้ Feature Importance  
- เปรียบเทียบประสิทธิภาพของโมเดล Tree-based  

**เป้าหมายภาษาไทย:**  
เข้าใจโมเดล Tree-based เบื้องต้น สามารถสร้างและประเมิน Decision Tree และ Random Forest พร้อมดูว่าฟีเจอร์ใดสำคัญ

---

## 📚 Topics / หัวข้อเรียน
- **Decision Tree**  
  > สร้างโมเดลแบบ tree structure เพื่อตัดสินใจจาก feature  
- **Random Forest**  
  > Ensemble ของหลาย Decision Tree เพื่อลด overfitting  
- **Overfitting / Pruning**  
  > ป้องกันโมเดลจำข้อมูลฝึกมากเกินไป  
- **Feature Importance**  
  > วิเคราะห์ว่า feature ใดมีผลต่อการทำนายมากที่สุด  
- **Evaluation Metrics**  
  > Accuracy, Precision, Recall, F1  

**หัวข้อภาษาไทย:**  
เรียนรู้ Tree-based models, การรวมหลายต้นไม้ (Ensemble) และวิเคราะห์ความสำคัญของแต่ละฟีเจอร์

---

## 🛠️ Deliverable / ผลลัพธ์ที่ต้องทำ
- Notebook: Titanic / Telco Churn หรือ dataset classification อื่น ๆ  
  - Train Decision Tree + Random Forest  
  - ปรับ hyperparameter ง่าย ๆ เช่น max_depth, n_estimators  
  - ประเมินผลด้วย Accuracy / Precision / Recall / F1  
  - ดู Feature Importance และ visualize  
  - บันทึก notebook + README  

**ผลลัพธ์ภาษาไทย:**  
มี notebook ที่สร้าง Tree-based models, ประเมินผล และสรุป insight ลง README  

---

## ✅ Tips / เคล็ดลับ
- ใช้ `plot_tree` หรือ `feature_importances_` เพื่อ visualize โมเดล  
- Random Forest มักแม่นกว่า Decision Tree แต่ต้องปรับ n_estimators และ max_depth  
- สร้างตารางเปรียบเทียบ metric ของทั้งสองโมเดล  
- อธิบาย insight แบบ non-tech เช่น:  
  > “เพศและอายุเป็น feature สำคัญที่สุดในการทำนายการรอดชีวิตของ Titanic”  

**เคล็ดลับภาษาไทย:**  
อย่ามองแต่ผล metric ให้เข้าใจว่าแต่ละโมเดลตัดสินใจอย่างไร และ Feature ไหนสำคัญที่สุด
