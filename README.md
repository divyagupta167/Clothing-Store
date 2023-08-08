# Clothing-Store

This is a simple shopping cart web application implemented using HTML, CSS, and JavaScript. The application allows users to view a list of items in a shop, add items to their shopping cart, adjust item quantities, remove items from the cart, and view the total bill. The shopping cart data is stored in the browser's local storage to persist the cart's state across sessions.

#How to Use the Application

Clone the Repository: Clone this repository to your local machine.

Open the index.html file in your web browser: After cloning, navigate to the repository folder and open the index.html file in your preferred web browser.

View Shop Items: Upon opening the application, you'll see a list of shop items displayed. Each item includes its name, description, price, and an image. The user can view these items in the shop and decide which ones they want to add to their shopping cart.

Add Items to Cart: To add an item to the cart, click the plus icon ('+') next to the item's quantity. The item's quantity will be updated in the cart, and the cart's total item count will be displayed in the cart icon in the top right corner of the page.

Adjust Item Quantity: If the user wants to increase or decrease the quantity of an item in the cart, they can do so by clicking the plus or minus icons ('+'/'-'). The cart's total item count will be updated accordingly.

Remove Items from Cart: To remove an item from the cart, click the 'x' icon next to the item in the cart. The item will be removed from the cart, and the cart's total item count will be updated.

View Total Bill: The total bill for all items in the cart will be displayed at the bottom of the cart section. It shows the sum of the prices of all items multiplied by their respective quantities.

Checkout and Clear Cart: If there are items in the cart, the user can click the "Checkout" button to proceed with the payment. They can also click the "Clear Cart" button to remove all items from the cart.

#Technical Details

The application is built using HTML, CSS, and JavaScript. The main logic of the shopping cart functionality is implemented in the JavaScript code. The shopping cart data is stored in the browser's local storage, allowing the cart to retain its state even if the user refreshes the page or closes the browser.

The generateShop() function dynamically generates the shop items' HTML and displays them on the page. The increment(), decrement(), and removeItem() functions handle the logic for adding, removing, and adjusting item quantities in the cart. The calculation() function updates the cart's total item count, and the TotalAmount() function calculates and displays the total bill of the items in the cart.

The application uses Font Awesome and Bootstrap icons for the plus, minus, and remove icons. The overall design is simple and responsive, making it suitable for both desktop and mobile devices.

 This application is a basic demonstration of a shopping cart and doesn't include actual payment processing or product ordering functionalities.
