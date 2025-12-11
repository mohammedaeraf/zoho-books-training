## 🧾 Tutorial: Bulk Importing Items, Vendors, and Customers in Zoho Books

Bulk import in Zoho Books helps you save time when setting up your organization or migrating data from another system.

---

### ✅ Step 1: Prepare Your Import File

Each module (Items, Vendors, Customers) has its own format. You can:

* Download sample files from Zoho Books (recommended)
* OR Create your own CSV/XLS/XLSX file with proper columns

#### Common Tips:

* Format: `.csv`, `.xls`, or `.xlsx`
* Headers should match Zoho’s expected fields
* Avoid merged cells, formulas, or special characters

---

### 📦 A. Importing Items

1. **Go to**: `Items` → Click the **gear icon** (⚙) → **Import Items**
2. **Choose File**: Click **Choose File** and upload your spreadsheet
3. **Map Fields**: Zoho Books will auto-map column headers. Manually map if needed.
4. **Data Format Validation**: Ensure correct number formats, SKU codes, etc.
5. **Next** → **Import**

🔍 **Pro Tip**: Use categories like **Goods / Services**, include `HSN/SAC` codes if applicable for GST.

---

### 🧑‍💼 B. Importing Vendors

1. **Go to**: `Purchases` → `Vendors`
2. **Click**: `More Options (⋮)` → **Import Vendors**
3. **Upload File**: Choose your Excel/CSV file
4. **Map Fields**: Match fields like:

   * Vendor Name
   * Email
   * GSTIN
   * Currency
   * Payment Terms
5. **Click Next** → **Import**

---

### 👥 C. Importing Customers

1. **Go to**: `Sales` → `Customers`
2. **Click**: `More Options (⋮)` → **Import Customers**
3. **Upload File**: Choose file to import
4. **Map Fields**: Include fields like:

   * Customer Name
   * Email
   * GST Treatment & GSTIN
   * Currency
   * Opening Balance (optional)
5. **Click Next** → **Import**

---

### 🧪 Optional: Run a Test Import

* Select **"Only import 5 records"** to preview how data will be mapped.
* Useful to avoid mass errors.

---

### 🛠 Tips for a Successful Import

| 🔸 Issue          | ✅ Solution                                      |
| ----------------- | ----------------------------------------------- |
| Incorrect format  | Use sample file format from Zoho Books          |
| Import fails      | Check for special characters or invalid headers |
| Duplicate entries | Use unique IDs like `Email`, `Vendor Code`      |
| Currency mismatch | Ensure proper currency settings per contact     |
| GSTIN issues      | Use valid format (e.g., 15-character GSTIN)     |

---

### 📂 Sample Fields for Each Module

**Items**

* Item Name
* Item Type (Goods/Service)
* SKU
* Rate
* Tax (if any)

**Vendors**

* Vendor Name
* Vendor Email
* Phone Number
* Currency
* GSTIN (if applicable)

**Customers**

* Customer Name
* Email
* Phone
* Billing/Shipping Address
* GST Treatment, GSTIN

---

### 🧩 Where to Download Sample Files

* When you click **Import**, Zoho provides a **"Download Sample File"** link — use it as a template!
