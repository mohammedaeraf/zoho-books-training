# 🧾 **Classroom Exercise: Purchase Workflow in Zoho Books**

---

## 🎯 **Objective**

To understand and implement the **entire Purchase Workflow** in Zoho Books by:

1. Adding a Vendor
2. Enabling Inventory Tracking
3. Creating Items with Inventory
4. Creating and Managing a Purchase Order
5. Recording Delivery (Mark as Received)
6. Converting PO to Bill
7. Recording Payment
8. Viewing Reports

---

## 📘 **Scenario**

Your business, **Skyline IT Solutions**, needs to purchase 10 wireless keyboards from a vendor named **Tech Supplies India**.

You'll now set up everything in Zoho Books to track this transaction properly from order to payment.

---

## ✅ **Step-by-Step Tasks**

---

### 🔹 **1. Add a Vendor**

- Navigate to **Purchases → Vendors → + New**
- Enter:

  | Field         | Value                                                       |
  | ------------- | ----------------------------------------------------------- |
  | Vendor Name   | Tech Supplies India                                         |
  | Email         | [techsupplies@example.com](mailto:techsupplies@example.com) |
  | Phone         | 9876543210                                                  |
  | Payment Terms | Net 15 (create if not available)                            |

✅ Save the vendor.

---

### 🔹 **2. Enable Inventory Tracking**

- Go to **Settings → Items → Preferences**
- Enable the checkbox: ✅ **Track Inventory for Items**
- Save the changes

---

### 🔹 **3. Add an Item with Inventory**

- Go to **Items → + New**
- Enter:

  | Field             | Value             |
  | ----------------- | ----------------- |
  | Type              | Goods             |
  | Item Name         | Wireless Keyboard |
  | Rate              | ₹1,200            |
  | Inventory Account | Inventory Asset   |
  | Opening Stock     | 0                 |
  | Reorder Point     | 5                 |
  | Unit              | Nos               |

✅ Save the item.

---

### 🔹 **4. Create a Purchase Order**

- Go to **Purchases → Purchase Orders → + New**

- Enter:

  | Field         | Value               |
  | ------------- | ------------------- |
  | Vendor        | Tech Supplies India |
  | Date          | Today’s date        |
  | Delivery Date | 7 days from today   |
  | Item          | Wireless Keyboard   |
  | Quantity      | 10                  |
  | Rate          | ₹1,200              |

- Add Notes: “Required for new office setup”

- Save the Purchase Order

✅ Mark PO as **Issued**

---

### 🔹 **5. Mark as Received**

- Open the Purchase Order
- Click **More → Mark as Received**
- Inventory will now show the 10 keyboards as **received**

---

### 🔹 **6. Convert to Bill**

- Open the same Purchase Order
- Click **Convert to Bill**
- Check item and amount: ₹12,000
- Save the bill

✅ The vendor now needs to be paid.

---

### 🔹 **7. Record Payment**

- Open the Bill
- Click **Record Payment**
- Enter:

  | Field            | Value               |
  | ---------------- | ------------------- |
  | Amount Paid      | ₹12,000             |
  | Paid Through     | Bank                |
  | Payment Date     | Today’s date        |
  | Reference Number | TXN987654           |
  | Notes            | Payment for PO #001 |

✅ Save

---

### 🔹 **8. View Reports**

- Go to **Reports → Purchases → Purchase Order Details**

  - View PO status, vendor, and amount

- Go to **Reports → Inventory Summary**

  - Confirm stock shows 10 Wireless Keyboards

- Go to **Reports → Payments Made**

  - Verify payment of ₹12,000 to **Tech Supplies India**

---

## ✨ **Part 2**

> Add another item — **Wireless Mouse**
> Create a **Purchase Order** of 20 units at ₹500 each from the same vendor.
> Complete the full workflow again (PO → Received → Bill → Payment)
