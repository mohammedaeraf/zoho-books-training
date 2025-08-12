## **Practice Sheet – End-to-End Purchase & Sales Workflow in Zoho Books**

### **Learning Objective**

By completing this exercise, students will:

* Add vendors and customers
* Manage inventory items
* Record purchases (PO → Bill → Payment)
* Record sales (Quote → Sales Order → Invoice → Payment)
* Track inventory changes through each stage

---

## **Scenario**

You run a business called **TechPoint Solutions** selling laptops and accessories.

* You purchase goods from your vendor **Digital World Pvt Ltd**.
* You then sell these goods to your customer **Neon Enterprises**.

---

## **Part A – Purchase Workflow**

### **1. Add Vendor**

* Name: **Digital World Pvt Ltd**
* Payment Terms: **Net 15**
* GSTIN: **27ABCDE1234F1Z5**
* Custom Field: **Supplier Code** – DW001

---

### **2. Enable Inventory**

* Go to **Settings → Items → Enable Inventory Tracking**.

---

### **3. Add Items**

1. **Dell Inspiron 14 Laptop**

   * SKU: **D14-INS**
   * Selling Price: ₹45,000
   * Purchase Price: ₹40,000
   * Opening Stock: 0
   * GST: 18%

2. **Logitech Wireless Mouse**

   * SKU: **LM-WLS**
   * Selling Price: ₹1,200
   * Purchase Price: ₹900
   * Opening Stock: 0
   * GST: 18%

---

### **4. Create Purchase Order (PO)**

* Vendor: **Digital World Pvt Ltd**
* Items:

  * Dell Inspiron 14 Laptop – Qty 5
  * Logitech Wireless Mouse – Qty 10
* Save and Mark as Issued.

---

### **5. Mark as Received**

* Receive full quantity for both items.
* Observe stock update after this step.

---

### **6. Convert to Bill**

* Convert PO to Bill.
* Record payment (full payment from Bank account).

---

## **Part B – Sales Workflow**

### **1. Add Customer**

* Name: **Neon Enterprises**
* Payment Terms: **Net 7**
* GSTIN: **29ABCDE6789L1Z7**

---

### **2. Create Quote**

* Customer: **Neon Enterprises**
* Items:

  * Dell Inspiron 14 Laptop – Qty 2
  * Logitech Wireless Mouse – Qty 4
* Send Quote to customer.

---

### **3. Convert Quote to Sales Order**

* Convert once customer approves.

---

### **4. Convert Sales Order to Invoice**

* Convert and send Invoice.
* Record **partial payment** from customer.

---

### **5. Check Inventory**

* Verify that inventory decreased based on sales quantity.

---

## **Reports to Review**

* **Purchase Report** → Bills by Vendor
* **Sales Report** → Sales by Customer
* **Inventory Report** → Item Details (Stock levels before and after transactions)

---

## **Discussion Questions**

1. How does marking a PO as Received affect inventory?
2. Why might you use a Sales Order instead of directly creating an Invoice?
3. How does partial payment appear in the Customer Statement?