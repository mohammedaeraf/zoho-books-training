## 📘 Inventory Valuation Methods: FIFO vs WAC

---

### ✅ 1. FIFO (First In, First Out)

**Definition**:
FIFO assumes that the **oldest inventory items** (first purchased) are sold first.

#### 🔍 How It Works:

Let’s say you bought:

| Date   | Quantity | Cost per Unit |
| ------ | -------- | ------------- |
| Jan 1  | 10 units | ₹100          |
| Jan 10 | 10 units | ₹120          |

Now, you sell 10 units.

✅ Under FIFO:

* You will assume the 10 units sold were from Jan 1 at ₹100 each
* So, **COGS = ₹1,000**, and your remaining stock is from Jan 10 at ₹120

#### ✅ Suitable for:

* Businesses that sell perishable or time-sensitive items (e.g., food, cosmetics)
* Ensures older stock is cleared first

---

### ✅ 2. WAC (Weighted Average Cost)

**Definition**:
WAC assumes that every unit of inventory has the **same average cost**, regardless of purchase date.

#### 🔍 How It Works:

Using the same example:

| Date   | Quantity | Cost per Unit | Total Cost |
| ------ | -------- | ------------- | ---------- |
| Jan 1  | 10 units | ₹100          | ₹1,000     |
| Jan 10 | 10 units | ₹120          | ₹1,200     |

Total = 20 units for ₹2,200

✅ Weighted Average Cost = ₹2,200 / 20 units = ₹110 per unit

Now, if you sell 10 units:

* COGS = 10 × ₹110 = ₹1,100
* Remaining inventory = 10 units at ₹110

#### ✅ Suitable for:

* Businesses where inventory items are indistinguishable (e.g., liquids, raw materials, bolts)
* Simplifies calculations for large volumes

---

## ⚖️ Key Differences at a Glance:

| Feature             | FIFO                         | WAC (Weighted Avg Cost)         |
| ------------------- | ---------------------------- | ------------------------------- |
| Inventory sold from | Earliest purchase            | Average cost of all purchases   |
| COGS impact         | Lower in rising price market | Smooths out cost fluctuations   |
| Best for            | Perishables, time-sensitive  | Uniform goods, manufacturing    |
| Tracking complexity | Slightly complex             | Easier to manage for large SKUs |

---

### 📌 In Zoho Books:

When you enable inventory tracking:

* Go to **Settings → Items → Inventory Settings**
* Choose **FIFO** or **Weighted Average** as your valuation method

*Note: Once selected and transactions are recorded, you **cannot change the valuation method** for historical consistency.*