# 🧾 ERP Inventory & Accounting System

A MongoDB-based ERP inventory module for managing items, stock, pricing, and GST.
This project is built for learning, testing, and extending into a full ERP system.

---

## 📌 Features

- Add & manage inventory items
- GST-compliant pricing (India)
- Opening stock & reorder level tracking
- Unit-based stock handling (PCS, KG, LTR, etc.)
- MongoDB-ready schema
- Clean and professional UI
- Ready for sales, purchase & accounting integration

---

## 📦 Item Fields

Each item includes the following fields:

| Field | Description |
|------|------------|
| itemName | Name of product or service |
| hsnBatchNo | HSN code or batch number |
| unit | Measurement unit (PCS, KG, LTR, MTR, BAG) |
| purchasePrice | Purchase price (₹) |
| salePrice | Sale price (₹) |
| gstRate | GST percentage |
| openingStock | Initial stock quantity |
| reorderLevel | Low-stock alert threshold |

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript / React
- **Backend:** Node.js (Express)
- **Database:** MongoDB (Local / Atlas)
- **Tools:** MongoDB Compass

---

## 📊 Business Logic

- Opening stock is recorded at item creation
- Reorder level triggers low-stock alerts
- Sale price − purchase price = profit margin
- GST is calculated per item during billing

---

## 🔐 Planned Enhancements

- Role-based access (Admin / User)
- Company-wise multi-tenant system
- Stock auto-update on sales & purchases
- Sales & Purchase invoices
- Payments, receipts & journal entries
- Reports & dashboards

---

## 📄 License

This project is intended for educational and practice purposes.

---

## ✨ Author

**Shlok Panchal**  
2nd Year AIML Student  
Symbiosis Institute of Technology, Pune
