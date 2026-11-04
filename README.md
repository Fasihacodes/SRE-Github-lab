# SRE-Github-lab

# Project Title: Restaurant Management System
## Overview
A centralized software application designed to streamline restaurant operations, resolve manual order and billing errors, and improve inventory and staff coordination.

## Stakeholders

 - Owner: Monitors sales, profits, and overall performance.
 - Manager: Oversees daily operations, staff attendance, and reports.
 - Cashier: Generates accurate bills and records payments.
 - Order Taker & Waiter: Takes table orders, sends them to the kitchen, and tracks service.
- Kitchen Staff & Delivery Boy: Prepares orders, updates stock availability, and handles deliveries.

## Scope

- In scope: Order management, menu updates, automated billing and payments, inventory tracking, delivery assignments, staff attendance, and sales reporting.

- Out of scope: Third-party online ordering, website table reservations, payroll, customer loyalty programs, multi-branch management, and advanced tax integrations.

## Functional requirements

 - FR-01: The system shall allow order takers to enter table orders with menu items and quantities.
 - FR-02: The system shall instantly transmit submitted orders to the kitchen.
 - FR-03: The system shall automatically calculate bills and process customer payments.

## Nonfunctional requirements

 - NFR-01: Transaction or search lists for 100 stored records shall load within 2 seconds in 95 of 100 trials.
 - NFR-02: Core ordering and billing tasks must be fully operable using standard input devices.

## Acceptance criteria

 - FR-01: Saving a new order correctly displays table details and items in the active queue.
 - FR-02: Submitting an order instantly within 5 seconds updates the kitchen display queue.
 - FR-03: Checking out and generates precise bill  and marks payment status as paid.

## Assumptions and open questions

- Assumption A-01: Staff possess basic digital literacy and compatible hardware devices.
- Open Questions: Requirements for payment gateway integrations and target test hardware specifications.

## Project status and viewing

Status: Documentation-only project; implementation not started.
 

## Author
 Ifra Ahmad Raza (BSEF25M542), Fasiha Muzzammil (BSEF25M534), Misbah Saeed (BSEF25M532).
## Contributing
Create a documentation branch, edit and review the README,
commit the change, push the branch, and open a pull request.



