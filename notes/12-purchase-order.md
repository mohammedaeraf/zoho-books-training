## 📘 Tutorial: Purchase Orders in Zoho Books

---

### ✅ What is a Purchase Order?

A **Purchase Order (PO)** is a formal document you send to a vendor to request goods or services. It includes:

* Item details
* Quantity
* Price
* Terms and conditions

Once accepted, it becomes a legally binding agreement.

---

## 🧭 Where to Create a Purchase Order

1. Log in to **Zoho Books**
2. Go to **Purchases → Purchase Orders**
3. Click **+ New Purchase Order**

---

## 🛠️ Steps to Create a Purchase Order

1. **Select Vendor** – Choose from your existing vendor list
2. **Purchase Order Date** – Auto-fills to today’s date
3. **Delivery Date** – Optional
4. **Items** – Add the products or services to be ordered

   * Quantity
   * Rate
   * Tax (if applicable)
5. Add optional Notes or Terms & Conditions
6. Click **Save as Draft** or **Save and Send**

---

## 🔁 What Happens at Each Stage?

Zoho Books allows you to **track the PO’s lifecycle**, and each stage affects **inventory** differently:

---

### 1. **Draft Stage**

* No action on inventory
* PO is just saved internally

---

### 2. **Mark as Issued**

* PO is officially sent to the vendor
* Inventory is **still unaffected**
* Status: `Issued`

---

### 3. **Mark as Received**

* Indicates the goods have been physically received
* Inventory is **increased** based on the item quantities
* Status: `Received`
  ✅ This is the first stage that **affects stock levels**

---

### 4. **Convert to Bill**

* Converts the PO into a Bill for payment
* Financial record of **Accounts Payable** is created
* Inventory remains **unchanged** here because it was already updated at the **Received** stage

---

### ✅ Summary: Inventory Impact by PO Stage

| PO Stage          | Inventory Updated? |
| ----------------- | ------------------ |
| Draft             | ❌ No               |
| Issued            | ❌ No               |
| Received          | ✅ Yes              |
| Converted to Bill | ❌ Already updated  |

---

## 🤔 Do You Need Purchase Orders for Services?

**No, Purchase Orders are optional for services** — but can be used if you want a record of what service was ordered and agreed upon.

> 📝 For example, if you hire a freelance **consultant** or **trainer**, you may:

* Create a **Service Item** (e.g., "Training Session", "Consulting - 4 hours")
* Raise a PO for internal tracking or for client/vendor agreement

---

## 💼 How to Create a Bill for a Consultant (Service Purchase)

If no PO is needed, you can directly create a **Bill**:

1. Go to **Purchases → Bills**
2. Click **+ New Bill**
3. Choose the **Vendor** (e.g., Consultant Name)
4. In the **Item Details**:

   * Select **Service Item** (e.g., “Consulting Fee”)
   * Quantity (e.g., 5 hours)
   * Rate (e.g., ₹1,000/hour)
   * Total = ₹5,000
5. Add any taxes if applicable
6. Save the bill

📌 Note: Since this is a **service**, there is **no impact on inventory**

---

## 🎯 Best Practices

* Use Purchase Orders for **physical goods** to track stock movement and manage vendor agreements
* Use Bills directly for **service-based vendors**
* Use **"Mark as Received"** carefully, as it **adds to inventory**
* Maintain a clear PO-to-Bill process to prevent duplicate entries