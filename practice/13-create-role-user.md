# **Classroom Exercise: Creating and Assigning an Accountant Role in Zoho Books**

## **Objective**

Students will:

* Create a custom **Accountant** role.
* Set permissions for the role.
* Invite a user and assign them to the role.
* Verify access rights from that user’s perspective.

---

## **Scenario**

Your company, **GreenLeaf Traders**, has hired an external accountant named **Ravi Mehta** to handle bookkeeping, bank reconciliation, and GST returns.
You want Ravi to have full access to:

* Sales
* Purchases
* Banking
* Reports
* Taxes
* Journals

But you want to **restrict access** to:

* Organization Profile
* User Management
* Inventory Setup

---

## **Step-by-Step Instructions**

### **Step 1: Navigate to Roles**

1. Login to Zoho Books.
2. Click the **Settings** icon (⚙️) in the top-right corner.
3. Under **Users & Roles**, click **Roles**.

---

### **Step 2: Create the Accountant Role**

1. Click **+ New Role**.
2. **Role Name:** Accountant
   **Description:** External accountant with access to sales, purchases, banking, and reports.
3. In the permissions checklist:

   * ✅ Enable: Sales, Purchases, Banking, Reports, Taxes, Journals.
   * ❌ Disable: Organization Profile, User Management, and other sensitive admin settings.
4. Click **Save**.

---

### **Step 3: Invite the Accountant User**

1. Go to **Settings → Users & Roles → Users**.
2. Click **+ Invite User**.
3. Fill in:

   * **Name:** Ravi Mehta
   * **Email:** [ravi.mehta@example.com](mailto:ravi.mehta@example.com)
4. Under **Role**, select **Accountant**.
5. Click **Send Invitation**.

---

### **Step 4: Simulate Accountant Access**

1. Log out from your admin account.
2. Login using the invited user’s credentials (Ravi’s account).
3. Check:

   * Can access Sales, Purchases, Banking, Reports, Taxes, Journals.
   * Cannot change Organization Profile or add new users.

---

### **Step 5: Verify Audit Trail**

1. Go back to Admin account.
2. Open **Reports → Audit Trail**.
3. Check for actions performed by Ravi Mehta to ensure tracking is in place.

---

## **Practice Questions**

1. Why should we create a custom role instead of using the default Admin role for an external accountant?
2. What modules should an accountant typically have access to in Zoho Books?
3. How can you remove access for an accountant without deleting their records?

---

## **Expected Outcome**

By the end of this exercise, students should be able to:

* Create a role with specific permissions.
* Assign a user to that role.
* Verify role-based access control in Zoho Books.