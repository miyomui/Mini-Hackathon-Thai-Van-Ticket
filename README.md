# 🚐 Thai Van Ticket Data Analysis & Dashboard

[English Version Below](#english-version)

---

<a name="thai-version"></a>
## 🇹🇭 เวอร์ชั่นภาษาไทย

### ภาพรวมโปรเจกต์
โปรเจกต์นี้เป็นการวิเคราะห์ข้อมูลการจองตั๋วรถตู้ (Thai Van Ticket) จากกิจกรรม Mini Hackathon เพื่อค้นหาข้อมูลเชิงลึกทางธุรกิจ (Business Insights) และนำเสนอผ่าน **Interactive Dashboard** ด้วย Power BI วัตถุประสงค์คือเพื่อให้ผู้บริหารสามารถติดตามภาพรวมธุรกิจ วิเคราะห์ยอดขาย ค้นหาจุดรั่วไหลของรายได้ และเข้าใจพฤติกรรมลูกค้าได้ดียิ่งขึ้น เป็นการแข่งขันภายในมหาวิทยาลับกรุงเทพ
* **ระยะเวลาดำเนินโปรเจกต์:** 1 พฤศจิกายน 2568 - 9 พฤศจิกายน 2568
* [**รายละเอียดและข้อมูลเพิ่มเติมเกี่ยวกับโปรเจกต์**](https://www.canva.com/design/DAG3WLG0FnY/i0SQTbZA6AOtN2kT_vD8uw/edit?utm_content=DAG3WLG0FnY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

### เครื่องมือที่ใช้
* **Python (Jupyter Notebook):** สำหรับการเตรียมข้อมูล (Data Cleaning) และวิเคราะห์เบื้องต้น
* **SQL:** สำหรับการดึงข้อมูล (Query) และสร้างตารางสรุปผล
* **Power BI:** สำหรับการสร้าง Dashboard และ Data Visualization

### โครงสร้างไฟล์
* `Mini Hackathon Thai Van Ticket.ipynb`: ไฟล์ Notebook แสดงขั้นตอนการวิเคราะห์ด้วย Python/SQL
* `Mini Hackathon Thai Van Ticket.pbix`: ไฟล์งาน Dashboard Power BI ฉบับสมบูรณ์
* `images/`: โฟลเดอร์เก็บรูปภาพ Screenshot ของ Dashboard

---

### ตัวอย่าง Dashboard

#### 1. Executive Summary (ภาพรวมผู้บริหาร)
หน้ารวม KPI สำคัญ เช่น รายได้จริง, จำนวนตั๋วที่ขายได้ และอัตราการจองล้มเหลว เพื่อให้เห็นสถานภาพของธุรกิจได้อย่างรวดเร็ว
![Executive Summary](image/1_summary.jpg)

#### 2. Sales & Revenue Deep Dive (เจาะลึกยอดขาย)
วิเคราะห์เจาะลึกว่ารายได้มาจากสถานะไหน และช่วงเวลาใดขายดีที่สุด
![Sales Analysis](image/2_sales.jpg)

#### 3. Operational Health & Leaks (จุดรั่วไหลของรายได้)
ติดตามยอดการจองที่ยังไม่ชำระเงิน (Pending) หรือล้มเหลว เพื่อหาแนวทางแก้ไขและเพิ่มรายได้
![Operational Health](image/3_operational.jpg)

#### 4. Customer Behavior (พฤติกรรมลูกค้า)
วิเคราะห์พฤติกรรมผู้ซื้อ เช่น ระยะเวลาการจองล่วงหน้า และจำนวนที่นั่งต่อการจอง
![Customer Behavior](image/4_customer.jpg)

<br>

---

<a name="english-version"></a>
## 🇬🇧 English Version

### Project Overview
This project analyzes van ticket booking data (Thai Van Ticket) from a Mini Hackathon event. The goal is to uncover business insights and present them through an **Interactive Dashboard** using Power BI, enabling executives to track business performance, analyze sales, identify revenue leaks, and understand customer behavior.

### Tools Used
* **Python (Jupyter Notebook):** For data preparation (cleaning) and initial analysis.
* **SQL:** For data querying and creating aggregated tables.
* **Power BI:** For Dashboard creation and Data Visualization.

### File Structure
* `Mini Hackathon Thai Van Ticket.ipynb`: Notebook file demonstrating Python/SQL analysis steps.
* `Mini Hackathon Thai Van Ticket.pbix`: The complete Power BI Dashboard file.
* `images/`: Folder containing dashboard screenshots.

---

### Dashboard Showcase

#### 1. Executive Summary
A high-level view of key KPIs such as Confirmed Revenue, Tickets Sold, and Failure Rate for quick business health assessment.
![Executive Summary](image/1_summary.jpg)

#### 2. Sales & Revenue Deep Dive
In-depth analysis of revenue status, identifying top-selling products and peak sales periods.
![Sales Analysis](image/2_sales.jpg)

#### 3. Operational Health & Leaks
Tracks pending or failed bookings to identify operational issues and potential revenue recovery opportunities.
![Operational Health](image/3_operational.jpg)

#### 4. Customer Behavior
Analyzes customer booking patterns, including booking lead time and party size preferences.
![Customer Behavior](image/4_customer.jpg)
<a name="english-version"></a>
