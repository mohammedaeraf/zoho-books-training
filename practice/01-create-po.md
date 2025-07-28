## 🧑‍💻 **Practice Exercise: Creating and Managing a Purchase Order**

### 🧾 Scenario:

You run a small training institute and need to purchase **50 notebooks** for your students. You’ll create a purchase order, mark the items as received, and convert the PO into a bill.

---

### ✅ Step-by-Step Instructions:

#### 🪪 Vendor Details:

* **Vendor Name**: *Stationery World*
* **Email**: [stationery@example.com](mailto:stationery@example.com)
* **Phone**: 9876543210

---

#### 📦 Product Details:

* **Item Name**: *Student Notebook – 200 Pages*
* **Type**: Product
* **Unit**: Piece
* **Rate (per piece)**: ₹40
* **Inventory Tracking**: Enabled
* **Opening Stock**: 0
* **Reorder Point**: 20

---

### 💼 Task A: Create a Product Item

1. Go to **Items → + New Item**
2. Enter details:

   * Name: `Student Notebook – 200 Pages`
   * Type: `Product`
   * Unit: `Piece`
   * Rate: ₹40
   * Track Inventory ✅
   * Opening Stock: `0`
   * Reorder Point: `20`
3. Save the item

---

### 📑 Task B: Add the Vendor

1. Go to **Purchases → Vendors → + New Vendor**
2. Name: `Stationery World`
3. Email: `stationery@example.com`
4. Phone: `9876543210`
5. Save

---

### 🛒 Task C: Create a Purchase Order

1. Go to **Purchases → Purchase Orders → + New Purchase Order**
2. Vendor: `Stationery World`
3. Date: Today
4. Add Item: `Student Notebook – 200 Pages`
5. Quantity: `50`
6. Rate auto-fills to ₹40 (₹2,000 total)
7. Notes: `Urgent delivery for student orientation`
8. Save as Draft

✅ Status: `Draft`

---

### 📤 Task D: Mark as Issued

1. Click on the PO → Click **Mark as Issued**
   ✅ Status changes to `Issued`
   📦 Inventory: Still **not affected**

---

### 📦 Task E: Mark as Received

1. Click **More Actions → Mark as Received**
2. Confirm item quantity received

✅ Inventory now **increases by 50 units**

---

### 🧾 Task F: Convert to Bill

1. Open the same PO → Click **Convert to Bill**
2. All item details are auto-filled
3. Click **Save**

✅ A Bill is now created, showing ₹2,000 payable to `Stationery World`

---

### 📊 Final Checks:

* Go to **Items** → Check that item stock is now `50`
* Go to **Reports → Inventory Summary** → View stock value
* Go to **Reports → Account Transactions** → Check “Purchase” expense recorded

---

### 🎓 Student Challenge (Optional):

> Create a PO for another item like “Pens (Blue)” – 100 units @ ₹5/unit.
> Follow all steps till “Convert to Bill” and verify stock and reports.
