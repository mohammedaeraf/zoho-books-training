## **1. Opening Balance (general concept in Zoho Books)**

* **Definition:** The amount that was already due **before you started recording transactions in Zoho Books** (i.e., the carry-forward balance from your previous accounting system).
* **Usage:**

  * You set it **once** when creating a customer (or later by editing their record).
  * This represents **historical dues** as of your Zoho Books start date.
* **Effect:** This amount gets added to that customer’s statement so their outstanding balance is correct from day one.

---

## **2. Customer Opening Balance in the Customer Statement**

* **Definition:** In the statement, the “Opening Balance” line is simply the **outstanding balance at the start date of the statement period** — it could be:

  * The original opening balance you set **plus** any older unpaid invoices and adjustments, **or**
  * If the statement start date is later, it’s the balance carried forward from all transactions before that date.
* **Dynamic:** It changes depending on the **statement date range** you choose.
* **Example:**

  * If you run a statement for **1 Jan – 31 Jan**, the “Opening Balance” is whatever the customer owed as of 1 Jan (even if you didn’t set an explicit opening balance at account creation).

---

### **In short**

* **Opening Balance** (customer record) → Set manually when migrating data into Zoho Books. It’s the balance as of your accounting start date.
* **Customer Statement Opening Balance** → Calculated automatically based on all transactions before your chosen statement period start date.

---

## **Scenario Setup**

* **Zoho Books start date:** 1 Jan 2025
* **Customer:** ABC Traders
* **Opening Balance set in customer record:** ₹5,000 (due before Zoho Books start date)
* **Transactions:**

| Date      | Transaction         | Amount (₹) | Payment (₹) | Balance (₹) |
| --------- | ------------------- | ---------- | ----------- | ----------- |
| 01 Jan 25 | **Opening Balance** | 5,000      |             | 5,000       |
| 05 Jan 25 | Invoice #INV-001    | 2,000      |             | 7,000       |
| 15 Jan 25 | Payment Received    |            | 3,000       | 4,000       |
| 28 Jan 25 | Invoice #INV-002    | 1,000      |             | 5,000       |
| 05 Feb 25 | Payment Received    |            | 2,000       | 3,000       |

---

## **Example 1 — Statement for 1 Jan – 31 Jan**

* **Opening Balance (in statement):** ₹5,000

  * This is the original Opening Balance set in the customer record (as of Zoho start date).
* **Transactions shown:**

  * Invoice #INV-001
  * Payment received on 15 Jan
  * Invoice #INV-002 (28 Jan)
* **Closing Balance:** ₹5,000 (due at end of Jan)

---

## **Example 2 — Statement for 1 Feb – 28 Feb**

* **Opening Balance (in statement):** ₹5,000

  * This is **not** the original ₹5,000 you set — this is the **carry-forward** from Jan’s closing balance.
* **Transactions shown:**

  * Payment received on 5 Feb (₹2,000)
* **Closing Balance:** ₹3,000

---

### **Key Takeaway for Students**

* **Customer Opening Balance (customer record)** → Fixed value set when you start with Zoho Books.
* **Opening Balance in Statement** → Always the amount owed at the **start date of the chosen statement period** — it can include the original opening balance **plus** any unpaid invoices from earlier periods.
