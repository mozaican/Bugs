# Bug Report Samples

Below are some bug report samples that I created.

------------------------

**Title:**
No picture shown for exceeded coffee intake

**Description:**
No picture is displayed after exceeding the daily maximum intake of coffee.

**Steps to reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Add 4 as input for the cups of coffee

**Expected result:**
When the coffee intake has exceeded the daily maximum a picture should be displayed.

**Actual result:**
No picture shown when the coffee intake has exceeded the daily maximum.

![image](https://user-images.githubusercontent.com/20253982/203814518-cd39431d-b296-47d0-ae06-f9f317b3b492.png)

------------------------

**Title:**
Decimal numbers accepted as inputs in Consumption Calculator

**Description:**
Decimal numbers are accepted as inputs for numbers of coffees and cigarettes in Consumption Calculator.

**Steps to reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Enter a decimal number as input for cups of coffee and cigarettes

**Expected result:**
Just integers should be accepted as inputs for numbers of coffees and cigarettes consumed. 

**Actual result:**
Decimal numbers are accepted as inputs for numbers of coffees and cigarettes.

![image](https://user-images.githubusercontent.com/20253982/203808190-190bb6ba-a259-43d0-8878-5d16e521d888.png)

------------------------

**Title:**
Failed to load browser tab icon on Fieni website

**Description:**
The specific browser tab icon for https://fieni.ro/ is missing, the image can't be loaded.

**Steps to reproduce:**
1. Go to https://fieni.ro/ 
2. Press F12 and go to the Console tab
3. Look for the error message: 'Failed to load resource: the server responded with a status of 404 () - /favicon.ico:1'
4. Observe the default browser tab icon that is displayed

**Expected result:**
A specific browser tab icon should be displayed after the page is loaded.

**Actual result:**
The default browser tab icon is being displayed.

![image](https://user-images.githubusercontent.com/20253982/203779636-083fe3d0-1737-4011-b562-1a294ee0617f.png)

--------------------------------------

**Title:**
Unresponsive section on Fieni homepage

**Description:**
On Samsung Galaxy S20 Ultra the homepage is not displayed properly, it has a section with text and button that are not visible.

**Steps to reproduce:**
1. Go to https://fieni.ro/ 
2. Press F12
3. Press Toggle Device Toolbar button (or Ctrl+Shift+M)
4. Select Samsung Galaxy S20 Ultra device
5. Scroll until the text and button are shown

**Expected result:**
The text and button should be visible on the page.

**Actual result:**
The text and button are not entirely visible, the user can't read the whole text.

![image](https://user-images.githubusercontent.com/20253982/203802170-a9139b06-839a-48ac-a4d8-6214f4d132a9.png)

--------------------------------------

**Title:**
Missing 404 custom page on Demoblaze 

**Description:**
There is no '404 - Not Found' custom page on Demoblaze

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/
2. Type something random at the end of the url (eg. https://www.demoblaze.com/jhkhgfjgff)
3. Press Enter

**Expected result:**
A customized '404 - Not Found' page should be displayed if no page is found.

**Actual result:**
The '404 - Not Found' page contains an error message, unfriendly to the user.

![image](https://user-images.githubusercontent.com/20253982/203779310-9c141eb2-6bce-4bfa-8ae0-f36b389333e0.png)

--------------------------------------

**Title:**
Purchase functionality works with no products in cart 

**Description:**
The purchase functionality works and a 'thank you for your purchase' message is displayed without products in cart

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/cart.html
2. Press 'Place Order' button
3. Fill required 'Name' and 'Credit card' fields in the form
4. Press 'Purchase' button

**Expected result:**
The 'Place Order' button should not work without products in cart and an error/warning message should be displayed if it is pressed.

**Actual result:**
Without products in cart the user can complete the purchase. 

![image](https://user-images.githubusercontent.com/20253982/203816765-096674da-0845-429e-8846-92cc677a2b09.png)

--------------------------------------

**Title:**
Navigation bar not aligned properly

**Description:**
The navigation bar on Demoblaze is not aligned properly on page.

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/

**Expected result:**
The right side and the left side of the nagivation bar should be symmetrically aligned on the page.

**Actual result:**
The layout of the nagivation bar is disproportionally aligned and it looks bad.

![image](https://user-images.githubusercontent.com/20253982/203800620-a16d70ca-77b7-4554-a6c1-3347273e697c.png)

--------------------------------------

**Title:**
Unresponsive navigation bar design

**Description:**
The navigation bar for page https://www.demoblaze.com/ becomes unresponsive for some device screens (tested on Surface Pro 7).

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/
2. Press F12
3. Press Toggle Device Toolbar button (or Ctrl+Shift+M)
4. Select Surface Pro 7 device screen

**Expected result:**
The navigation bar should be visible and displayed properly on the page.

**Actual result:**
The navigation bar is hidden. 

https://www.awesomescreenshot.com/image/37195068?key=015dbf4f01cfec0eea5f214ebefdce27
