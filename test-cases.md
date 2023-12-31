# Test scenarious & cases

- [Test scenarious \& cases](#test-scenarious--cases)
  - [1. Test scenario: Translation Feature](#1-test-scenario-translation-feature)
    - [1.1. Test Case 1: Verify Translation Trigger](#11-test-case-1-verify-translation-trigger)
  - [2. Test scenario: Testing "Cart" Button Functionality](#2-test-scenario-testing-cart-button-functionality)
    - [2.1. Test Case 2.1: Verify "Cart" button](#21-test-case-21-verify-cart-button)
    - [2.2. Test Case 2.2: Verify Cart Counter with 0 Drinks](#22-test-case-22-verify-cart-counter-with-0-drinks)
    - [2.3. Test Case 2.3: Verify Cart Counter with Multiple Drinks](#23-test-case-23-verify-cart-counter-with-multiple-drinks)
    - [2.4. Test Case 2.4: Verify Cart Page Contents](#24-test-case-24-verify-cart-page-contents)
    - [2.5. Test Case 2.5: Verify Cart Page Contents with Multiple Drinks](#25-test-case-25-verify-cart-page-contents-with-multiple-drinks)
    - [2.6. Test Case 2.6: Verify Coffe is Add to "Cart"](#26-test-case-26-verify-coffe-is-add-to-cart)
    - [2.7. Test Case 2.7: Verify "Add to Cart" Dialog Openss](#27-test-case-27-verify-add-to-cart-dialog-openss)
  - [3. Test scenario: Testing "Total" Button with Different Cart Configurations](#3-test-scenario-testing-total-button-with-different-cart-configurations)
    - [3.1. Test Case 3.1: Empty Cart](#31-test-case-31-empty-cart)
    - [3.2. Test Case 3.2: Single Item is added to the Cart](#32-test-case-32-single-item-is-added-to-the-cart)
    - [3.3. Test Case 3.3: Multiple Items are added to the Cart](#33-test-case-33-multiple-items-are-added-to-the-cart)
    - [3.4. Test Case 3.4: Remove Items from the Cart](#34-test-case-34-remove-items-from-the-cart)
  - [4. Test scenario: Testing "Payment details" pop-up](#4-test-scenario-testing-payment-details-pop-up)
    - [Test Case 4.1: Verify that pop-up with "Payment details" is displayed after click on the "Total" buttom](#test-case-41-verify-that-pop-up-with-payment-details-is-displayed-after-click-on-the-total-buttom)
    - [Test Case 4.2: Verify Successful Form Submission](#test-case-42-verify-successful-form-submission)
    - [Test Case 4.3: Verify Name Field Validation](#test-case-43-verify-name-field-validation)
    - [Test Case 4.4: Verify Email Field Validation](#test-case-44-verify-email-field-validation)
    - [Test Case 4.5: Verify Order Updates and Promotional Messages Option](#test-case-45-verify-order-updates-and-promotional-messages-option)

##  1. Test scenario: Translation Feature

###  1.1. Test Case 1: Verify Translation Trigger

- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    1. A coffee is selected from the menu.
- **Steps:**
    1. Open the Aplication - https://coffee-cart.app/;
    1. Select coffee from the menu;
    1. Double-click on the coffee title;
- **Expected result:**
    - The coffee title should be translated to Chinese;
- **Result (Pass/Fail):** 
    - Pass

##  2. Test scenario: Testing "Cart" Button Functionality 

###  2.1. Test Case 2.1: Verify "Cart" button
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on the "Cart" section from the top menu.
- **Expected result:**
    - User is navigated to Cart page;
- **Result (Pass/Fail):**  
    - Pass

###  2.2. Test Case 2.2: Verify Cart Counter with 0 Drinks
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Observe the Cart counter.
- **Expected result:**
    - The counter should display "0." 
- **Result (Pass/Fail):**  
    - Pass

###  2.3. Test Case 2.3: Verify Cart Counter with Multiple Drinks
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    2. Multiple coffee drinks are selected.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Add multiple drinks to the Cart.
    3. Observe the Cart counter.
- **Expected result:**
    - The Cart counter should display the accurate quantity of drinks added to the Cart. 
- **Result (Pass/Fail):**
    - Pass 

###  2.4. Test Case 2.4: Verify Cart Page Contents
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    2. Coffee drink is not select. 
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;  
    2. Click on the "Cart" section from the top menu.
- **Expected result:**
    - A "No coffee, go add some" sign should appear.
- **Result (Pass/Fail):**
    - Pass

###  2.5. Test Case 2.5: Verify Cart Page Contents with Multiple Drinks
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    2. Multiple coffee drinks are selected.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/; 
    2. Click on multiply coffee drinks from the menu.
    3. Click on the "Cart" section from the top menu.
- **Expected result:**
    - The user should see the contents of their Cart, including the names, prices, and quantities of the added items.
- **Result (Pass/Fail):**
    - Pass

###  2.6. Test Case 2.6: Verify Coffe is Add to "Cart"
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on a coffee drink icon from the menu;
- **Expected result:**
    - The selected drink should be add to "Cart";
- **Result (Pass/Fail):**
    - Pass

###  2.7. Test Case 2.7: Verify "Add to Cart" Dialog Openss
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Right-click on a coffee icon;
- **Expected result:**
    - A conformation dialog should open, allowing the user to confirm or decline the selected coffee;
- **Result (Pass/Fail):**
    - Pass

##  3. Test scenario: Testing "Total" Button with Different Cart Configurations

###  3.1. Test Case 3.1: Empty Cart
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    2. The user has an empty cart.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Navigate to the "Total" button;
- **Expected result:**
    - The displayed total amount should be $0.00;
- **Result (Pass/Fail):**
    - Pass

###  3.2. Test Case 3.2: Single Item is added to the Cart
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    2. The user has one item in the cart.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on a coffee icon;
    3. Navigate to the "Total" button;
- **Expected result:**
    - The displayed total amount should match the price of the single item;
- **Result (Pass/Fail):**
    - Pass

###  3.3. Test Case 3.3: Multiple Items are added to the Cart
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    2. The user has multiple items in the cart.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on diffrent coffee drinks from the menu;
    3. Navigate to the "Total" button;
- **Expected result:**
    - The displayed total amount should be the sum of the prices of all items in the cart.;
- **Result (Pass/Fail):**
    - Pass

###  3.4. Test Case 3.4: Remove Items from the Cart
- **Precondition:**
    1. The user is on the Coffee Cart App webpage.
    2. The user has multiple items in the cart.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Hover on the "Total" button;
    3. Click on the minus button in the pop-up;
    4. Remove a coffee drink;
- **Expected result:**
    - The displayed total amount should be updated to reflect the new cart configuration;
- **Result (Pass/Fail):**
    - Pass

##  4. Test scenario: Testing "Payment details" pop-up

### Test Case 4.1: Verify that pop-up with "Payment details" is displayed after click on the "Total" buttom

- **Precondition:**
    1. The user is on the Coffee Cart App webpage and clicks the "Total" button.
- **Steps:** 
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on the "Total" button;
    3. A "Payment details" pop-up is displayed;
- **Expected result:**
    - A pop-up with "Payment details" shoul appear;
- **Result (Pass/Fail):**
    - Pass

### Test Case 4.2: Verify Successful Form Submission

- **Precondition:**
    1. The user is on the Coffee Cart App checkout page with the Payment Details form displayed.  
- **Steps:**  
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on the "Total" button;
    3. A "Payment details" pop-up is displayed; 
    4. Fill in the Name field with valid name;
    5. Fill in the Email field with valid email;
    6. Choose the option to receive order updates and promotional messages;
    7. Click the "Submit" button;     
- **Expected result:**
    - The form should be submitted successfully, and the user should see a confirmation message;
- **Result (Pass/Fail):**
    - Fail

### Test Case 4.3: Verify Name Field Validation

- **Precondition:**
    1. The user is on the Coffee Cart App checkout page with the Payment Details form displayed.
- **Steps:**
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on the "Total" button;
    3. A "Payment details" pop-up is displayed; 
    4. Leave the Name field empty;
    5. Fill in the Email field with valid email;
    6. Choose the option to receive order updates and promotional messages;
    7. Click the "Submit" button;  
- **Expected result:**
    - The form submission should fail, and an error message should indicate that the Name field is required;
- **Result (Pass/Fail):**
    - Pass

### Test Case 4.4: Verify Email Field Validation

- **Precondition:**
    1. The user is on the Coffee Cart App checkout page with the Payment Details form displayed.
- **Steps:**
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on the "Total" button;
    3. A "Payment details" pop-up is displayed; 
    4. Fill in the Name field with valid name;
    5. Leave the Email field empty;
    6. Choose the option to receive order updates and promotional messages;
    7. Click the "Submit" button;  
- **Expected result:**
    - The form submission should fail, and an error message should indicate that a valid Email address is required;
- **Result (Pass/Fail):**
    - Pass

### Test Case 4.5: Verify Order Updates and Promotional Messages Option

- **Precondition:**
    1. The user is on the Coffee Cart App checkout page with the Payment Details form displayed.  
- **Steps:**  
    1. Open the Aplication - https://coffee-cart.app/;
    2. Click on the "Total" button;
    3. A "Payment details" pop-up is displayed; 
    4. Fill in the Name field with valid name;
    5. Fill in the Email field with valid email;
    6. Choose not to receive order updates and promotional messages;
    7. Click the "Submit" button;     
- **Expected result:**
    - The form should be submitted successfully, and the user should not receive promotional messages or order updates unless explicitly chosen;
- **Result (Pass/Fail):**
    - Fail