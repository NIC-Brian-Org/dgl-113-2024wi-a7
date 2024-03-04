# DGL 113 2024WI Assignment #7

Add the required code to implement the following functionality:

1. Add an item to the drink order. Add the logic to determine
   if an item with the same size and description already appears
   in the order. If so, then consolidate the quantities. For
   example, if order already contains "3 Venti Earl Grey Tea"
   and the the customer adds "4 Venti Earl Grey Tea", then
   the resulting order should only have one order item for
   "Venti Earl Grey Tea" with quantity "7".
1. Delete an item from the drink order.
1. Modify an item in the drink order. If the user clicks on
   the "Quantity", "Size", or "Description" of an existing
   order item, change the presentation to a select input
   control so that the user can select a new "Quantity",
   "Size", or "Description" for that order item. After the
   user chages their selection, update the order. If the
   user changes the "Size" or "Description", be sure
   to consildate the quantities (like for adding an item).

**Remember that:**

- Short, Tall, Grande, and Venti coffees cost 2.99, 3.19, 3.49 and 3.99 respectively, and
- Short, Tall, Grande, and Venti teas cost 2.85, 3.05, 3.25, and 3.50 respectively.

NOTE: Only modify the `docs/app.js` file.
Do not make changes to any other files.
