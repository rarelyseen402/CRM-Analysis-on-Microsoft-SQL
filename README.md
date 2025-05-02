## **CRM-Analysis-on-Microsoft-SQL**

### **Project Overview**
This project demonstrates a practical use of `SQL` to analyze data in a Customer Relationship Management (CRM) database. My analysis mainly focused on extracting customer information and identifying order shipping status based on business logic. The purpose of this project is to apply real world `CRM` scenarios, and show how `SQL` can support decision making in customer service & sales operations.

### **Case Study Questions**
1. Retrieve details for all customers
   ```sql -- SELECT * FROM SalesLT.Customer;```
2. Determine the shipping status of sales orders by classifying whether each has been 'Shipped' or 'Awaiting Shipment'
   ```sql -- UPDATE SalesLT.SalesOrderHeader SET ShipDate = NULL WHERE SalesOrderID > 71899;```

```sql -- SELECT SalesOrderID, OrderDate, CASE WHEN ShipDate IS NULL THEN 'Awaiting Shipment' ELSE 'Shipped' END AS ShippingStatus FROM SalesLT.SalesOrderHeader;```

### **Skills Demonstrated**
- `SQL QUERIES`
- `Data Manipulation`
- `SSMS`
- `Data Analysis`
- `Conditional Logic`
- `Business Insights`



  









