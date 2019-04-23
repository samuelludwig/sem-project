# Specifications Document

***

## Inventory Management

- The system will allow the management of ECAM to keep close watch on:
  - Their inventory levels
  - Thier inventory costs
  - Their labor costs

***

## Aircraft

- The system must track all aircraft the ECAM manufactures.
- Each aircraft must have its own unique identification number.
- Each aircraft is made up of many, many aircraft parts.
- For each aircraft, the system will maintain a list of parts used for that aircraft.

***

## Aircraft Parts

- The system must track all parts that are used to assemble each aircraft.
- Each part must have its own unique part number.
- Each part is associated with one or more aircraft.
- For each part, the system must maintain a list of aircraft where the part is used.
- Each part must be tracked so that the company knows, at any time, how many of each part are in stock to make sure that the production schedule can proceed as planned.
- Each part must have one or more drawings/models associated with it.
- The system must track the cost of each part.

***

## Order Management

- The system must track all customer orders for aircraft.
- Each customer order must be tracked and ledgered eternally (past, current, and future).
- Each order in the system must contain:
  - The customer
  - The order total (dollar amount)
  - The items ordered
  - The date ordered
  - The order id number

***

## Employee Management

- The system must keep track of each employee of the ECAM.
- Each Employee must have a job title.
- Each Employee must have a list of projects they are assigned to.
- Each Employee must have an amount of hours worked on each program.
- Each Employee must have a list of engineering drawings/models that they are associated with.
- The system must track the wages fo each employee.

***

## Drawing/Model Management

- The system must track each Engineering Drawing/Model for each aircraft part.
- Each Drawing/Model must be associated with one or more engineers.
- Each Drawing/Model will be occasionally updated.
- Each Drawing/Model must have a list of timestamps (with authors) recording each change made.
- Each Drawing/Model must have an indication that the most current design is being used.

***

## Security

- The system and the information held within it must be highly secure, no unauthorized personnel can be allowed access.

## Other Specifications

- The system will be scalable up to a minimum of 300 users.
- The system's servers will be stored in a 2 story building.