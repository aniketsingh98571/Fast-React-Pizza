## Pizza Delivery and Co.
### Functional Requirements:-

 - Users can order one or more pizzas from menu.
 - Requires no user accounts and no login, users just input their names before using the app.
 - The pizza menu can change, so it should be loaded from an API.
 - Users can add multiple pizzas to a cart before ordering.
 - Ordering requires just the user's name,phone number and address.
 - If possible, GPS location should also be provided to make delivery easier.
 - Users can mark their orders as "priority" for an additional 20% of the cart price.
 - Orders are made by sending a POST request with the order data (user data + selected pizza) to the API.
 - Payments are made on delivery,so no payment processing is necessary in the app.
 - Each Order will get unique ID that should be displayed so the user can later look up their orders based on ID.
 - Users should be able to mark their order as priority order even after it has been placed.

### Feature Categories:-
 - User
 - Menu
 - Cart
 - Order

### Necessary Pages

 - Home Page
 - Pizza Menu
 - Cart
 - Placing New Order
 - Old Orders history

### State Management

 - User : Global UI state
 - Menu: Global Remote state
 - Cart: Global UI state
 - Order: Global Remote state
