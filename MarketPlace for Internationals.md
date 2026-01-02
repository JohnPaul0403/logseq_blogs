# A MarketPlace Infrastructure for Foreign Nationals in Korea
- This app main purpose is to create a Marketplace available and easy-to-use for foreign nationals, the platform itself will be mainly tight to the idea of helping people buy and sell things in a easy and secure manner all in one place. In this sense we will take in consideration several aspects of the current working project, which is Keasy. In these design we will borrow elements from the already build marketplace, but we will make better and more intuitive to user. Not only this but the overall design should allow for a more well rounded app which can attract customers to buy more inside this app in a easier fashion.
- In general purposes we will make use of of the authentication process from Keasy and as well implement more of our design for this app. On the side of this we will create a marketplace that allows users to buy and sell different good and services, but the interesting side of this is the availability for users to engage more inside the app. For example we will make use of subscriptions models so people get alerted when a product from their favorite store in back in stock, or they can get the latest deals and trends inside the app.
- To help users we will make use of a comparison table where users can find-out how cheap of a price they're getting for their products compared to commonly used site such as coupang or others. This involves the users into setting a mindset of best bidder. We will also promote ads and use graph based search engine to help users find the best products based on their searches and others. Finally users will be able to checkout with any card they wish to do so, does not matter if it is foreign or international cards.
- ## Core Features
	- **Subscription Model**: Inside this idea we will have a many-to-many aspect, multiple users can subscribe to different stores and multiple user can subscribe to a single user. Inside this feature we should expect:
		- Email Notifications
		  logseq.order-list-type:: number
		- Phone notifications
		  logseq.order-list-type:: number
		- Sale tracking
		  logseq.order-list-type:: number
		- Recommendation model
		  logseq.order-list-type:: number
	- **Recommendations**: This feature will allow users to get recommended items based on a graph structure, key points to this feature are:
		- Users proximity, how close is this product to the buyer
		  logseq.order-list-type:: number
		- User's interests, based on a on-boarding process
		  logseq.order-list-type:: number
		- User's recent searches
		  logseq.order-list-type:: number
	- **Seller's Ads**: In this feature sellers who pays for ads will have a stronger weight at the moment to recommend new items to the end-user, this feature will not violate the recommendations feature but will not create a multiplier for payed ads.
	- **Payments System**: On this part we will make use a PayPal's payments system to allow users to buy things inside the marketplace without the need of a foreign with ease.
	- **Express Checkouts**: Users can easily save their preferred payment system for express checkouts. This should allow:
		- Save credit cards
		  logseq.order-list-type:: number
		- Save local bank accounts
		  logseq.order-list-type:: number
- ## Key-Points (Possible Add-ons)
- This app should help users to easily navigate and make them purchase any good or service they wish.
- Subscriptions models for exclusive deals.
- Verification system system, not just Korean Id but also a way to verify the person is real via Persona or similar