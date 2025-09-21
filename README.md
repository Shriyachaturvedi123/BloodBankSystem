# 🩸 Blood Bank Management System

A Java Swing-based GUI application to manage blood donors – allowing you to add, search, and delete donor records.

---

## 📌 Features

- Add new blood donors with name, blood group, and contact number
- Search donors by blood group
- Delete selected donor from the list
- Display all donor records in a table
- Preloaded with sample data for testing

---

## 🖥️ GUI Layout

### 🔺 Top Panel:
- Displays title: **"Blood Bank Management System"**

### 🔹 Left Panel (Form):
- Fields:
  - Name (TextField)
  - Blood Group (ComboBox)
  - Contact (TextField)
- Buttons:
  - Add Donor
  - Search by Group

### 🏷️ Center Panel:
- Donor list shown in a JTable

### 🔻 Bottom Panel:
- Search field to filter by blood group
- Buttons:
  - Show All
  - Delete Selected

---

## 🔄 Functionalities

| Action              | Method Name           | Description                              |
|---------------------|------------------------|------------------------------------------|
| Add a Donor         | `addDonor()`           | Adds a donor to the list and reloads UI  |
| Search Blood Group  | `searchByBloodGroup()` | Filters donors matching blood group      |
| Delete Selected     | `deleteSelected()`     | Deletes selected row from table          |
| Show All Donors     | `loadTable()`          | Displays all donor data in the table     |

---

## 🧪 Sample Donors (pre-added)

```java
donorList.add(new Donor("John Doe", "A+", "9876543210"));
donorList.add(new Donor("Jane Smith", "O-", "9123456789"));
