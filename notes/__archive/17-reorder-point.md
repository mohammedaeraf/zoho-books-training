# 📦 Tutorial: **Reorder Point in Zoho Books**

---

## ✅ What is a Reorder Point?

**Reorder Point** is the **minimum stock level** at which you should **reorder an item** to avoid stockouts.

Think of it as a **low-stock alert**. When your stock falls to or below this level, Zoho Books will remind you to place a new purchase order.

---

### 📘 Example:

Let’s say you sell **USB Drives** and set the Reorder Point to **5 units**.

- If your stock drops to 5 or below, Zoho Books will flag it as **“Reorder Needed”**
- You can then quickly create a **Purchase Order** to restock

---

## 🛠️ How to Set a Reorder Point in Zoho Books

---

### 🔹 Step 1: Enable Inventory Tracking (if not already enabled)

1. Go to **Settings → Items → Preferences**
2. Tick ✅ **Track Inventory for Items**
3. Click **Save**

---

### 🔹 Step 2: Add or Edit an Item with Inventory

1. Go to **Items → + New** or edit an existing item
2. Choose **Type**: Goods
3. Fill out details like Item Name, Rate, Tax, etc.
4. Under **Inventory Info**, fill:

| Field                 | Example Value   |
| --------------------- | --------------- |
| **Opening Stock**     | 10              |
| **Reorder Point**     | 5               |
| **Inventory Account** | Inventory Asset |

5. Click **Save**

---

## 🔁 How Reorder Point Works

Once set, Zoho Books will **automatically monitor your stock levels**.

- When stock ≤ Reorder Point, it shows a label:
  🔴 **Reorder Needed**

- You’ll also see low-stock items in the **Dashboard widget** and **Inventory Summary Report**

---

### 🔍 Where to See Reorder Alerts

- **Items List**: A red dot with “Reorder Needed” appears
- **Dashboard**: Look for **Low Stock Items** widget
- **Reports → Inventory Summary**: View items with stock below reorder point

---

## ✨ Benefits of Using Reorder Point

| Benefit                     | Description                             |
| --------------------------- | --------------------------------------- |
| 📦 Avoid stockouts          | Get alerts before running out of stock  |
| 🔄 Better purchase planning | Helps schedule orders on time           |
| 📊 Inventory efficiency     | Keep optimal levels of stock            |
| 💰 Saves money              | Avoid over-ordering or emergency buying |

---

## 🧠 Example Scenario

You run a stationery shop. For **A4 Paper Packs**:

- Opening stock: 15
- Reorder Point: 5

After selling 11 packs, the stock becomes **4**. Zoho Books flags this item as **Reorder Needed**, and you quickly raise a **Purchase Order** for 20 more.

---

## 🧪 Optional Practice Task

> Add a new item:

- Name: Whiteboard Markers
- Opening Stock: 8
- Reorder Point: 3
  Then record a sale of 6 units. Observe how Zoho Books alerts you to reorder.
