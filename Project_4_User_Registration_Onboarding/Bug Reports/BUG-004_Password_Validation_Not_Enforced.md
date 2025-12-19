## Bug ID
BUG-004

## Title
Password validation rules are not enforced during registration

## Environment
- Browser: Google Chrome
- OS: Windows 10
- Environment: Test

## Steps to Reproduce
1. Access registration page
2. Fill all mandatory fields
3. Enter a weak password (e.g., "123")
4. Submit the registration form

## Expected Result
System should block submission and display password complexity requirements.

## Actual Result
System accepts weak passwords without validation feedback.

## Severity
High

## Status
Open
