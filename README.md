# Authentication Service #
Project Code: B0001

## Use Cases ##

## User Stories ##
 ### B0001-001: Register ###

 * Actor: User without account 
 * Pre Condition:
 1. User Should have a working gmail account which is not previously registered.

 * Input:

 1. Email.
 2. OTP through mail.
 3. Set  password with 8 characters(alphanumeric with at least one upper case and one lower case letter)

 * Sequence:

 1. User opens the Webpage and click on 'Register'.
 2. Then the registration page appears.
 3. User can enter his email ID.
 4. User gets otp through mail.
 5. An OTP entering screen appears and User can enter the OTP.
 6. Then set password screen appears and user should enter a password with 8 characters and should re enter the password in confirm password field.
 7. Now the user should enter his name and select geners.
 8. page displays success message and redirects to login page. 

 * Post Condition:
 1. Page displays Success Message and the login page appears.

 * Exceptions:

 1. Error is shown on the registration page if user enters invalid email-ID or mobile Number or password.
 2. If the email ID is already registered, "email Id is already registered" is shown on the page.
 3. The registration form shows "resend" if the otp is not entered within 1 minute.
 
 ### B0001-002: Forget Password ###

 * Actor: User forgot the password
 * Pre Condition:
 1. User Should have a registered  email ID

 * Input:

 1. Email ID.
 2. OTP through mail .
 3. Set  password with 8 characters(alphanumeric with at least one upper case and one lower case letter)

 * Sequence:

 1. User opens the Webpage and click on 'forget password'.
 2. A page appears with email field.
 3. User can enter his registered email ID.
 4. User gets otp through mail.
 5. An OTP entering screen appears and User can enter the OTP.
 6. Then set password screen appears and user should enter a password with 8 characters and should re enter the password in confirm password field.
 7. redirects to login page. 

 * Post Condition:
 1. login page appears.

 * Exceptions:

 1. Error is shown on the  page if user enters unregistered email-ID or password and takes to registration page.
 2. The page shows "resend" if the otp is not entered within 1 minute.


### B0001-003: Active account ###

 * Actor: User with active account
 * Pre Condition:
 1. User Should have a registered email ID
 2. password

 * Input:

 1. Email ID.
 2. Password

 * Sequence:

 1. User opens the login Webpage 
 2. User enters registered email  and password.
 3. User click on login button.
 4. Home page appears 

 * Post Condition:
 1. home page appears.

 * Exceptions:

 1. Error is shown on the  page if user enters unregistered email-ID  or password and takes to registration page.




### B0001-004: Logout ###

* Actor: User with active account

* Pre Condition:

1. User should have logged in to the account

* Input:

1. None

* Sequence:

1. User click on Logout.
2. Page displays a message 'successfully Logout' and the login page appears.

* Post Condition:

1. Login screen appears


* Exceptions:


 ### B0001-005: Delete Account ###
 * Actor: User with active account

* Pre Condition:

1. User should have logged in to the account

* Input:

1. None

* Sequence:

1. User click on Delete account.
2. Page displays a message 'successfully Deleted' and feed back page appears.

* Post Condition: feed back page appears and then to redirects to login page.

1. Login screen appears

### B0001-006: Update Profile ###
* Actor: User to update profile

* Pre Condition:

1. User Should have logged in to the account
 
* Input:
1. None
* Sequence:
1. User click on Update profile.
2. Page displays a name field to edit.
3. After editing user clicks on Save button.
4. Page displays a message 'successfully Updated'.





 


