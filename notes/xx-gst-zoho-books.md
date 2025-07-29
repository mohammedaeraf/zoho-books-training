# 📘 ** GST in Zoho Books (India)**

---

## ✅ **What is GST?**

**Goods and Services Tax (GST)** is a unified indirect tax system applicable across India. It replaces multiple taxes like VAT, Service Tax, and Excise Duty.

In Zoho Books, GST features allow businesses to:

* Create GST-compliant invoices
* Automatically calculate CGST, SGST, IGST
* Track Input Tax Credit (ITC)
* Generate GSTR-1, GSTR-3B, and other reports
* Export data for filing on the GSTN portal

---

## 🛠️ **Step 1: Enable GST in Zoho Books**

### 🔹 How to Enable:

1. Go to ⚙️ **Settings** → **Taxes**
2. Click **Enable GST**
3. Enter the following details:

   * **GSTIN** (your business’s 15-digit GST number)
   * **Place of Business** (State)
   * **Tax Basis** (Accrual or Cash)
   * **Effective Date**

> ✅ *Tip: If you operate in multiple states, you can add multiple GSTINs for each branch.*

---

## 🧾 **Step 2: Add GST Details to Contacts**

When you create a **Customer** or **Vendor**, it’s important to assign their GST details.

### 📝 For Each Contact:

* Go to **Contacts → Customers/Vendors**
* Click on the contact name → Edit
* Under the **GST Details** section:

  * Enter GSTIN
  * Select **GST Treatment**:

    * **Registered Business – Regular**
    * **Registered Business – Composition**
    * **Unregistered Business**
    * **Consumer**
    * **Overseas**
    * **Special Economic Zone (SEZ)**

> 🔍 This ensures correct tax types (CGST/SGST or IGST) are applied during transactions.

---

## 🛍️ **Step 3: Create GST-Compliant Items**

Each item you sell or purchase should be assigned an HSN or SAC code and tax rate.

### 🔹 How to do it:

1. Go to **Items → + New Item**
2. Choose **Goods** (HSN) or **Services** (SAC)
3. Enter:

   * **HSN/SAC Code**
   * **Tax Rate** (e.g., 18%)
   * **Item Name and Description**

> ✅ Items with tax preferences will auto-apply correct taxes in invoices.

---

## 📄 **Step 4: Create GST-Compliant Invoices & Bills**

### 🔹 For Sales:

* Go to **Sales → Invoices → + New**
* Add a GST-enabled customer
* Select items (GST applied automatically)
* Based on location:

  * **Same State** = CGST + SGST
  * **Different State** = IGST

### 🔹 For Purchases:

* Go to **Purchases → Bills → + New**
* Choose a GST-registered vendor
* Select taxable items → Tax is auto-calculated
* Input Tax Credit (ITC) is tracked automatically

---

## 📊 **Step 5: GST Reports in Zoho Books**

Zoho Books generates the following GST reports automatically:

| Report                            | Purpose                             |
| --------------------------------- | ----------------------------------- |
| **GSTR-1**                        | Details of outward supplies (sales) |
| **GSTR-3B**                       | Summary of tax liability and ITC    |
| **GSTR-2** *(for reconciliation)* | Purchases and inward supplies       |
| **ITC Summary**                   | Input Tax Credit report             |
| **GST Summary**                   | Overall GST collected and paid      |
| **HSN/SAC Summary**               | HSN-wise sales and purchases        |

### 🔹 Access via:

**Reports → Taxes → GST Returns**

> 📤 Reports can be downloaded as **JSON, Excel, or PDF** for GSTN filing.

---

## 🧠 **Step 6: Filing GST Returns**

### ⚙️ How Zoho Helps:

* GSTR-1 and GSTR-3B reports are prepared monthly/quarterly.
* JSON files are compatible with the **GST Portal ([https://www.gst.gov.in](https://www.gst.gov.in))**.
* You still need to **log in to GSTN portal to file returns manually**, unless integrated with GST Suvidha Provider (GSP).

---

## 🔄 **Step 7: Reconciliation of GST**

1. Import GSTR-2A/2B from the GST portal (JSON file).
2. Compare with purchase data in Zoho Books.
3. Match discrepancies (missed ITC, mismatched invoices).

> 🔍 Use the **GSTR-2 Reconciliation tool** to avoid missed credits.

---

## 🧾 **GST Composition Scheme in Zoho Books**

If your business is under the **Composition Scheme**:

* Enable it in Settings → Taxes → Select “Composition”
* You’ll charge tax as a flat rate (not invoice-wise)
* Generate **Bill of Supply** instead of Tax Invoice

---

## 🚨 Common GST Errors & How to Avoid Them

| Issue                                 | Fix                                           |
| ------------------------------------- | --------------------------------------------- |
| Wrong tax applied (IGST vs CGST+SGST) | Check customer/vendor state and GST treatment |
| Missing GSTIN in invoices             | Ensure all contacts have GSTIN entered        |
| Inaccurate GSTR reports               | Review items and tax rates before invoicing   |

---

## 🎯 **Best Practices**

* ✅ Regularly update HSN/SAC codes as per notifications
* ✅ Reconcile monthly to avoid ITC loss
* ✅ File returns on time to avoid penalties
* ✅ Keep backup of filed reports and challans

---

## 🧠 **Recap: Workflow in Zoho Books for GST**

1. Enable GST in settings
2. Add GSTIN to contacts
3. Add items with HSN/SAC and tax rates
4. Create tax-compliant invoices and bills
5. Generate and reconcile GSTR reports
6. Export and file via GST portal
