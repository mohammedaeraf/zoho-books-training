# 📄 **Classroom Exercise: Creating and Applying a Credit Note in Zoho Books**

### 🎯 **Objective**

Students will learn how to:

* Create a credit note for a returned item
* Link the credit note to an existing invoice
* Apply the credit to reduce the customer’s outstanding balance

---

## 🧑‍💼 **Scenario**

Your company, **BrightTech Solutions**, sold 5 computer monitors to **VisionWare Pvt. Ltd.** for ₹10,000 each.
However, 1 monitor was returned due to a dead pixel issue. You need to issue a **credit note** for the returned item.

---

## 📋 **Instructions for Students**

---

### 🔹 Step 1: Add a Customer

Go to:
📍 `Sales → Customers → + New`

| Field         | Value                                                   |
| ------------- | ------------------------------------------------------- |
| Customer Name | VisionWare Pvt. Ltd.                                    |
| Email         | [accounts@visionware.in](mailto:accounts@visionware.in) |
| GST Treatment | Registered Business - Regular                           |

---

### 🔹 Step 2: Add an Item

Go to:
📍 `Items → + New`

| Field           | Value           |
| --------------- | --------------- |
| Item Name       | 24-inch Monitor |
| Type            | Goods           |
| Selling Price   | ₹10,000         |
| Tax             | 18% GST         |
| Track Inventory | ✅ Yes           |

---

### 🔹 Step 3: Create a Sales Invoice

Go to:
📍 `Sales → Invoices → + New`

| Field         | Value                |
| ------------- | -------------------- |
| Customer Name | VisionWare Pvt. Ltd. |
| Date          | 01-Aug-2025          |
| Item          | 24-inch Monitor × 5  |
| Price         | ₹10,000 per unit     |
| Tax           | 18% GST              |

💡 Save the invoice.

---

### 🔹 Step 4: Create a Credit Note

Go to:
📍 `Sales → Credit Notes → + New`

| Field          | Value                               |
| -------------- | ----------------------------------- |
| Customer Name  | VisionWare Pvt. Ltd.                |
| Linked Invoice | Select the invoice you just created |
| Item           | 24-inch Monitor × 1                 |
| Reason         | “Returned – Dead Pixel”             |

💡 Save the credit note.

---

### 🔹 Step 5: Apply the Credit Note

1. Open the same invoice
2. Click **“Apply Credit”**
3. Select the newly created credit note
4. Apply ₹10,000 (excluding GST or full amount if including)

💡 Save the invoice with reduced balance.

---

## ✅ **Checklist**

| Task                      | Done (✔/✘) |
| ------------------------- | ---------- |
| Customer created          |            |
| Item added                |            |
| Invoice created           |            |
| Credit Note created       |            |
| Credit applied to invoice |            |

---

## 🧠 Discussion Questions

1. What happens to the original invoice total after applying the credit?
2. Can a credit note be issued without linking it to an invoice?
3. How would this affect inventory if tracking is enabled?