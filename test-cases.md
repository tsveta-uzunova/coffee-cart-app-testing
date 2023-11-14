# Test scenarious & cases

## Test scenario: Translation Feature

### Test Case 1.1: Verify Translation Trigger
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. A coffee is selected from the menu.
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/;
 2. Select coffee from the menu;
 3. Double-click on the coffee title;
 * Expected result:
 1. The coffee title should be translated to Chinese;
* Pass / Fail: Pass;

## Test scenario: Testing "Cart" Button Functionality 

### Test Case 2.1: Verify "Cart" button
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/;
 2. Click on the "Cart" section from the top menu.
 * Expected result:
 1. User is navigated to Cart page;
 * Pass / Fail: Pass;

### Test Case 2.2: Verify Cart Counter with 0 Drinks
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/;
 2. Observe the Cart counter.
 * Expected result:
 1. The counter should display "0." 
 * Pass / Fail: Pass; 

### Test Case 2.3: Verify Cart Counter with Multiple Drinks
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. Multiple coffee drinks are selected.
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/;
 2. Add multiple drinks to the Cart.
 3. Observe the Cart counter.
 * Expected result:
 1. The Cart counter should display the accurate quantity of drinks added to the Cart. 
 * Pass / Fail: Pass; 

### Test Case 2.4: Verify Cart Page Contents
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. Coffee drink is not select. 
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/;  
 2. Click on the "Cart" section from the top menu.
 * Expected result:
 1. A "No coffee, go add some" sign should appear.
 * Pass / Fail: Pass;

### Test Case 2.4: Verify Cart Page Contents with Multiple Drinks
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. Multiple coffee drinks are selected.
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/; 
 2. Click on multiply coffee drinks from the menu.
 3. Click on the "Cart" section from the top menu.
 * Expected result:
 1.The user should see the contents of their Cart, including the names, prices, and quantities of the added items.

### Test Case 2.5: Verify Coffe is Add to "Cart"
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/;
 2. Click on a coffee drink icon from the menu;
 * Expected result:
 1. The selected drink should be add to "Cart";
 * Pass / Fail: Pass;

 ### Test Case 2.6: Verify "Add to Cart" Dialog Opens
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
 * Steps: 
 1. Open the Aplication - https://coffee-cart.app/;
 2. Right-click on a coffee icon;
 * Expected result:
 1. A conformation dialog should open, allowing the user to confirm or decline the selected coffee;
  * Pass / Fail: Pass;

## Test scenario: Testing "Total" Button with Different Cart Configurations

### Test Case 3.1: Empty Cart
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. The user has an empty cart.
* Steps: 
1. Open the Aplication - https://coffee-cart.app/;
2. Navigate to the "Total" button;
* Expected result: 
1. The displayed total amount should be $0.00;
* Pass / Fail: Pass;

### Test Case 3.2: Single Item is added to the Cart
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. The user has one item in the cart.
* Steps: 
1. Open the Aplication - https://coffee-cart.app/;
2. Click on a coffee icon;
3. Navigate to the "Total" button;
* Expected result: 
1. The displayed total amount should match the price of the single item;
* Pass / Fail: Pass;

### Test Case 3.3: Multiple Items are added to the Cart
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. The user has multiple items in the cart.
* Steps: 
1. Open the Aplication - https://coffee-cart.app/;
2. Click on diffrent coffee drinks from the menu;
3. Navigate to the "Total" button;
* Expected result: 
1. The displayed total amount should be the sum of the prices of all items in the cart.;
* Pass / Fail: Pass;

### Test Case 3.3: Remove Items from the Cart
1. **Precondition:**
1.1. The user is on the Coffee Cart App webpage.
1.2. The user has multiple items in the cart.
* Steps: 
1. Open the Aplication - https://coffee-cart.app/;
2. Hover on the "Total" button;
3. Click on the minus button in the pop-up;
4. Remove a coffee drink;
* Expected result: 
1. The displayed total amount should be updated to reflect the new cart configuration;
* Pass / Fail: Pass;