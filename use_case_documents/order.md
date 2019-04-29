# Title: Customer Order Use Case

***

**Created By:** Samuel Ludwig
**Date Created:** April 24th, 2019

**Last Updated By:** Samuel Ludwig
**Last Revision Date:** April 27th, 2019

***

**Description:** Use case for creating and tracking customer orders for aircraft.

**Step by Step:**

1. Record the name of the customer, the items ordered, the dollar total of the order, and the date of the order.
2. Verify that the order can be fufilled.
3. Create Order form using the information recorded in step 1, with an added unique Order_Id Number.
4. Insert Order into database.

**IO:**

Inputs: Customer Information, Order Information.
Outputs: Order entry.

**Exceptions:**

- (2) Order cannot be fufilled.