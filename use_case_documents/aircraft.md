# Title: Aircraft Use Case

***

**Created By:** Samuel Ludwig
**Date Created:** April 15th, 2019

**Last Updated By:** Samuel Ludwig
**Last Revision Date:** April 27th, 2019

***

**Description:** Use case for combining aircraft-parts to create an aircraft product.

**Step by Step:**

 1. Verify the ID of the aircraft, if one is not present, assign a new ID.
 2. Verify the parts needed to create the aircraft.
 3. Verify that the parts to create the aircraft are on hand and in the necessary amount.
 4. Combine parts according to engineer instruction to create the aircraft.
 5. Verify that inventory is updated for aircraft and parts on hand.

**IO:**

- Input: Aircraft parts.
- Output: Constructed aircraft.

**Exceptions:**

- (3): Parts are not on hand.