# 📄 **Practice Worksheet: Sales Workflow in Zoho Books**

### 🧑‍🎓 **Objective**:

Create a complete sales cycle in Zoho Books — starting with a **Quote**, converting to a **Sales Order**, then to an **Invoice**, and recording the **payment received**.

---

## 🛒 **Scenario**

You are a salesperson at **TechNest Solutions**, a business that sells computer accessories.

A customer, **Brightline Enterprises**, has contacted you for the following items:

| Item Name         | Quantity | Rate (₹) | Tax (%) | Item Type |
| ----------------- | -------- | -------- | ------- | --------- |
| HP Wired Mouse    | 5        | ₹500     | 18%     | Goods     |
| Logitech Keyboard | 3        | ₹1,200   | 18%     | Goods     |

---

## 📝 **Instructions**

Follow these steps in **Zoho Books**:

---

### 🔹 **Step 1: Add Customer**

* Go to **Sales → Customers → + New**
* Customer Name: `Brightline Enterprises`
* Email: `accounts@brightline.in`
* Payment Terms: `Net 15`
* GST Treatment: `Registered Business - Regular`
* GSTIN: `29AAHCB7856M1Z3` *(optional for demo)*

---

### 🔹 **Step 2: Add Items**

Add the two items below via **Items → + New**:

#### ➤ Item 1: HP Wired Mouse

* Type: `Goods`
* Selling Price: ₹500
* Tax: GST 18%
* Inventory Tracking: Enable
* Opening Stock: 25 units

#### ➤ Item 2: Logitech Keyboard

* Type: `Goods`
* Selling Price: ₹1,200
* Tax: GST 18%
* Inventory Tracking: Enable
* Opening Stock: 15 units

---

### 🔹 **Step 3: Create a Quote**

Go to **Sales → Quotes → + New**

* Customer: `Brightline Enterprises`
* Quote Date: Today
* Items:

  * HP Wired Mouse × 5
  * Logitech Keyboard × 3
* Apply appropriate tax
* Add Notes: *“Valid for 7 days”*

🟢 **Save and Send** or **Mark as Accepted**

---

### 🔹 **Step 4: Convert Quote to Sales Order**

* Open the Quote
* Click **More → Convert to Sales Order**
* Review item quantities and totals
* Save the Sales Order

🟢 Optionally mark it as **Confirmed or Delivered**

---

### 🔹 **Step 5: Convert Sales Order to Invoice**

* Open the Sales Order
* Click **More → Convert to Invoice**
* Confirm date, payment terms
* Save and Send Invoice to customer

---

### 🔹 **Step 6: Record Payment**

* Open the Invoice
* Click **Record Payment**
* Mode: UPI
* Amount: Full
* Payment Date: Today
* Reference: UPI-TXN-89674

---

## ✅ **Checklist**

| Task                                 | Status (✔/✘) |
| ------------------------------------ | ------------ |
| Customer created                     |              |
| Items added with inventory tracking  |              |
| Quote created and marked as accepted |              |
| Sales Order generated                |              |
| Invoice generated from Sales Order   |              |
| Payment recorded                     |              |
