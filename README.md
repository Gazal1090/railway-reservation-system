# railway-reservation-system

## Demo

![demo](https://github.com/pranjalibajpai/railway-reservation-system/blob/master/demo1.gif)

## Things Done & Assumptions Made
- Admins are added in the table - admins manually

## Validations
- Password - minimun 8 characters
- Username - Must contain letters only
- Full Name, Address - must not be empty
- Email - should be valid and not empty
- For login (both admins & users) Username & Password should not be empty & must be valid
- If user/admin logouts then access the page through URL then Access is Denied

## ToDo
- [ ] Change type="text" to type="password" in admin-login.php, index.php, register.php to Hide Password
- [ ] Add condition to all queries if query is not executed / throws an error
- [ ] Hash algo is needed to store password in database
