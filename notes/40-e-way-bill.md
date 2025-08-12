# **Tutorial – e-Way Bill in Zoho Books**

## **Objective**

Learn how to generate and manage e-Way Bills for goods movement directly from Zoho Books.

---

## **1. What is an e-Way Bill?**

An **e-Way Bill** is a document required under GST law for the movement of goods valued over **₹50,000**.
It contains details of:

* Goods being transported
* Consignor & consignee information
* Transport details (vehicle number / transporter ID)

It is mandatory for:

* Interstate supply of goods
* Intrastate movement above state-specific threshold

---

## **2. Pre-requisites in Zoho Books**

Before you can generate e-Way Bills:

1. **Enable GST** in your organization profile.
2. Ensure **HSN codes, GST rates, and taxable values** are correctly set for all items.
3. Have an **active e-Way Bill portal account** from NIC (National Informatics Centre).
4. Enable e-Way Bill integration in Zoho Books.

---

## **3. Enabling e-Way Bill in Zoho Books**

1. Go to **Settings → Taxes → e-Way Bill**.
2. Click **Enable e-Way Bill**.
3. Enter:

   * **e-Way Bill Portal Username**
   * **GSTIN**
4. Click **Generate OTP** → enter OTP from your registered mobile/email.
5. Zoho Books is now connected to the e-Way Bill portal.

---

## **4. When is an e-Way Bill Generated in Zoho Books?**

Zoho Books lets you generate an e-Way Bill from:

* **Invoices** (Sales)
* **Delivery Challans**
* **Credit Notes** (in case of goods return)

---

## **5. Generating an e-Way Bill from an Invoice**

1. Create an **Invoice** as usual.
2. Ensure:

   * **Total invoice value > ₹50,000** (or as per state rules)
   * **HSN code** and **GST rate** are set for all items
3. Save and Confirm the invoice.
4. Click **More → Generate e-Way Bill**.
5. Fill:

   * **Mode of Transport** (Road / Rail / Air / Ship)
   * **Vehicle Number** or **Transporter ID**
   * **Distance (KM)** to destination
6. Click **Generate**.
7. Zoho Books will send the data to the e-Way Bill portal and return the **e-Way Bill Number (EBN)** and **validity date**.

---

## **6. Printing an Invoice with e-Way Bill**

* After generation, the **e-Way Bill Number** will be printed automatically on the invoice.
* You can also download the **e-Way Bill PDF** from the invoice’s More options.

---

## **7. Canceling an e-Way Bill**

* Go to the invoice → **More → Cancel e-Way Bill**.
* Enter **Reason for Cancellation** (e.g., goods not transported).
* Must be done **within 24 hours** of generation.

---

## **8. Best Practices**

* Always update **vehicle details** before goods start moving.
* For multiple consignments in one vehicle, use **Consolidated e-Way Bill**.
* Regularly reconcile e-Way Bills in Zoho Books with the **NIC portal**.

---

## **9. Common Errors and Fixes**

| Error            | Cause                     | Fix                                      |
| ---------------- | ------------------------- | ---------------------------------------- |
| Missing HSN Code | Item not updated with HSN | Edit item & update HSN                   |
| Invalid GSTIN    | Wrong GST number entered  | Correct GSTIN in customer/vendor profile |
| OTP not received | Network or portal delay   | Retry or check registered mobile/email   |

---

## **Quick Flow Recap**

**Invoice / Delivery Challan → Generate e-Way Bill → Print with EBN → Transport Goods → Cancel (if needed)**
