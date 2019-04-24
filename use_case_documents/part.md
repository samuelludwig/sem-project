# Title: Part Use Case

***

**Created By:** Samuel Ludwig
**Date Created:** April 24th, 2019

**Last Updated By:** Samuel Ludwig
**Last Revision Date:** April 24th, 2019

***

**Description:** Use case for keeping track of part supplies and making sure enough are on hand at any one time. The "x amount of aircraft" referenced within the step-by-step is nothing more than a buffer, and can be changed depending on how quickly one may need to respond to a sudden influx of customer orders. This routine should be run every time aircraft and/or part inventories are updated.

**Step by Step:**

1. Determine the amount of parts needed to create x amount of each aircraft at any one time.
2. Determine if enough of the parts are on hand to create x amount of each aircraft.
   1. If not, order the parts necessary so that there will be enough on hand to create x amount of each aircraft.

**IO:**

Inputs: Part amounts, amount of each aircraft.
Outputs: Either no output, or an order is made -> depending on evaluation of step 2.

**Exceptions:**

- (2.1) The parts necessary may not be able to be ordered.
