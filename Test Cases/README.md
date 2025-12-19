# Test Cases — User Registration and Login

---

## TC-001 — User registration with valid data

**Precondition:** User is on registration page

**Steps:**
1. Open registration page
2. Enter valid name
3. Enter valid email
4. Enter valid password
5. Click Register

**Expected Result:**
User account is successfully created and confirmation message is displayed

---

## TC-002 — Registration with invalid password

**Precondition:** User is on registration page

**Steps:**
1. Enter valid name
2. Enter valid email
3. Enter password with less than 6 characters
4. Click Register

**Expected Result:**
Error message indicating invalid password is displayed

---

## TC-003 — Login with valid credentials

**Precondition:** User has a registered account

**Steps:**
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click Login

**Expected Result:**
User is redirected to dashboard
