# **Tutorial: Configuring Users & Roles in Zoho Books**

## **1. Introduction**

In Zoho Books, **Users** are the people who can access your organization’s account, while **Roles** define what those users can do or see.
By configuring users and roles, you control permissions and safeguard sensitive financial data.

---

## **2. Navigating to Users & Roles**

1. **Login** to your Zoho Books account.
2. Go to the **Settings** icon (⚙️) in the top-right corner.
3. Under **Users & Roles**, click **Users** to manage users, or **Roles** to manage role permissions.

---

## **3. Default Roles in Zoho Books**

Zoho Books comes with some predefined roles such as:

* **Admin** – Full access to all modules and settings.
* **Staff** – Limited access, mostly related to sales or basic reports.
* **Time Tracking** – Can only log time for projects.
* **External Accountant** – Access to accounting modules but not sensitive admin settings.

---

## **4. What is the Accountant Role?**

The **Accountant Role** is designed for:

* Your in-house accountant or external CA.
* People who need access to financial reports, journals, bank reconciliation, and taxes.
* Restricted access to sensitive admin settings (unless you allow it).

**Typical permissions for Accountant Role:**

* View and manage **Sales** & **Purchases**
* Access **Banking**
* Manage **Journals**
* Access **Reports**
* Manage **Taxes**
* View Audit Trail

---

## **5. Creating an Accountant Role**

1. Go to **Settings → Users & Roles → Roles**.
2. Click **+ New Role**.
3. Name it **Accountant** (or “External Accountant”).
4. In the permissions checklist:

   * Enable access to **Sales**, **Purchases**, **Banking**, **Reports**, **Taxes**, **Journals**, and **Settings → Taxes**.
   * Disable access to **Organization Profile**, **User Management**, and sensitive configuration options unless required.
5. Click **Save**.

---

## **6. Adding a User to the Accountant Role**

1. Go to **Settings → Users & Roles → Users**.
2. Click **+ Invite User**.
3. Enter:

   * **Name**
   * **Email Address**
4. Under **Role**, select the newly created **Accountant**.
5. Click **Send Invitation**.
6. The user will receive an email invitation to join your Zoho Books organization.

---

## **7. Managing User Access Later**

* You can **Edit User Role** anytime by:

  * Going to **Users → Select User → Edit** and changing their role.
* You can **Deactivate** a user without deleting their records if they no longer need access.

---

## **8. Best Practices**

* **Use Role-based Access** instead of giving everyone Admin rights.
* For external accountants, give only necessary modules to avoid data leaks.
* Regularly review user activity via the **Audit Trail**.

---

### **Quick Recap Table**

| Step | Action                               |
| ---- | ------------------------------------ |
| 1    | Go to Settings → Roles → + New Role  |
| 2    | Name Role "Accountant"               |
| 3    | Assign relevant permissions          |
| 4    | Save Role                            |
| 5    | Go to Users → + Invite User          |
| 6    | Select Accountant Role & Send Invite |

