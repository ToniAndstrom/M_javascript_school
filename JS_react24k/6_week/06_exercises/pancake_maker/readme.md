# Build a Pancake Maker with dynamic pricing

## Step 2

Elevate the application by integrating a feature that displays a detailed summary of the pancake order, capturing the essence of customer preferences and calculated total price.

1. Capture user interactions: Implement event listeners to react to button clicks, initiating the display of the order summary.
2. Accurate Price Calculation: Refine the pricing logic to account for:

- The base price of the selected pancake variety.
- Incremental costs of chosen toppings and extras, efficiently tracking these selections for a granular order breakdown.

3. Order Composition Tracking: Employ arrays to manage the selection and deselection of toppings and extras, ensuring a dynamic adjustment of the order's content and total price.
4. Order Summary Display: Upon actioning a designated button, present an exhaustive summary that outlines:

- The name of the customer placing the order.
- The chosen type of pancake, articulated clearly.
- A comprehensive list of selected toppings and extras.
- The final calculated total price.
- Adopt a presentation style reminiscent of an invoice for enhanced clarity and professionalism.

## Step 3

Utilize Object-Oriented Programming to introduce advanced order management features, enabling the tracking of multiple orders, updating order statuses, and displaying orders on a separate management page.

1. Implement an order class:

- Define an Order class to encapsulate the properties and methods associated with a pancake order, including customer name, pancake type, toppings, extras, total price, and completion status.
- The class should provide methods to calculate the total price, add or remove toppings and extras, and toggle the completion status of the order.

2. Manage Multiple Orders:

- Develop a system to track multiple orders using an array. This system should support adding new orders, updating existing ones, and marking orders as completed.

3. Create a Separate Order Management Page:

- Design and implement a separate HTML page dedicated to order management. This page should list all orders with their details and allow administrative actions such as marking orders as completed.
- Ensure there's a way to navigate between the order placement page and the order management page.

4. Incorporate Order Interaction on the Management Page:

- On the order management page, enable functionality to update the status of orders. Implement UI elements (such as buttons or checkboxes) to mark orders as completed, reflecting these changes in the system and the UI.

5. Persist orders between sessions:

Optionally, for a more advanced challenge, implement functionality to save orders to local storage, allowing orders to persist across browser sessions.
