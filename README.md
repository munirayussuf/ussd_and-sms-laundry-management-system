# ussd_and-sms-laundry-management-system
# USSD and SMS for Laundry Service Management System

## Project Overview

The USSD and SMS Laundry Service Management System is a digital solution designed to make laundry services more accessible to customers using both formal laundry businesses and informal laundry providers (Mama Fua).

The system provides an alternative way for customers to request laundry services, track their orders, and receive notifications without requiring an internet connection.

It aims to bridge the digital gap between customers, formal laundry businesses, and informal laundry service providers.

## Problem Statement

Many laundry service providers still rely on manual record-keeping and traditional communication methods to manage customer requests and track laundry orders.

This can result in misplaced items, lost records, communication delays, and difficulties tracking order progress.

Additionally, customers who do not have smartphones or reliable internet access may face challenges accessing digital laundry services.

## Objectives

- To simplify laundry service requests through USSD and SMS.
- To support both formal laundry businesses and informal Mama Fua providers.
- To enable customers to track their laundry orders.
- To improve communication between customers and service providers.
- To provide an accessible solution for users without internet access.

## Key Features

### 1. USSD Simulation
- Customers can access the service by dialing `*123#` within the demonstration.
- Select formal laundry or informal Mama Fua services.
- Choose a laundry provider.
- Select available services and quantities.
- Choose between pick-up and drop-off.
- Receive order confirmation.

### 2. SMS Functionality
Customers can interact with the system through simulated SMS commands.

Available commands include:

| Command | Description |
|---|---|
| HELP | Displays available SMS commands. |
| PRICES | Displays laundry service prices. |
| STATUS LD1001 | Checks an order's status. |
| CANCEL LD1001 | Cancels an eligible order. |
| BOOK MAMA MILIMANI MEDIUM | Books an informal laundry service. |
| BOOK FORMAL WASH 5 | Requests a formal laundry service. |

### 3. Provider Communication

Laundry service providers can manage customer requests using SMS commands.

| Command | Action |
|---|---|
| ACCEPT LD1001 | Accepts a laundry request. |
| READY LD1001 | Marks an order as ready for delivery. |
| DONE LD1001 | Marks an order as delivered. |

### 4. Order Tracking
Customers can check the progress of their laundry requests and receive status updates.

Order statuses include:
- Received
- Accepted
- Washing
- Ready for delivery
- Delivered

### 5. Admin Dashboard

The administration panel provides an overview of laundry activities, including:

- Total orders.
- Orders received through USSD.
- Orders received through SMS.
- Formal laundry requests.
- Mama Fua requests.
- Total order value.
- Order details and current status.

## Technologies Used

- HTML5 – Structure of the application.
- CSS3 – Styling and responsive interface.
- JavaScript – Application logic, USSD simulation, SMS interactions, and order management.

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder.
3. Locate the HTML file.
4. Open the HTML file using a web browser.
5. Use the phone interface to explore the USSD demonstration.
6. Dial `*123#` to start a simulated session.
7. Navigate to the Messages section to test SMS interactions.
8. Explore the Admin Panel to view customer orders and their progress.

**Note:** This is a browser-based prototype. USSD sessions and SMS messages are simulated locally. Live integration with a telecommunications provider, such as Safaricom, is not currently implemented.

## Project Significance

The system demonstrates how digital technology can improve laundry service management by making services accessible to both formal businesses and informal laundry providers.

By incorporating USSD and SMS-based interactions, the proposed solution aims to accommodate customers who may not have smartphones or consistent internet connectivity.

## Future Improvements

- Integrate a live USSD gateway.
- Implement real SMS communication through an SMS gateway.
- Connect the application to a centralized database.
- Develop a complete provider management system.
- Introduce secure user authentication.
- Integrate M-Pesa payment functionality.

## Author

**Munira Yussuf Suraw**

Bachelor of Science in Information Technology

Laundry Service Management System – Final Year Project.
