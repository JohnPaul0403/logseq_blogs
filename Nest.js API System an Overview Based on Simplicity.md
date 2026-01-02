# Using Nest.js as a API System to Orchestrate my App Business
- In this app we will handle the complexity of the whole based on a Nust.js server, this server's main goal is to the be the bridge between the E-commerce and the user, it will handle payments gateways using tokens and it will give access to the store manager to directly interact with the user without the need of any data.
- This process can facilitate self-made apps and much more.
- **Models**:
	- This app will make use of data models to help the users organize there payments. In this sense we will have:
		- autofill-in method which returns to the user it's payments methods to the user only (Demo).
		  logseq.order-list-type:: number
		- Create dummy credit cards with ease. No need of a physical card for free-trials (Demo).
		  logseq.order-list-type:: number
		- Send e-mails to the user as a notification (Not in demo).
		  logseq.order-list-type:: number
		- One click payment system (demo).
		  logseq.order-list-type:: number
	- The app will only need 3 models for now and later one we can add more:
		- **User Profile Model**: This model covers the user email, address (just a simplified version) and country.
		  logseq.order-list-type:: number
		- **Payments Model**: Whether is an credit card or a dummy card they both will follow the process of making payment as easy as possible, the fields are the card number, expiracy and cvv. This should be encrypted and not visible to anyone except the end-user.
		  logseq.order-list-type:: number
		- **Payment Tracking**: For now this system will allow the store manager to send subscriptions status to the user without the need of having their personal data.
		  logseq.order-list-type:: number
- **TO-DO list**: We will make use of slack and plane to track my project in a decent and professional way.