# Test Case Samples

Here are a few examples of Test Cases that I wrote while studying on a QA course.

-------------------

**Title:**
Test login with correct credentials

**Description:**
Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to emag.ro/login
2. Add correct user/pass
3. Press login button

**Expected result:**
User should be able to login.

**Test Data:**
User: test & Pass: 123

-------------------

**Title:**
Test login with incorrect credentials

**Description:**
Test the login by using incorrect credentials.

**Steps to reproduce**
1. Go to emag.ro/login
2. Add incorrect user/pass
3. Press login button

**Expected result:**
User should not be able to login.

-------------------

**Title:**
Test login without any credentials

**Description:**
Test the login by leaving empty user/pass fields.

**Steps to reproduce:**
1. Go to emag.ro/login
2. Don't type any characters in user/pass fields
3. Press login button

**Expected result:**
User should not be able to login.

-------------------

**Title:**
Test login with correct credentials and "Remember Me" box checked

**Description:**
Test the login by using correct credentials and check the "Remember Me" box.

**Steps to reproduce:**
1. Go to emag.ro/login
2. Add correct user/pass
3. Check the "Remember Me" box
4. Press login button
5. Leave the site
6. Join the site
7. Observe if the credentials have been saved

**Expected result:**
User should be able to login and when he leaves the site and comes back again, he should be already logged in.

-------------------

**Title:**
Test search functionality

**Description:**
Test the search functionality by searching any product.

**Steps to reproduce:**
1. Go to emag.ro
2. Type any product in the search bar
3. Press search button

**Expected result:**
User should get the results of his product search.

---------------------

**Title:**
Test autocomplete function of search functionality

**Description:**
Test the autocomplete function of search functionality by typing the first letters of a product.

**Steps to reproduce:**
1. Go to emag.ro
2. Type just the first letters of any product in the search bar
3. Observe if the autocomplete function is suggesting the whole product name
4. Press search button

**Expected result:**
User should get the whole product name after typing just the first letters and should be able to see the product results.

---------------------

**Title:**
Test search functionality with a non existing product

**Description:**
Test search functionality by searching a product that doesn't exist.

**Steps to reproduce:**
1. Go to emag.ro
2. Type in the search bar the name of a product that does not exist
3. Press search button

**Expected result:**
The app will not give an error, but the user should get a message like: "0 results for the product that you are searching for".
