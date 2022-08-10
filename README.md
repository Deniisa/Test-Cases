# Test Case Samples

Below are some test case samples that I wrote during my QA course.

------------------------------------------------------------------
**Title**
Test login with correct credentials

**Description:**
Check if the login works when a person uses incorrect user/pass.

**Steps to reproduce:**
1. Go to www.website.com/login
2. Add an incorrect user/pass
3. Press Login button

**Expected result:**
User shouldn't be able to login and it gets an error message.

**Test data:**
User: denisapop93@gmail.com
Pass: 1234 

-----------------------------------------------------------------------
**Title**
SQL Injection

**Description:**
Check if the login works when a person uses malicious code for user/pass.

**Steps to reproduce:**
1. Go to www.website.com/login
2. In the username field add a single quote
3. Press the Login button

**Expected result:**
User shouldn't be able to login and it gets an error message.

**Test data:**
User: '

----------------------------------------------------------------------------------
**Title**
Test search with valid product name

**Description:**
Check if the search works when a person uses a valid product name.

**Steps to reproduce:**
1. Go to www.emag.ro
2. Add a valid product name in the seach field
3. Press the search button

**Expected result:**
A page should display the results for the selected product.

**Test data:**
Product searched: Iphone

-------------------------------------------------------------------------------
**Title**
Test the clear seach button

**Description:**
Check if the clear search button works.

**Steps to follow:**
1. Go to www.emag.ro
2. Type a text in the search box
3. Press the clear search button

**Expected result:**
Once pressed, the clear search button should remove the text from the search box.

--------------------------------------------------------------------------------------------
**Title**
Enter nothing in the search box

**Description:**
Check what happens if you click/press on the search button with no data in the search box.

**Steps to reproduce:**
1. Go to www.emag.ro
2. Click/Press on the search button

**Expected results:**
It should show the same page without refresing the page.
