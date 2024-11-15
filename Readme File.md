"#SQA_Automation_Assignment#"

Test 01: Locked Out User Login Verification
Navigate to the Sauce Demo login page.
Enter locked_out_user as the username.
Enter secret_sauce as the password.
Click the login button.
Verify an error message displays, confirming the user is locked out.

Test 02: Standard User Full Purchase Flow
Navigate to the Sauce Demo login page.
Log in with standard_user and secret_sauce.
Reset App State by opening the hamburger menu and selecting "Reset App State."
Add Products:
Add three items to the cart.
Navigate to Cart and verify the added products.
Checkout:
Proceed to checkout and enter user information.
Verify the product names and the total price on the overview page.
Finish Purchase:
Complete the order and verify the successful order message.
Reset App State again and log out.

Test 03: Performance Glitch User Purchase Flow
Navigate to the Sauce Demo login page.
Log in with performance_glitch_user and secret_sauce.
Reset App State using the hamburger menu.
Sort Products by name in descending order (Z to A).
Add Product:
Add the first product in the sorted list to the cart.
Navigate to Cart and proceed to checkout.
Checkout:
Enter user information and verify the product name and total price.
Finish Purchase:
Complete the order and verify the successful order message.
