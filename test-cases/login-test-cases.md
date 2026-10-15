# Login Test Cases

## TC01 - Login with valid credentials

**Precondition:**  
A registered and active user account exists.

**Steps:**
1. Open the Login page.
2. Enter a valid username.
3. Enter a valid password.
4. Click Login.

**Expected Result:**  
The user should log in successfully and be redirected to the Products page.

---

## TC02 - Login with invalid password

**Steps:**
1. Open the Login page.
2. Enter a valid username.
3. Enter an invalid password.
4. Click Login.

**Expected Result:**  
The login should fail and an appropriate error message should be displayed.

---

## TC03 - Login with invalid username

**Steps:**
1. Open the Login page.
2. Enter an invalid username.
3. Enter a valid password.
4. Click Login.

**Expected Result:**  
The login should fail and an appropriate error message should be displayed.

---

## TC04 - Login with empty credentials

**Steps:**
1. Open the Login page.
2. Leave the username field empty.
3. Leave the password field empty.
4. Click Login.

**Expected Result:**  
The system should prevent login and display a validation message.

---

## TC05 - Login with empty password

**Steps:**
1. Open the Login page.
2. Enter a valid username.
3. Leave the password field empty.
4. Click Login.

**Expected Result:**  
The system should prevent login and display a message that the password is required.
