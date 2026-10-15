# Sample Bug Reports

## BUG-01 - Invalid email format is accepted during checkout

**Environment:**  
Web application – Chrome, Windows 11

**Preconditions:**  
A product is added to the cart and the user is on the Checkout page.

**Steps to Reproduce:**
1. Open the Checkout page.
2. Enter `test@` in the Email field.
3. Click **Place Order**.

**Expected Result:**  
The system should reject the invalid email format, display a validation message, and prevent the order from being placed.

**Actual Result:**  
The system accepts the invalid email address and displays "Order confirmed".

**Severity:** Medium  
**Priority:** High

---

## BUG-02 - Duplicate €500 transfer occurs when Confirm is tapped twice

**Environment:**  
Mobile banking application – Android

**Preconditions:**  
User is logged in and has sufficient balance to complete a €500 transfer.

**Steps to Reproduce:**
1. Open the mobile banking application.
2. Initiate a transfer of €500.
3. Tap **Confirm** once.
4. While the application is unresponsive for approximately 2 seconds, tap **Confirm** again.

**Expected Result:**  
The application should process the €500 transfer only once and prevent duplicate submission while the transaction is being processed.

**Actual Result:**  
The application accepts the second tap and creates two separate €500 transfers.

**Severity:** Critical  
**Priority:** High

---

## BUG-03 - Typo displayed in Black Friday promotional banner

**Environment:**  
Web application – Chrome, Windows 11

**Preconditions:**  
User can access the e-shop home page.

**Steps to Reproduce:**
1. Open the e-shop home page.
2. Locate the Black Friday promotional banner.
3. Observe the campaign title.

**Expected Result:**  
The campaign title should be displayed as "BLACK FRIDAY – 50% OFF".

**Actual Result:**  
The campaign title is displayed as "BLACK FRDAY – 50% OFF".

**Severity:** Low  
**Priority:** High
