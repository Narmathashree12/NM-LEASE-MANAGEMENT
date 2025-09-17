# NM-LEASE-MANAGEMENT

## 📌 Project Overview

The **Lease Management System** is developed on **Salesforce** to simplify and automate the management of property lease agreements. The system addresses common challenges such as manual property tracking, tenant management, payment processing, and communication.

It streamlines the entire lease lifecycle—from contract creation to payment tracking—while ensuring accurate data, timely notifications, and better financial reporting.

---

## 🎯 Objectives & Business Goals

* **Improve Operational Efficiency**
  Automate manual lease processes, reduce administrative tasks, and optimize workflows.
* **Enhance Data Accuracy & Centralization**
  Store tenant, property, and payment data in Salesforce with real-time updates.
* **Increase Rent Collection & Timely Payments**
  Automate reminders and overdue notifications to reduce late payments.
* **Improve Tenant Satisfaction & Communication**
  Provide automated emails for lease renewals, payments, and approvals.
* **Better Financial Visibility & Reporting**
  Enable real-time dashboards to track occupancy, payments, and lease expirations.

---

## ⚙️ Development in Salesforce

* **Custom Objects Created:** Property, Tenant, Lease, Payment
* **Custom Tabs:** For managing each object
* **Lightning App:** "Lease Management" with navigation items & profiles
* **Fields & Validation Rules:** To ensure data consistency in all objects
* **Email Templates:** For tenant leaving, approvals, rejections, and monthly payment reminders
* **Approval Processes:** To handle vacant property and tenant approvals
* **Apex Triggers & Classes:**

  * `test` trigger to prevent duplicate tenant-property records
  * `testHandler` class to handle validations
* **Flows:** Record-triggered flows for monthly payment reminders
* **Scheduler Class:** `MonthlyEmailScheduler` to send rent reminder emails automatically

---

## 🧪 Testing

* **Validation Rule Testing** – Ensured incorrect/duplicate entries are blocked.
* **Trigger Testing** – Prevented duplicate tenant-property assignments.
* **Approval Process Testing** – Notifications & email approvals/rejections verified.
* **Performance Testing** – Checked for accuracy and efficiency in workflows.

---

## ✅ Results

* Automated **end-to-end lease management process**.
* Reduced manual errors and redundant data entry.
* Improved **communication between tenants and administrators**.
* Enhanced operational efficiency and tenant satisfaction.

---

## 📖 Documentation

For detailed workflows, screenshots, and code samples, see the full project report:
**`SF - LEASE MANAGEMENT.docx`**

---

## 👥 Team Members

* **Team Leader:** Narmathashree T ([2326kb29@kgcas.com](mailto:2326kb29@kgcas.com))
* **Team Member:** Nishanth C ([2326kb29@kgcas.com](mailto:2326kb29@kgcas.com))
* **Team Member:** Nithish S ([2326kb29@kgcas.com](mailto:2326kb29@kgcas.com))
* **Team Member:** Nithya Sree ([2326kb29@kgcas.com](mailto:2326kb29@kgcas.com))

---

## 📜 Conclusion

The Lease Management System, built on Salesforce, successfully automates the leasing process, providing transparency, better financial tracking, and scalability for future growth.

---

