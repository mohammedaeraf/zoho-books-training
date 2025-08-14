# 📘 Tutorial: Importing Bank Statement & Matching Transactions in Zoho Books

## **1. Why Import and Match Transactions?**

In Zoho Books, importing your bank statements and matching them with existing records helps you:

* Save time in reconciliation.
* Ensure your books reflect accurate financial activity.
* Avoid manual entry errors.

---

## **2. Methods of Getting Bank Data**

You can bring your bank transactions into Zoho Books in two ways:

1. **Automatic Bank Feeds** (if supported by your bank).
2. **Manual Bank Statement Import** (via CSV, TSV, or XLS format).

In this tutorial, we’ll focus on the **manual import** method.

---

## **3. Steps to Import a Bank Statement**

### **Step 1: Navigate to Banking**

* Go to the **Banking** module from the sidebar.
* Select the bank account you want to import transactions for.

### **Step 2: Choose “Import Statement”**

* Click the **Settings ⚙️** icon in the top right corner of the bank account page.
* Select **Import Statement**.

### **Step 3: Upload the File**

* Choose your bank statement file (formats: **CSV**, **TSV**, or **XLS**).
* Make sure it contains at least:

  * **Date**
  * **Description**
  * **Amount (Debit/Credit)**

### **Step 4: Map the Fields**

* Zoho Books will ask you to map your file’s columns to its own:

  * **Transaction Date** → Date
  * **Payee/Description** → Description
  * **Deposit Amount** → Credit
  * **Withdrawal Amount** → Debit
* Click **Next**.

### **Step 5: Review & Import**

* Zoho Books will show a preview.
* If all looks good, click **Import**.
* The transactions will now appear under the **Uncategorized Transactions** tab.

---

## **4. Matching Transactions**

Once the transactions are imported, you need to match them with your existing records.

### **Step 1: Go to Uncategorized Transactions**

* In the bank account, click **Uncategorized Transactions**.

### **Step 2: Matching Options**

* **Auto-Match**: Zoho Books will try to match based on date, amount, and payee.
* **Manual Match**: If no match is found, you can manually choose an existing transaction.

  * Click **Match Manually**.
  * Select the correct invoice, bill, or expense from the list.
  * Click **Match**.

### **Step 3: Add New Transactions (if needed)**

* If no matching record exists, click **Categorize Manually** to record it as:

  * Expense
  * Income
  * Transfer between accounts

---

## **5. Tips for Successful Matching**

* Keep your **dates** aligned with your accounting period.
* Ensure your **invoice/bill amounts** match exactly with bank entries.
* Use **Clear Descriptions** when recording transactions so matching is easier.

---

✅ **End Result**: Your imported bank statement is reconciled, with each entry matched or categorized.
