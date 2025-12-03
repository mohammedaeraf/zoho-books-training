# **What is Auto-Charge in Recurring Invoice?**

**Auto-Charge** is a feature that lets Zoho Books **automatically collect payment from your customer** whenever a recurring invoice is generated.

Instead of just sending the invoice, the system:

* Charges the customer’s saved card / bank mandate
* Marks the invoice as **Paid** (if successful)
* Sends a payment confirmation email automatically

---

## **How Auto-Charge Works (Simple Flow)**

1. You create a **Recurring Invoice**
2. You enable **Auto-Charge**
3. Customer saves payment method (card / bank mandate)
4. On each billing date:

   * Invoice is generated
   * Payment is charged automatically
   * Invoice is marked “Paid”
   * Receipt is emailed

---

## **When Should Auto-Charge Be Used?**

Use Auto-Charge for:

* Subscriptions
* Maintenance contracts
* Monthly retainers
* SaaS billing
* Gym fees
* Website hosting charges

Basically, for **fixed recurring payments**.

---

## **Requirements to Use Auto-Charge**

✅ Payment gateway must be configured
✅ Customer must **authorize saving payment method**
✅ Auto-charge option must be enabled in the recurring invoice
✅ Customer’s card / mandate must be valid

---

## **What Happens If Payment Fails?**

If auto-charge fails:

* Invoice remains **Unpaid**
* Customer gets a payment failure notification
* You can retry charging manually or ask customer to update card

---

## **Difference: Auto-Charge vs Normal Recurring Invoice**

| Feature                   | Normal Recurring Invoice | Auto-Charge      |
| ------------------------- | ------------------------ | ---------------- |
| Invoice created           | Yes                      | Yes              |
| Email sent                | Yes                      | Yes              |
| Payment collected         | ❌ No                     | ✅ Yes            |
| Manual follow-up required | Yes                      | No               |
| Invoice auto-marked Paid  | No                       | Yes (if success) |

---

## **Real-Life Example**

You run a hosting service charging ₹2,000/month.

With Auto-Charge:

* Every month invoice is created
* Customer is charged automatically
* You get paid without sending reminders

Without Auto-Charge:

* Invoice is created
* You must chase payments manually