# 📊 IT Support Ticket Desk - Business Intelligence Dashboard

<div align="center">

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/Data_Analysis-DAX-blue?style=for-the-badge)
![Analytics](https://img.shields.io/badge/Business%20Intelligence-Executive%20KPIs-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<p align="center">
  <b>لوحة بيانات تنفيذية وتحليلية متقدمة في Power BI لمراقبة أداء مكتب الدعم الفني وتقنية المعلومات (IT Service Desk)، مع قياس مؤشرات الأداء الرئيسية (KPIs)، الالتزام باتفاقيات مستوى الخدمة (SLA)، وكفاءة حل التذاكر.</b>
</p>

</div>

---

## 📈 Overview | نظرة عامة

يقدم مشروع **IT Support Ticket Desk Analytics** تحليلاً شاملاً وتفاعلياً لبيانات التذاكر التقنية داخل المؤسسات. تم تطوير لوحة التحكم باستخدام **Microsoft Power BI** لتمكين مديري تكنولوجيا المعلومات وصناع القرار من تقييم ضغط العمل، التعرف على المشكلات المتكررة، تحسين زمن الاستجابة، ورفع معدلات رضا العملاء (CSAT).

---

## 🎯 Key KPIs & Metrics | مؤشرات الأداء الرئيسية

- 🎫 **Total Volume & Resolution Rate:** تتبع إجمالي التذاكر المفتوحة والمغلقة ومعدل الإنجاز العام.
- ⏱️ **First Contact Resolution (FCR) & MTTR:** حساب متوسط وقت الحل (Mean Time to Resolve) وسرعة الاستجابة الأولى.
- 🎯 **SLA Compliance Rate (%):** قياس مدى الالتزام باتفاقيات مستوى الخدمة بحسب درجة الأهمية (Critical, High, Medium, Low).
- 👥 **Agent & Team Performance:** تقييم إنتاجية مهندسي الدعم الفني وتوزيع أحمال العمل بين الأقسام.
- ⭐ **Customer Satisfaction (CSAT):** تحليل تقييمات المستخدمين ومقارنتها بنوع الخدمة ومستوى الإلحاح.

---

## 🛠️ Data Modeling & DAX | نمذجة البيانات والـ DAX

- **Star Schema Modeling:** بناء نموذج بيانات علائقي يربط جدول الوقائع (Fact Table) بجداول الأبعاد (Dimensions: Date, Agents, Priority, Categories, SLA).
- **Power Query ETL:** تنظيف وتجهيز البيانات، إزالة القيم الشاذة، وتوحيد المعايير الزمنية.
- **Advanced DAX Measures:**
  - Dynamic Time Intelligence (MTD, QTD, YTD).
  - SLA Breach Percentage.
  - Priority Weighted Resolution Index.

---

## 📂 Project Files | ملفات المشروع

```plaintext
data-Dashboard-/
├── IT_Support_Ticket_Desk.pbix           # تقرير Power BI التفاعلي مع كافة الصفحات والرسوم البيانية
├── IT_Support_Ticket_Desk_English.xlsx   # مجموعة البيانات المصدرية الكاملة (Cleaned Excel Dataset)
├── .gitignore                            # استبعاد ملفات النظام والمخلفات المؤقتة
└── README.md                             # التوثيق الشامل للوحة البيانات
```

---

## 🚀 How to View & Explore | طريقة التشغيل والاستعراض

1. قم بتحميل وتثبيت **[Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/)**.
2. افتح ملف [`IT_Support_Ticket_Desk.pbix`](./IT_Support_Ticket_Desk.pbix) مباشرة داخل Power BI Desktop.
3. تفاعل مع الـ Slicers والفلاتر الزمنية لاستعراض التحليلات عبر مختلف الأقسام والمستويات.

---

## 👨‍💻 Developer & Data Analyst

Developed with precision by **[Mohamed Shaaban (momoshworks)](https://github.com/momoshworks)**  
Faculty of Artificial Intelligence — Delta University for Science & Technology.

---

## 📄 License
This project is open-source under the MIT License.
