
# 🚗 Salesforce Car Booking Flow

An end-to-end automated vehicle rental booking process built inside Salesforce using **Screen Flows**, dynamic contextual data binding (`recordId`), and custom objects (`Car__c` & `Booking__c`).

---

## 🛠️ Tech Stack & Key Features

- **Salesforce Automation:** Screen Flows, Flow Data Tables, Quick Actions (`Book Car`).
- **Data Model & Schema:** Custom Objects (`Car__c`, `Booking__c`), Custom Fields, Master-Detail / Lookup relationships.
- **Local Development:** VS Code, Salesforce CLI (SFDX), Metadata Management, Git & GitHub Version Control.

---

## 📱 User Interface Screenshot

![Car Booking Flow Screen](https://raw.githubusercontent.com/jackmaherghally/Salesforce-Car-Booking-Flow/main/Screenshot%20(510).png)

---

## 🚀 How It Works

1. User navigates to any **Car** record in Salesforce.
2. Clicks the **Book Car** Quick Action.
3. The Screen Flow launches dynamically, retrieving the selected car's context via `recordId`.
4. User enters rental dates and customer info to generate a new `Booking__c` record automatically.
