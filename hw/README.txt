Usecase Name: Order a product.
Usecase ID: 12345678.
Date: 24/03/2015.

Description: A user clicks on the 'Buy Now' button from a specific product page.

Actors: Main actor: User/Registered user.
        Stake Holder: 1. Seller User.
					  2. Credit Card Company and/or 3rd party defrayal services company.
						{please note - it can be both CC and 3rd party company interest since sometimes you buy 'money' at the defrayal services company WITH YOUR credit card.

(incl. main actor and stakeholders)

Success criterion: 1. Buyer user has been successfully completed the purchase process.
				   2. Seller user has received the payment.
				   3. Product has been successfully shipped and arrived to the buyer.
		 Optional: 4. Buyer is happy with his new product & positively feedbacks the seller.

Post-conditions:    1. User is registered. (If not - redirect user to login screen and from there to the purchasing screen).
					2. User is not blocked/prevented from purchasing.

Flow				1. Registered User is exploring the online shop.
					2. User finds what he wants to buy.
					3. User read some of the product's reviews and decides to buy the product.
					4. User selects to directly buy the product.
					5. User is redirected to the buying screen.
					6. Credit card/Pay-pal/etc. details are being authenticated.
					7. Purchase is completed.
					8. Credit card/... company deposit the ammount of money at the seller user account.
					9. Seller ships the product through the relevant posting type.
					10. User recieves the product at the estimated time.

Alterntive Flows: 1. If user is not registered - upon selecting to buy the product he is redirected to the registration page.
				  1-b. If user is not registered - he still has the option to complete the purchase process WITHOUT SIGNING-UP.
				  4. User does not buying this specific product only, but adds it to the cart and continue shopping, eventually - step 4 will take place.
				  

Exceptions:	  