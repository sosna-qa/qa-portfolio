# SauceDemo Test Cases

## TC01 – Login with valid credentials

**Steps**
1. Open https://www.saucedemo.com
2. Enter username: standard_user
3. Enter password: secret_sauce
4. Click Login button

**Expected Result**
User is redirected to the products page.

---

## TC02 – Login with invalid credentials

**Steps**
1. Open login page
2. Enter username: wrong_user
3. Enter password: wrong_password
4. Click Login

**Expected Result**
Error message appears: "Username and password do not match"

---

## TC03 – Login with empty fields

**Steps**
1. Open login page
2. Leave username empty
3. Leave password empty
4. Click Login

**Expected Result**
Validation error message appears.

---

## TC04 – Verify products list is displayed

**Steps**
1. Login with valid credentials

**Expected Result**
Products list is visible with names, prices and "Add to cart" buttons.

---

## TC05 – Sort products by price (low to high)

**Steps**
1. Login
2. Select sorting option "Price (low to high)"

**Expected Result**
Products are sorted from lowest price to highest.

---

## TC06 – Sort products by name (A to Z)

**Steps**
1. Login
2. Select sorting option "Name (A to Z)"

**Expected Result**
Products are sorted alphabetically.

---

## TC07 – Add product to cart

**Steps**
1. Login
2. Click "Add to cart" for any product

**Expected Result**
Cart icon shows number "1".

---

## TC08 – Add multiple products to cart

**Steps**
1. Login
2. Add two products to cart

**Expected Result**
Cart icon shows number "2".

---

## TC09 – Remove product from cart

**Steps**
1. Login
2. Add product to cart
3. Click "Remove"

**Expected Result**
Product is removed and cart counter updates.

---

## TC10 – Open cart page

**Steps**
1. Login
2. Add product to cart
3. Click cart icon

**Expected Result**
Cart page opens and added product is visible.

---

## TC11 – Checkout with valid data

**Steps**
1. Add product to cart
2. Open cart
3. Click Checkout
4. Enter first name, last name, postal code
5. Click Continue

**Expected Result**
Checkout overview page is displayed.

---

## TC12 – Checkout with missing data

**Steps**
1. Add product to cart
2. Go to checkout
3. Leave fields empty
4. Click Continue

**Expected Result**
Validation error appears.

---

## TC13 – Complete order

**Steps**
1. Complete checkout
2. Click Finish

**Expected Result**
Order confirmation page appears.

---

## TC14 – Cart persists after refresh

**Steps**
1. Add product to cart
2. Refresh page

**Expected Result**
Product remains in cart.

---

## TC15 – Logout from application

**Steps**
1. Login
2. Open menu
3. Click Logout

**Expected Result**
User is redirected to login page.
