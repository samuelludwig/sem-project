# Title: Drawing/Model Update Use Case

***

**Created By:** Samuel Ludwig
**Date Created:** April 28th, 2019

**Last Updated By:** Samuel Ludwig
**Last Revision Date:** April 28th, 2019

***

**Description:** Use case detailing how Part Drawings/Models will be tracked and managed in the system when they are updated.

**Step by Step:**

1. Verify name of part and its ID number.
2. Verify associated engineers.
3. Make desired changes to the drawing/model.
4. Append date and name of author that made the change to the edit history.
5. Push the update of the drawing/model to the database.

**IO:**

Inputs: Drawing/Model form, changes to Drawing/Model.
Outputs: Drawing/Model form in database is updated.

**Exceptions:**

- (1) Drawing/Model does not have a database entry.
- (1 + 2) Information cannot be verified or is incorrect.