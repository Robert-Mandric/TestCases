# TestCases

Below are some test case samples that I wrote while working on previous projects.

------------------------------------------

**Description:**

Test the login by using correct credentials.

**Steps to Reproduce:**
1. Go to site.com/login
2. Add correct user/pass
3. Observe if user can login

**Expected Results:**

User should be able to login

**Test Data:**

-User: test

-Pass: 123

------------------------------------------

**Description:**

Test the login by not using correct credentials.

**Steps to Reproduce:**
1. Go to site.com/login
2. Add wrong user/pass
3. Observe if user can login

**Expected Results:**

User should not be able to login

**Test Data:**

-User: test1

-Pass: 123

------------------------------------------

**Description:**

Test the login by not using credentials.

**Steps to Reproduce:**
1. Go to site.com/login
2. Do not add user/pass
3. Observe if user can login

**Expected Results:**

User should not be able to login

**Test Data:**

------------------------------------------

**Description:**

Test the "Remember Me" checkbox.

**Steps to Reproduce:**
1. Go to site.com/login
2. Add the correct user/pass
3. Check the checkbox saying "Remember Me:"
4. Observe if the site remembers your credentials

**Expected Results:**

The site should remember your credentials

**Test Data:**

-User: test1

-Pass: 123

------------------------------------------

**Description:**

Test that the search results are displayed correctly on the page.

**Steps to Reproduce:**
1. Go to site.com/home
2. Add the name of a registered item
4. Observe if the search results are displayed correctly on the page

**Expected Results:**

The search results should be displayed correctly on the page

**Test Data:**

-Item

------------------------------------------

**Description:**

Test that the % sign in search keyword should not redirect to 404 ERROR.

**Steps to Reproduce:**
1. Go to site.com/home
2. Add the % sign to search bar
4. Observe if the search results does not redirect to 404 ERROR.

**Expected Results:**

The % sign in search keyword should not redirect to 404 ERROR.

**Test Data:**

-%
