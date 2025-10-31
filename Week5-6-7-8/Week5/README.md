# 🗓️ Week 5 — XGBoost + Hyperparameter Tuning

## 🎯 Goal / เป้าหมาย
- เรียนรู้การใช้ XGBoost สำหรับ Classification / Regression  
- ทำ Hyperparameter Tuning เพื่อปรับปรุงประสิทธิภาพโมเดล  
- เปรียบเทียบผลกับ Tree-based Models ก่อนหน้า  

**เป้าหมายภาษาไทย:**  
เข้าใจวิธีใช้ XGBoost และปรับพารามิเตอร์ให้โมเดลทำงานได้ดีที่สุด พร้อมเปรียบเทียบกับ Decision Tree / Random Forest

---

## 📚 Topics / หัวข้อเรียน
- **XGBoost**  
  > Gradient Boosting Tree แบบมีประสิทธิภาพสูง  
- **Hyperparameter Tuning**  
  - `n_estimators`, `max_depth`, `learning_rate`, `subsample`  
  - ใช้ `GridSearchCV` หรือ `RandomizedSearchCV`  
- **Evaluation Metrics**  
  - Accuracy, Precision, Recall, F1, RMSE (Regression)  
- **Model Comparison**  
  > เปรียบเทียบ performance ของ XGBoost กับ Decision Tree / Random Forest  

**หัวข้อภาษาไทย:**  
ฝึกใช้ XGBoost พร้อมปรับพารามิเตอร์เพื่อให้โมเดลแม่นยำขึ้น และเข้าใจว่าความแตกต่างกับ Tree-based models ก่อนหน้านั้นเป็นอย่างไร

---

## 🛠️ Deliverable / ผลลัพธ์ที่ต้องทำ
- Notebook: Titanic / House Prices หรือ dataset อื่น ๆ  
  - Train XGBoost Model  
  - ทำ Hyperparameter Tuning ด้วย GridSearchCV / RandomizedSearchCV  
  - ประเมินผลด้วย metric ที่เหมาะสม  
  - เปรียบเทียบกับ Decision Tree / Random Forest  
  - บันทึก notebook + README  

**ผลลัพธ์ภาษาไทย:**  
มี notebook ที่ใช้ XGBoost พร้อมปรับ Hyperparameter และเปรียบเทียบผลลัพธ์กับโมเดลก่อนหน้า พร้อมสรุป insight

---

## ✅ Tips / เคล็ดลับ
- เริ่ม tuning จากพารามิเตอร์หลักก่อน (`n_estimators`, `max_depth`, `learning_rate`)  
- ใช้ CV เพื่อตรวจสอบ performance ก่อนสรุป  
- สร้างตารางเปรียบเทียบ metric ระหว่างโมเดลหลายแบบ  
- อธิบาย insight แบบ non-tech เช่น:  
  > “XGBoost ปรับพารามิเตอร์แล้วแม่นยำขึ้นจาก Random Forest 2–3%”  

**เคล็ดลับภาษาไทย:**  
อย่ามองแต่ accuracy ให้เข้าใจว่าการปรับพารามิเตอร์ช่วยอะไร และโมเดลตอบโจทย์ธุรกิจอย่างไร
