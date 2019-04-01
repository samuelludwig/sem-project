# Requirements Breakdown

***

## Inventory Management

### The system under consideration must

- allow the management of ECAM to keep close watch on
  - their inventory levels
  - inventory costs
  - labor costs

***

## Aircraft (Program)

### Each aircraft (hereafter referred to as a program)

- has its own unique identification number
- is made up of many, many parts

***

## Aircraft (Program) Parts

### Each part

- has its own unique part number
- is associated with one or more programs
- is either made by ECAM or bought from outside vendors
- needs to be tracked so that the company knows, at any time, how many of each part are in stock to make sure that the production schedule can proceed as planned.
- has one or more drawings/models associated with it

***

## Order Management

### Each program

- might be for the exclusive use of a single customer (e.g. US Navy)
- might be built for many different customers (i.e. single engine trainers for a variety of flight schools)

### Each Order

- will be tracked and ledgered eternally (past, current, and future)
- will contain:
  - customer
  - order total (dollar amount)
  - items ordered
  - date(?)
  - order id

***

## Employee Management

### Each Employee

- has a job title
- has a list of projects they are assigned to
- has an amount of hours worked on each program
- may be associated with one or more engineering drawings/models for parts of each aircraft

### Each Drawing/Model

- is associated with one or more engineers
- is occasionally updated
- must have any changes tracked
- must have an indication as that the most current design is being used

***

## Ledgend

- (?) = Not Certain If Neccesary
- (*) = Potentially Complicated Sub-problem