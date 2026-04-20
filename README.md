# Assignment2_Release-Based-Workflow-in-GitHub-Azure-Board
Software delivery project demonstrating GitHub collaboration workflow, release based versioning and Azure Boards integration with full traceability between work items, commits and pull requests.



## Add wishlist button on product cards 
- Each product card includes a wishlist button
- Users can add or remove products from the wishlist directly from the product list
- The wishlist button updates its state after each click 

## Product Detail Page
- Users can view the product description directly on the detail page
- Stock or availability information is clearly displayed
- Product details are structured and easy to read
- The layout improves overall usability and user experience


## Product Detail Page Layout
- Added basic structure for product detail page
- Includes title, image section, and description area


## Product Search
- Users can search products by keyword using the search bar
- Search results update dynamically as the user types
- Filters can be applied by category and price range

Cart Management
* Users can remove individual items from the cart using the Remove button
* Cart updates immediately after an item is removed
* An empty cart message is displayed when all items have been removed


## Product Search Bar
- A search input is clearly visible on the product listing page
- Users can type any keyword to search for products
- Matching products are displayed in the results as the search runs

## User Registration Form 
- New users can register through a dedicated registration form
- Name, email, and password fields are clearly visible and required
- Required fields are validated before submission
- A success message is displayed after successful registration
- Prevents submission if any required field is empty

## User Login Validation

- Added basic login validation check
- Prevents empty username and password submission
- Displays validation message for missing input

## Product Filtering

- Added filtering by category
- Added filtering by price range
- Users can narrow products using selected filters


##Search Results Handling

## Release v1.1 Updates


## Cart Quantity Controls
- Added increase (+) and decrease (−) buttons for cart items
- Users can adjust product quantity directly from the cart
- Quantity updates dynamically without refreshing the page

## Cart Quantity Validation
- Prevented quantity from going below 1
- Disabled decrease button at minimum limit
- Ensured consistent quantity updates across UI and backend

## Cart Interaction Improvements
- Improved responsiveness of quantity controls
- Added smooth UI updates when quantity changes
- Enhanced overall user experience when modifying cart items

## Real-Time Cart Price Updates
- Cart prices stay accurate as users adjust item quantities
- Each item's subtotal reflects the current quantity at all times
- The final cart total recalculates instantly with every change

- Added improvements and bug fixes for upcoming release


- Displays matching products based on user search input
- Updates search results dynamically as the user types
- Ensures relevant products are shown clearly in the results list

## Empty State Message

- Displays a message when no search results are found
- Helps users understand that no matching products exist
- Provides clear feedback instead of showing an empty screen

## Search UX Improvements
- Improves user experience with clear result feedback
- Handles both successful searches and no-result cases
- Ensures consistent UI behavior across all search scenarios

## Product Filtering by Category and Price
 
- Category filter is available to narrow products by type
- Price range filter allows users to set a minimum and maximum price
- Visible products update instantly after a filter is selected
- Filters can be combined to refine results further

## Mobile Responsiveness
- Product list page is fully responsive and works correctly on mobile
- Product detail page adapts to smaller screens without layout issues
- Cart page displays correctly on mobile with no broken layout
- Key pages are optimized for a smooth mobile shopping experience

TESTING SQUASH MERGE RULE - commit 1
Squash rule test - commit 2
Squash rule test - commit 3

## Squash Rule 
- Add project overview and release workflow summary 
- Document wishlist and product detail page features in README
