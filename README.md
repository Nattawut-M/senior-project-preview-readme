# Senior Project : Web Assessment COVID-19

สร้าง[เว็บแอพพลิเคชันประเมินความเสี่ยงไวรัสโคโรนาสายพันธุ์ใหม่ 2019 (COVID-19)](https://covid-assessment.azurewebsites.net) ด้วยวิธีแบบ Classification

> ตอนนี้เว็บ**ไม่สามารถใช้งานได้** เนื่องจาก Azure Subscription หมดแล้ว

---

## Tools

1. React.js (Javascript)
2. Express.js (Javascript)
3. Sequelize (SQL)
4. Azure (Azure Web Services, Azure Machine Learning, Azure Database)

--- 

## Preview

### หน้าสำหรับผู้ใช้ (User)

1. หน้าแรก (1) บอกจำนวนผู้ติดเชื้อรายวัน

![หน้าแรก](/images/home-covid-daily.png)

2. หน้าแรก (2) บอกยอดผู้ติดเชื้อย้อนหลัง 30 วัน แบบกราฟเส้น

![หน้าแรก](/images/home-line-chart.png)

3. หน้าแรก (3) บอกรายละเอียดแยกแต่ละจังหวัด แบบกราฟแท่ง

![หน้าแรก](/images/home-province-stat.png)

4. หนัาข่าวสาร

![ข่าวสาร](/images/news.png)

5. หน้าเข้าสู่ระบบ

![เข้าสู่ระบบ](/images/login.png)

6. หน้าสมัครสมาชิก

![สมัครสมาชิก](/images/register.png)

7. หน้าฟอร์มการประเมินความเสี่ยง (1)

![ข่าวสาร](/images/form-assessment.png)

8. หน้าฟอร์มการประเมินความเสี่ยง (2) พร้อมผลลัพธ์ที่ตอบกลับมาจาก **Azure Machine Learning**

![ข่าวสาร](/images/result-prediction.png)

9. หน้าประวัติการประเมินความเสี่ยง

![ข่าวสาร](/images/history-prediction.png)

10. หน้าผู้ใช้งานตั้งค่าบัญชี (1) เปลี่ยนข้อมูลส่วนตัว

![ข่าวสาร](/images/user-setting-info.png)

11. หน้าผู้ใช้งานตั้งค่าบัญชี (2) เปลี่ยนรหัสผ่าน

![ข่าวสาร](/images/user-settings-passwors.png)

### หน้าสำหรับผู้ดูแลระบบ (Admin)

1. หน้าภาพรวมระบบ (1)

![dashboard-1](/images/admin-dashboard-1.png)

2. หน้าภาพรวมระบบ (2)

![dashboard-1](/images/admin-dashboard-2.png)

3. หน้าจัดการข่าวสาร (1)

![dashboard-1](/images/admin-news-1.png)

4. หน้าจัดการข่าวสาร (2)

![dashboard-1](/images/admin-news-2.png)

5. หน้าจัดการผู้ใช้ (1)

![dashboard-1](/images/admin-user-1.png)

6. หน้าจัดการผู้ใช้ (2)

![dashboard-1](/images/admin-user-2.png)
