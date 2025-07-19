# 🚀 Power BI Dashboard – Onboarding Performance & Aging Analysis

This is a freelance Power BI project built to help a team lead monitor onboarding requests (ORs), identify delays, and evaluate trends in aging across statuses and request types. The dashboard enables better visibility into request aging, ownership, and follow-ups.

## 📊 Dashboard Features

- **Stats Bar**: Shows total onboarding records, average aging days, and counts bucketed by aging:  
  - 🔴 Over 30 Days  
  - 🟡 20–30 Days  
  - 🟢 Under 19 Days  

- **Weekly ORs Trend**:  
  A 4-week stacked bar chart showing weekly request trends by aging buckets with average onboarding age displayed on top.

- **Aging Reason Pie Chart**:  
  Visual analysis of records that have a defined reason vs. those without, grouped by sub-status.

- **Onboarding Customer Type Breakdown**:  
  Bar chart and line graph showing total records and average aging by customer type (excluding Smartsource).

- **Custom Buckets for Flags**:  
  - “New” records flagged if aging > 1 business day  
  - “Ready for SAP Shell” flagged if aging > 3 business days  

- **Filters**:  
  - Record Type  
  - Request Type  
  - Owner  
  - CIDM Specialist

## 🧠 What I Learned

- Cleaning and transforming raw Excel data using **Power Query**  
- Fixing serial date formats (e.g. Excel number 45824 → actual date)  
- Using **DAX measures** for aging buckets, week-level calculations, and business logic  
- Creating dynamic, business-friendly visuals aligned with stakeholder requirements  
- Applying conditional formatting and filter panels for better UX

## 📁 Files

- `Onboarding_Dashboard.pbix` – main Power BI file
- `onboarding_mock_data.xlsx` – sample data used (scrubbed for privacy)
- `Screenshots/` – visual previews of dashboard elements

## 🛠 Tools Used

- Power BI (Desktop)
- Power Query (M)
- DAX
- Excel (for raw data input)

## 📌 Use Case

Designed for internal onboarding operations teams to monitor and act on delays, ensuring smoother go-lives and better ownership tracking.

---

## 📬 Contact

**Created by Huzaifa Moin**  
🧑‍💻 Junior Data Analyst | Freelance Projects  
📧 [huzaifamoin02@gmail.com](mailto:huzaifamoin02@gmail.com)

