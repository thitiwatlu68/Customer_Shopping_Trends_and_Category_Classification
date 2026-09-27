# Customer Shopping Trends and Category Classification
โครงงานวิเคราะห์เทรนด์การซื้อของผู้บริโภคและจำแนกหมวดหมู่สินค้าด้วยเทคนิค Machine Learning สำหรับวิชา 1145 201 Mathematics for Data Science

## 📊 สรุปภาพรวมโครงงาน (Project Summary)
* **CLO1 (Linear Algebra):** ทำ PCA พบว่า PC1 อธิบายความแปรปรวนข้อมูลได้ 70.81% และ PC2 อธิบายได้ 29.19% โดยตัวแปรยอดใช้จ่าย (Purchase Amount) มีอิทธิพลต่อข้อมูลมากที่สุด
* **CLO2 (Statistical Learning):** ข้อมูลกลุ่มสินค้ามีการกระจายตัวสมดุล และจากการวิเคราะห์กราฟ U-Curve พบว่าความซับซ้อนที่เหมาะสมที่สุดของโมเดล KNN อยู่ที่ค่า K = 50
* **CLO3 & CLO4 (Model Building & Selection):** พัฒนาแบบจำลองจำแนกประเภทข้อมูล 3 รูปแบบ และประเมินผลอย่างเป็นธรรมด้วย 5-Fold Cross-Validation พบว่า **Model 1 (Logistic Regression)** ให้ค่าความแม่นยำเฉลี่ยสูงสุดที่ **0.4218** 

## 📂 สมาชิกกลุ่ม (Group Members)
* นายฐิติวัฒน์ ลุณบุตร รหัสนักศึกษา 68114540814
---
**Acknowledgements:** แหล่งข้อมูลสาธารณะจาก Kaggle Dataset และระบบประมวลผล Google Colab
