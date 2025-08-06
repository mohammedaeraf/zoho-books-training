# **Basic regular expression (regex) validations** for **custom fields**

## ✅ Goal:

Create a **Custom Field** (e.g., Serial Number or Tracking Code) that:

* Accepts input like: `1234-5678-9012`
* Validates that it's exactly **12 digits** grouped in 3 parts of 4 digits each
* Ensures **hyphens** are in the correct position

---

## 🛠 Step-by-Step: Creating the Custom Field with Validation

---

### 🔹 Step 1: Navigate to Custom Fields

* Go to **Settings** → **Preferences**
* Choose the module (e.g., **Customers**, **Invoices**, **Items**, etc.)
* Scroll to **Custom Fields**
* Click **+ New Custom Field**

---

### 🔹 Step 2: Enter Field Details

| Field                | Value                            |
| -------------------- | -------------------------------- |
| **Label Name**       | `Serial Number` (or any name)    |
| **Data Type**        | `Text`                           |
| **Placeholder Text** | `e.g., 1234-5678-9012`           |
| **Validation Regex** | `[0-9]{4}-[0-9]{4}-[0-9]{4}`     |
| **Error Message**    | `Enter in format XXXX-XXXX-XXXX` |

---

### ✅ Regex Breakdown:

* `[0-9]{4}` → Four digits
* `-` → Hyphen
* Repeat pattern 3 times: `[0-9]{4}-[0-9]{4}-[0-9]{4}`

So valid input will be:

```
1234-5678-9012 ✅
```

Invalid input examples:

```
123456789012 ❌
1234-567-8901 ❌
ABCD-1234-5678 ❌
```

---

## 🔍 Where This Is Useful

You can apply such validation for:

* **Serial Numbers**
* **Asset IDs**
* **License Keys**
* **Subscription codes**
* **Structured Reference IDs**

---

## 🎯 Summary

| Feature                   | Available in Zoho Books        |
| ------------------------- | ------------------------------ |
| Regex Validation          | ✅ Yes                          |
| Input Pattern for Numbers | ✅ `[0-9]{4}-[0-9]{4}-[0-9]{4}` |
| Error Message Display     | ✅ Yes                          |
| Applies To Which Fields   | `Text` fields only             |