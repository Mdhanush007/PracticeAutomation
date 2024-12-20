
# Flipkart Web Automation




## Overview
This project is an automated testing framework for the Flipkart website. It covers critical functionalities such as login, product search, add to cart. The framework ensures the website's stability and reliability through automated regression testing.
## Objective
Simulate an End-to-End product search to add cart workflow on Flipkart, covering diverse Selenium concepts.
## Technologies Used
- Programming Language: [Java]
- Automation Tool: [Selenium]
- Test Framework: [TestNG, JUnit]
- Build Tool: [Maven]
- Reporting Tool: [ExtentReports]

## Test Scenarios
The following scenarios are automated in this project:
1. User Login
2. Search Product
3. Add Product to Cart
4. Validate Cart Contents
5. Proceed to Checkout


---
 
### **Steps to Perform**:
 
1. **Open Flipkart Website**:
   - Launch the Flipkart homepage.
   - Maximize the browser window for better visibility.
 
   **Concepts Covered**:
   - Browser navigation (`get()`).
   - Window management (`maximize()`).
 
---
 
2. **Handle Login Popup**:
   - If a login popup appears, close it using the "X" button.
   - Ensure the test continues seamlessly if the popup doesn’t appear.
 
   **Concepts Covered**:
   - Dynamic element handling.
   - Exception handling for unpredictable UI elements.
 
---
 
3. **Search for a Product**:
   - Enter a product name (e.g., "iPhone") into the search bar.
   - Click on the search button to display results.
 
   **Concepts Covered**:
   - Locating elements using various strategies (`id`, `name`, `CSS`, `XPath`).
   - Performing actions on elements (`sendKeys`, `click`).
 
---
 
4. **Apply Filters**:
   - Filter the results by brand (e.g., "Apple"), price range, and ratings.
   - Verify if the filters are applied correctly.
 
   **Concepts Covered**:
   - Interacting with checkboxes and dropdowns.
   - Verifying page changes after user actions.
 
---
 
5. **Select a Product**:
   - Click on the first product in the filtered search results.
   - Verify that the product details page opens in a new tab.
 
   **Concepts Covered**:
   - Handling multiple elements with indexing.
   - Validating navigations within the web application.
 
---
 
6. **Switch to Product Details Tab**:
   - Switch the WebDriver context to the newly opened product tab.
   - Confirm the product details match the selected item.
 
   **Concepts Covered**:
   - Handling multiple browser tabs.
   - Managing WebDriver context.
 
---
 
7. **Add Product to Cart**:
   - Click on the "Add to Cart" button on the product details page.
   - Ensure the product is successfully added to the cart.
 
   **Concepts Covered**:
   - Button interactions (`click`).
   - Verifying post-action results.
 
---
 
8. **Proceed to Checkout**:
   - Navigate to the cart.
   - Verify that the correct product and quantity are present.
