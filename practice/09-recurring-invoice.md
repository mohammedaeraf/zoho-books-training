
# 📄 **Classroom Exercise: Creating a Recurring Invoice in Zoho Books**

---

### 🎯 **Objective**

Students will create a recurring invoice profile for a subscription-based customer, configure the billing cycle, and automate invoice generation.

---

## 🧑‍💼 **Scenario**

You run a **Design Software Agency** called **PixelCraft Studios**.
A customer, **The Art House**, has subscribed to your **Graphic Design Support Plan** for ₹3,000 per month.

---

## 📋 **Task Overview**

Create a **Recurring Invoice** profile for The Art House that:

- Automatically invoices the client monthly
- Starts from **1st August 2025**
- Is valid for **6 months**
- Automatically sends the invoice to the customer via email

---

## 🔧 **Steps to Follow in Zoho Books**

---

### 🔹 Step 1: Add the Customer

Go to:
📍 `Sales → Customers → + New`

**Customer Name**: The Art House
**Email**: [billing@arthouse.in](mailto:billing@arthouse.in)
**Payment Terms**: Net 15
**GST Treatment**: Unregistered Business _(for simplicity)_

---

### 🔹 Step 2: Add the Item

Go to:
📍 `Items → + New`

| Field         | Value                       |
| ------------- | --------------------------- |
| Item Name     | Graphic Design Support Plan |
| Type          | Service                     |
| Selling Price | ₹3,000                      |
| Tax           | No Tax _(for simplicity)_   |

---

### 🔹 Step 3: Create Recurring Invoice

Go to:
📍 `Sales → Recurring Invoices → + New`

| Field                   | Value                           |
| ----------------------- | ------------------------------- |
| Customer Name           | The Art House                   |
| Profile Name            | Monthly Design Plan – ArtHouse  |
| Repeat Every            | 1 Month                         |
| Start Date              | 01-August-2025                  |
| End Date                | 31-January-2026                 |
| Send email notification | ✅ Yes                          |
| Auto-charge             | ❌ No                           |
| Items                   | Graphic Design Support Plan × 1 |

Click **Save**.

---

## ✅ **Checklist**

| Task                              | Done (✔/✘) |
| --------------------------------- | ---------- |
| Customer created                  |            |
| Service item added                |            |
| Recurring invoice profile created |            |
| Email notifications enabled       |            |