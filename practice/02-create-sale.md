## 🧑‍💼 Practice Exercise: Creating and Managing a Sales Transaction in Zoho Books

---

### 🧾 **Scenario**:

You run a small stationery shop. A customer named **Rahul Nair** walks in and purchases **5 Student Notebooks (200 Pages)**. You need to:

1. Add the customer
2. Ensure the item is in stock
3. Create an **invoice**
4. Record the **payment**
5. Verify the inventory reduction

---

### ✅ Product Details

| Field                | Value                        |
| -------------------- | ---------------------------- |
| Item Name            | Student Notebook – 200 Pages |
| Unit                 | Piece                        |
| Rate (Selling Price) | ₹60                          |
| Opening Stock        | 50 units                     |

---

### ✅ Customer Details

| Field | Value                                         |
| ----- | --------------------------------------------- |
| Name  | Rahul Nair                                    |
| Email | [rahul@example.com](mailto:rahul@example.com) |
| Phone | 9876543210                                    |

---

## 🧪 Steps to Perform

---

### 🧱 Task A: Add or Verify Item

1. Go to **Items → Items**
2. Check if `Student Notebook – 200 Pages` exists

   - If not, click **+ New Item**
   - Type: `Product`
   - Selling Price: ₹60
   - Track Inventory ✅
   - Opening Stock: `50`
   - Reorder Point: `10`

3. Save

---

### 👤 Task B: Add the Customer

1. Go to **Sales → Customers**
2. Click **+ New Customer**
3. Fill in details:

   - Name: `Rahul Nair`
   - Email: `rahul@example.com`
   - Phone: `9876543210`

4. Save

---

### 🧾 Task C: Create a Sales Invoice

1. Go to **Sales → Invoices**
2. Click **+ New Invoice**
3. Choose **Customer**: `Rahul Nair`
4. Add Item: `Student Notebook – 200 Pages`

   - Quantity: `5`
   - Price auto-fills as ₹60

5. Total: ₹300
6. Notes: “Thank you for your purchase!”
7. Click **Save and Send** (or Save as Draft)

✅ Invoice is now created

---

### 💰 Task D: Record the Payment

1. Open the Invoice
2. Click **Record Payment**
3. Enter:

   - Amount Received: ₹300
   - Mode of Payment: Cash / UPI
   - Payment Date: Today

4. Save

✅ Invoice status becomes **Paid**

---

### 📦 Task E: Verify Inventory Update

1. Go to **Items → Items**
2. Check stock for `Student Notebook – 200 Pages`

✅ Stock should now show **45 units** (50 – 5)

---

### 📊 Task F: View in Reports (Optional)

- Go to **Reports → Sales → Sales by Item**
- Select date range = Today
- You’ll see that 5 notebooks were sold

---

## 🎯 Student Challenge (Optional):

> Create another customer named _Asha Reddy_.
> Sell her 3 notebooks and 1 pen (if pen is not created, create it with a selling price of ₹20).
> Record the invoice and payment.
> Check updated stock levels for both items.
