# BugsExample
This document includes writing bug reports.

---------------------------------------------------------------

### Application under test:    *[Product Store](https://www.demoblaze.com/index.html)*   

---------------------------------------------

**Description:** <br>
[Product section] The user cannot see more pictures of the product.

**Preconditions:** <br>
Navigate to https://www.demoblaze.com/index.html

**Steps to reproduce:**
1. Click on the Samsung galaxy s6 card
2. Click on the displayed Samsung galaxy s6 image

**Expected result:** <br>
The image enlarges and more photos of the product can be seen.

**Actual result:** <br>
Nothing happens when you click on the image.

--------------------------------------------------------------------

**Description:** <br>
[Product section] The slide with the images representing the product does not work.

**Preconditions:** <br>
Navigate to https://www.demoblaze.com/index.html

**Steps to reproduce:**
1. Click on the "Nokia lumia 1520"
2. Click on the white underline buttons on the displayed phone image.

**Expected result:** <br>
Another image of the chosen product will be displayed.

**Actual result:** <br>
No other image is displayed to the user.

-----------------------------------------------------------------------

**Description:** <br>
[Contact section] The contact form accepts an invalid email address.

**Preconditions:** <br>
Navigate to https://www.demoblaze.com/index.html

**Steps to reproduce:**
1. Click on the "Contact" section of the displayed menu
2. Provide an invalid email address
3. Provide a valid "Contact Name"
4. Provide a valid "Message"
5. Click on the button "Send message"

**Expected result:** <br>
A warning message will be displayed under the "Contact email address" field with the message: "Enter a valid email address"

**Actual result:** <br>
The form is submitted. A pop-up with the message "Thanks for the message!!" is displayed.

**Attachments:** <br>

<img src="RaportDeBuguriPentruGitPOZE/images/Bug-ContactSection-WrongEmail.PNG" width="400" height="300" alt="The contact form accepts an invalid email address">


*Notes* **Test data:** Contact Email: aaaaaaaaaaaaaaaaaaaaaaaaa  / Contact Name: Ionescu Ion / Message: This is my message.

--------------------------------------------------------------------------------------------------

**Description:** <br>
[Cart section] The "Place Order" form accepts an invalid card number.

**Preconditions:** <br>
Navigate to https://www.demoblaze.com/index.html
Add at least one product to the shopping cart.

**Steps to reproduce:**
1. Click on the "Cart" section of the displayed menu
2. Click on the button "Place Order"
3. Enter only an invalid "Name" and "Credit card", leaving the other fields empty.
4. Click on the "Purchase" button

**Expected result:** <br>
Warning messages will be displayed under each field.

**Actual result:** <br>
The form is submitted. A success message is displayed on the screen.

**Attachments:** <be>

<img src="RaportDeBuguriPentruGitPOZE/images/Bug-CartSection-WrongName&CreditCard.PNG" width="400" height="300" alt="The Place Order form accepts an invalid card number">




*Notes* **Test data:** Name: eeeeeeeeeeeeeee / Credit card: pppppppppppppppppppppppppp

-----------------------------------------------------------------------------------------------------------

**Description:** <br>
[Sign up section] The user can create an account using an invalid username

**Preconditions:** <br>
Navigate to https://www.demoblaze.com/index.html

**Steps to reproduce:**
1. Click on the "Sign up" section of the displayed menu
2. Provide an invalid "Username"
3. Provide a valid password
4. Click on "Sign up" button

**Expected result:** <br>
A warning message will be displayed under the "Username" field.

**Actual result:** <br>
The account is created. A success message is displayed: "Sign up successful."

**Attachments:** <be>

<img src="RaportDeBuguriPentruGitPOZE/images/Bug-SignUp.PNG" width="400" height="300" alt="The user can create an account using an invalid username">


-----------------------------------------------------------------------------------------------------------




