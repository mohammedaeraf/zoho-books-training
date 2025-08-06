## ❓ **Problem Summary**

When you:

1. Create a **Purchase Order (PO)** and apply a **discount** (either per item or overall),
2. Then **convert that PO into a Bill**,
   👉 The **discount amount disappears** in the Bill — the items show up without the discount.

---

## 🧠 **Why This Happens**

In **Zoho Books**, **Purchase Orders are non-accounting documents** used primarily for:

* Sending a **request** to the vendor
* Negotiating prices, discounts, and terms

However, when a PO is **converted to a Bill**, Zoho Books assumes that:

> The actual bill received from the vendor is **final**, and may not reflect the same discount as the PO.

Hence, the system **does not carry forward the discount** from PO to Bill **by default**, because:

* Vendors may **not honor** the discount on the invoice
* Or you might need to **negotiate again** or apply a different discount

This gives the user **manual control** to apply or ignore discounts in the Bill.

---

## ✅ **Workaround / Best Practice**

If you **want the discount to be carried over** from PO to Bill, you’ll need to:

### 🔹 Manually re-enter the discount

When you convert the PO to a Bill:

* Edit the **item rows**
* Reapply the **discount** (same as in PO)
* Or, apply an **overall discount** at the bottom of the bill

---

## 📝 Example

| Step           | PO     | Converted Bill             |
| -------------- | ------ | -------------------------- |
| Item Price     | ₹1,000 | ₹1,000                     |
| Discount @ 10% | ₹100   | ❌ Not carried over         |
| Final Amount   | ₹900   | ₹1,000 (unless re-entered) |
