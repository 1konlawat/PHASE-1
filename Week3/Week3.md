# 🗓️ Week 3 — Regression Models

## 🎯 Goal / เป้าหมาย
- เรียนรู้ Regression Models เบื้องต้น  
- ทำความเข้าใจ Linear Regression และ Regularization (Ridge, Lasso)  
- ประเมินโมเดลด้วย RMSE และ R²  

**เป้าหมายภาษาไทย:**  
เข้าใจวิธีสร้างโมเดลทำนายตัวเลข (Regression) และวิธีวัดความแม่นยำของโมเดล

---

## 📚 Topics / หัวข้อเรียน
- **Linear Regression**  
  > โมเดลพื้นฐานสำหรับทำนายตัวเลข  
- **Ridge & Lasso Regression (Regularization)**  
  > ลด overfitting ด้วย penalty term  
- **Polynomial Features**  
  > สร้าง feature ใหม่เพื่อ capture ความสัมพันธ์ไม่เชิงเส้น  
- **Evaluation Metrics / ตัวชี้วัดประเมินโมเดล**  
  - RMSE (Root Mean Squared Error)  
  - MAE (Mean Absolute Error)  
  - R² (Coefficient of Determination)  

**หัวข้อภาษาไทย:**  
ฝึกสร้างโมเดล Regression เบื้องต้น, ใช้ Regularization ป้องกัน overfitting, และประเมินผลโมเดลด้วยตัวชี้วัดหลายตัว

---

## 🛠️ Deliverable / ผลลัพธ์ที่ต้องทำ
- Notebook: House Prices dataset หรือ dataset ตัวเลขอื่น ๆ  
  - ทำ EDA + Data Cleaning  
  - Train Linear Regression + Ridge + Lasso  
  - ประเมินผลด้วย RMSE, MAE, R²  
  - บันทึก notebook + README  

**ผลลัพธ์ภาษาไทย:**  
มี notebook ที่สร้างโมเดล Regression หลายแบบ พร้อมประเมินผล และสรุป insight ลง README

---

## ✅ Tips / เคล็ดลับ
- ลอง plot actual vs predicted → เข้าใจ performance ของโมเดล  
- ทดลอง feature scaling ถ้าใช้ Regularization → จะช่วยให้โมเดลเสถียรขึ้น  
- สร้างตารางเปรียบเทียบ metric ของแต่ละโมเดล  
- อธิบาย insight แบบ non-tech เช่น:  
  > “โมเดล Ridge ช่วยทำนายราคาบ้านได้แม่นยำกว่า Linear Regression ปกติ”  

**เคล็ดลับภาษาไทย:**  
อย่ามองแต่ตัวเลข metric ให้เข้าใจว่าโมเดลแต่ละแบบต่างกันอย่างไร และ Regularization ช่วยอะไร
