# [cite_start]Airline Loyalty Program Data Description [cite: 1, 2]

[cite_start]This documentation describes two datasets that track customer behavior and profiles within an airline loyalty program. [cite: 2]

---

## 1. Customer Flight Analysis.csv
[cite_start]This file contains details regarding flight activity, distance, and loyalty point transactions. [cite: 3, 4]

| Column Name | Description |
| :--- | :--- |
| **Loyalty Number** | [cite_start]A unique identifier for each customer. [cite: 5] |
| **Year** | [cite_start]The year the flight activities were recorded. [cite: 7] |
| **Month** | [cite_start]The month (1-12) the activities occurred. [cite: 8] |
| **Flights Booked** | [cite_start]Total flights booked by the customer in that month. [cite: 9] |
| **Flights with Companions** | [cite_start]Number of flights booked where the customer traveled with others. [cite: 10] |
| **Total Flights** | [cite_start]Total flights taken, including those from previous months. [cite: 11] |
| **Distance** | [cite_start]Total distance flown during the month. [cite: 12] |
| **Points Accumulated** | [cite_start]Points earned during the month. [cite: 13] |
| **Points Redeemed** | [cite_start]Points used for benefits like free flights or upgrades. [cite: 14] |
| **Dollar Cost Points Redeemed** | [cite_start]The dollar value of the redeemed points. [cite: 15] |

---

## 2. Customer Loyalty History.csv
[cite_start]This file provides a detailed profile of the customers and their membership history. [cite: 16, 17]

### **Demographics & Location**
* [cite_start]**Loyalty Number**: Unique identifier used to link this file with flight activity. [cite: 18, 19]
* [cite_start]**Location**: Includes **Country**, **Province**, **City**, and **Postal Code**. [cite: 20, 21, 22, 23]
* [cite_start]**Gender**: The customer's gender (e.g., Male or Female). [cite: 24]
* [cite_start]**Education**: Highest educational level achieved. [cite: 25]
* [cite_start]**Salary**: Estimated annual income. [cite: 26]
* [cite_start]**Marital Status**: Marital status (e.g., Single, Married, Divorced). [cite: 27]

### **Membership Details**
* [cite_start]**Loyalty Card**: The tier or category of the loyalty program card. [cite: 28, 29]
* [cite_start]**CLV (Customer Lifetime Value)**: Total estimated value the customer brings to the company. [cite: 30]
* [cite_start]**Enrollment**: Includes **Enrollment Type**, **Year**, and **Month**. [cite: 31, 32, 33]
* [cite_start]**Cancellation**: The **Year** and **Month** the membership was cancelled, if applicable. [cite: 34, 35]