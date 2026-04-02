# 📄 **Practice Worksheet: Sales & Inventory Workflow in Zoho Books**

---

### 🧑‍🎓 **Objective**:

Create a complete **sales workflow with inventory tracking** in Zoho Books — starting with a **Quote**, converting to a **Sales Order**, then to an **Invoice**, and recording the **payment received**, while monitoring **stock movement (including committed stock)**.

---

## 🛒 **Scenario**

You are a salesperson at **DigitalHub Traders**, a business that sells office and tech accessories.

A customer, **Skyline Corp**, has requested the following items:

| Item Name          | Quantity | Rate (₹) | Item Type |
| ------------------ | -------- | -------- | --------- |
| Dell USB Keyboard  | 4        | ₹900     | Goods     |
| Portronics Speaker | 2        | ₹1,500   | Goods     |

---

## 📝 **Instructions**

Follow these steps in **Zoho Books**:

---

### 🔹 **Step 1: Add Customer**

* Go to **Sales → Customers → + New**
* Customer Name: `Skyline Corp`
* Email: `accounts@skylinecorp.in`
* Payment Terms: `Net 15`

---

### 🔹 **Step 2: Add Items (Inventory Focus)**

Add the two items below via **Items → + New**:

#### ➤ Item 1: Dell USB Keyboard

* Type: `Goods`
* Selling Price: ₹900
* Inventory Tracking: Enable
* Opening Stock: 20 units
* Opening Stock Rate: ₹700

#### ➤ Item 2: Portronics Speaker

* Type: `Goods`
* Selling Price: ₹1,500
* Inventory Tracking: Enable
* Opening Stock: 10 units
* Opening Stock Rate: ₹1,100

✅ Ensure stock is visible in item list

---

### 🔹 **Step 3: Verify Opening Stock**

* Go to **Items → Item List**
* Check:

  * Available Quantity
  * Inventory Value

---

### 🔹 **Step 4: Create a Quote**

Go to **Sales → Quotes → + New**

* Customer: `Skyline Corp`
* Quote Date: Today
* Items:

  * Dell USB Keyboard × 4
  * Portronics Speaker × 2
* Add Notes: *“Valid for 5 days”*

🟢 Save and mark as **Accepted**

---

### 🔹 **Step 5: Convert Quote to Sales Order**

* Open the Quote
* Click **More → Convert to Sales Order**
* Save the Sales Order

🟢 Mark as **Confirmed**

---

### 🔹 **Step 6: Check Committed Stock (Important)**

After creating the Sales Order:

* Go to **Items → Item List**
* Open each item and check:

📌 **Committed Stock should be updated:**

* Dell USB Keyboard → 4 units committed
* Portronics Speaker → 2 units committed

👉 This means stock is **reserved but not yet reduced**

---

### 🔹 **Step 7: Convert Sales Order to Invoice**

* Open the Sales Order
* Click **More → Convert to Invoice**
* Save and Send Invoice

---

### 🔹 **Step 8: Record Payment**

* Open the Invoice
* Click **Record Payment**
* Mode: UPI
* Amount: Full
* Reference: UPI-TXN-45218

---

### 🔹 **Step 9: Check Inventory Impact (Very Important)**

After invoicing:

* Go to **Items → Item List**
* Verify:

📌 **Stock should reduce and committed stock cleared**

Expected Stock:

* Dell USB Keyboard → 20 - 4 = **16 units**
* Portronics Speaker → 10 - 2 = **8 units**

---

## ✅ **Checklist**

| Task                             | Status (✔/✘) |
| -------------------------------- | ------------ |
| Customer created                 |              |
| Items created with opening stock |              |
| Opening stock verified           |              |
| Quote created and accepted       |              |
| Sales Order created              |              |
| Committed stock verified         |              |
| Invoice generated                |              |
| Payment recorded                 |              |
| Stock reduced correctly          |              |