Usecase Name: Check out
Usecase ID: 001.
Date: 29/03/2015.

Description: on the cart page that contains at least one product, the registered user clicks on the ‘check out’ button .

Actors: 
Main actor: Registered user.
        Stake Holder: 1. Credit Card approver.
          2. Inventory Management System. 

Success criterion: 1. Registered user finished shopping and has at least one item in the cart.
      2. Registered user is directed to the shopping cart page and click on the ‘check out’  button. 
      3. Credit Card approver system has approved the payment method successfully.
      4. Registered user gets a message that his order has been paid and waiting to be shipped. 

Post-conditions:    1. User is registered. (If not - redirect user to login screen and from there to the purchasing screen).
      2. User is not blocked/prevented from purchasing.

Flow:       1. Registered User is exploring the products online.
      2. User finds what he wants to buy.
      3. User decides to buy a product based on the reviews.
      4. User is redirected to the shopping cart page.
                              5. User clicks on the check out button after making sure the items are what he wanted in the first place.
      6. Credit card/Pay-pal/etc. details are being authenticated.
      7. Purchase is completed, the User receives an email and a pop-up page that his order is paid successfully and is waiting to be shipped.
      8. Credit card/... company deposit the amount of money at the seller user account.
      9. Seller ships the product through the relevant address.
    10. User receives the product at the estimated time.

Alternative Flows: 1. If user is not registered - upon selecting to buy the product he is redirected to the registration page.
    2. If the Credit Card approver system fails then the User gets a pop-up message why the payment has failed.
