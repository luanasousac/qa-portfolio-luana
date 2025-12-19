# Test Cases — Login and Password Recovery

---

## TC-001 — Login with valid credentials

Precondition: User has a registered account

Steps:
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click Login

Expected Result:
User is successfully authenticated and redirected to dashboard

---

## TC-002 — Login with invalid password

Steps:
1. Enter valid email
2. Enter invalid password
3. Click Login

Expected Result:
Error message displayed indicating invalid credentials

---

## TC-003 — Password recovery with registered email

Steps:
1. Click "Forgot password"
2. Enter registered email
3. Submit request

Expected Result:
Password recovery email is sent successfully
