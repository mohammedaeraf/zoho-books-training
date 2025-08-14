# 📘 Classroom Tutorial: How Zoho Books Calculates GST Payable with ITC Adjustment

## 🎯 Learning Objective

By the end of this tutorial, students will be able to:

* Understand the role of Input Tax Credit (ITC) in GST calculation.
* View GST reports in Zoho Books.
* Identify the steps Zoho Books follows to arrive at the net GST payable.
* Verify calculations using sample transactions.

---

## 1️⃣ **Introduction to GST & ITC in Zoho Books**

* **GST Payable** = **GST on Sales (Output Tax)** − **Input Tax Credit (ITC)**.
* **Output Tax**: Tax collected from customers on sales.
* **ITC**: Tax paid on purchases, which can be deducted from Output Tax.

💡 *Example:*
If Output GST = ₹50,000 and ITC = ₹30,000 → GST Payable = ₹20,000.

---

## 2️⃣ **Step 1: Record Sales & Purchases with GST**

1. Log in to **Zoho Books**.
2. Record at least one sale with GST applied.
3. Record a purchase with GST paid.
4. Ensure GST is correctly assigned to each line item.

📷 *\[Screenshot Placeholder: Sales entry screen with GST field]*

---

## 3️⃣ **Step 2: Access GST Summary**

1. Navigate to:
   **Reports → Taxes → GST Summary**.
2. Select the reporting period (e.g., April 2025).
3. Review:

   * **GST Collected** (Sales)
   * **GST Paid** (Purchases)
   * **Net Tax Payable** after ITC adjustment.

📷 *\[Screenshot Placeholder: GST Summary screen]*

---

## 4️⃣ **Step 3: Understanding Zoho Books’ Calculation**

Zoho Books automatically:

1. **Adds up Output Tax** from all sales invoices in the period.
2. **Adds up Input Tax** from all purchase bills in the period.
3. **Adjusts Output Tax with ITC**:

   * **If Output Tax > ITC** → Pay the difference.
   * **If ITC > Output Tax** → Carry forward ITC to next period.

📌 Formula:

```
GST Payable = Output Tax – ITC
```

---

## 5️⃣ **Step 4: Example Calculation**

**Sales:**

* Invoice 1: ₹1,00,000 + GST (18%) = ₹18,000
* Invoice 2: ₹50,000 + GST (18%) = ₹9,000
  **Total Output Tax:** ₹27,000

**Purchases:**

* Bill 1: ₹40,000 + GST (18%) = ₹7,200
* Bill 2: ₹30,000 + GST (18%) = ₹5,400
  **Total ITC:** ₹12,600

**Calculation:**

```
Output Tax = ₹27,000
ITC = ₹12,600
Net GST Payable = ₹27,000 – ₹12,600 = ₹14,400
```

📷 *\[Screenshot Placeholder: GST calculation table in Zoho Books]*

---

## 6️⃣ **Step 5: Filing the Return**

1. From the **GST Summary**, click **Prepare Return**.
2. Review:

   * Sales
   * Purchases
   * ITC
   * Net Tax Payable
3. Submit to GST Portal via Zoho Books (if API connected) or manually.

---

## 7️⃣ **Quick Tips for Classroom**

* Always ensure **GSTIN** is entered for B2B customers/suppliers.
* Verify GST rates in item master before transactions.
* Check **unmatched transactions** before filing.
* Explain **carry forward ITC** scenarios.

---

## ✅ Practice Exercise

**Task:**
Create:

1. 2 sales invoices (₹50,000 and ₹1,00,000 @ 18% GST).
2. 2 purchase bills (₹30,000 and ₹40,000 @ 18% GST).
   Then:

* View GST Summary.
* Verify Zoho Books’ GST Payable matches manual calculation.
