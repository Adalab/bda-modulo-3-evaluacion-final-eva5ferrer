# Airline Loyalty Program Data Description

This documentation describes two datasets that track customer behavior and profiles within an airline loyalty program.

---

## 1. Customer Flight Analysis.csv
This file contains details regarding flight activity, distance, and loyalty point transactions.

| Column Name | Description |
| :--- | :--- |
| **Loyalty Number** | A unique identifier for each customer. |
| **Year** | The year the flight activities were recorded. |
| **Month** | The month (1-12) the activities occurred. |
| **Flights Booked** | Total flights booked by the customer in that month. |
| **Flights with Companions** | Number of flights booked where the customer traveled with others. |
| **Total Flights** | Total flights taken, including those from previous months. |
| **Distance** | Total distance flown during the month. |
| **Points Accumulated** | Points earned during the month. |
| **Points Redeemed** | Points used for benefits like free flights or upgrades. |
| **Dollar Cost Points Redeemed** | The dollar value of the redeemed points. |

---

## 2. Customer Loyalty History.csv
This file provides a detailed profile of the customers and their membership history.

### **Demographics & Location**
* **Loyalty Number**: Unique identifier used to link this file with flight activity.
* **Location**: Includes **Country**, **Province**, **City**, and **Postal Code**.
* **Gender**: The customer's gender (e.g., Male or Female).
* **Education**: Highest educational level achieved.
* **Salary**: Estimated annual income.
* **Marital Status**: Marital status (e.g., Single, Married, Divorced).

### **Membership Details**
* **Loyalty Card**: The tier or category of the loyalty program card.
* **CLV (Customer Lifetime Value)**: Total estimated value the customer brings to the company.
* **Enrollment**: Includes **Enrollment Type**, **Year**, and **Month**.
* **Cancellation**: The **Year** and **Month** the membership was cancelled, if applicable.