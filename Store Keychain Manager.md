# The no BS Store Keychain and Subscriptions Manager
- This is an app will be primarily design as a no-bs store keychain and subscriptions manager, what it essentially will do is to manage all your store accounts with only one setup, it is a no bs app which essentially means that nothing will be hided from the user and they can essentially manage everything they need. Also we will offer Budget management and cards and bank accounts easy integrations. This will essentially allow the user to manage everything that is a taking money out of there pockets.
- The second best part is the 1-click payment system which will be offer to stores. This system allows stores to have easy and secure checkouts and at the same it will give no personal details about the person, just a metadata of the transaction avoiding users to get spammed with emails no-body cares about.
- ## System Overview
- In general steps we can divide the project into 2 architectures, the first one is the **client** and the second one is the **Store**. In this division the client will be able to manage all it's subscriptions and others in 1 simple-to-use app. On the other hand we will have a simple to integrate API gateway for stores to add the 1 click auth. Once the purchase is made a dummie user is created for the item collection. This process will involve on deciding based on the store so they can have access to the user's email inbox to send them emails about the delivery and others. We will also create a **your data your privacy** system. No data store by user is owned or sell than anyone else than the user.
- **User profile**:
	- Each user is granted with a profile where they can add there credentials once and buy everywhere.
	- In difference to systems like paypal this app will eventually allow the user to see everything about their profile and subscriptions they are currently using.
	- User can opt-in to stores recommendations system, which basically allows them to search for better stores deals than the store they shop the most or the items they shop the most. This system will make use of algorithms and not any AI involve therefore the user data is always private to them.
	- Payments gateway, this will be a system where users add their payments details once, pay everywhere, in this sense with a one-click payment auth they can buy everything they need. They will also be able to create dummies cards for free-trials to avoid get overcharged.
	- Virtual Account, similar to wise but just to buy things, this virtual account should enable people to have a credit-card or virtual bank account register on any part of the world so they can easily but from everywhere with there data being protected.
- **Store API**:
	- For the store we will make use of the store API with a simple to query user token.
	- By default it will have built-in system that allows the store to manage, deliveries, e-books deliveries, SaaS subscription management.
	- All this gateways will be based on a JWT token. This means that the store won't need to store any info of the user and all the important mailing will be automatically handled by this api.
	- The store owner cannot store any data since all the data can be achieve based on the token. The token will handle systems like email systems.
	- This protects the integrity of the user and avoids businesses stealing data and at the same time it simplifies most of the processes since everything is via a gateway.
	- Store will have a store dashboard where they can access to the printout for deliveries and others without the need of storing this information themselves.
	- In this account they can manage multiple stores and self-host once the free-tier is finished.
- **App Architecture**:
	- The app will be mainly be done in JavaScript using TypeScript and it will follow the path of Nuxt.js as the main driver.
	- First and foremost we will have 3 apps:
		- User app, using full nuxtjs
		  logseq.order-list-type:: number
		- Nestjs server as a microservice, for handling the stores API
		  logseq.order-list-type:: number
		- UI store management app in vue using ruby-on-rails for merchants to set-up stores without the need of knowing how to code.
		  logseq.order-list-type:: number
		- The Ruby on Rails app will give most of the elements we need for a merchant to work properly and with a robust system out of the box
		  logseq.order-list-type:: number
	- **Nuxt App** :
		- This app will handle all the logic for the users, where the user can manage and handle their debit or credit cards easily, just a setup-once use forever architecture.
		  logseq.order-list-type:: number
		- In this sense this app will handle user auth towards supporting apps and dummies credit cards for subscriptions. 
		  logseq.order-list-type:: number
		- It will make use of Drizzle as our ORM and neon as the database. As an API we will make use of stripe as our main payment system to handle secure payment gateways.
		  logseq.order-list-type:: number
		- The frontend will make use of TailwindCSS and Shadcn for components.
		  logseq.order-list-type:: number
	- **Nest.js API** [[Nest.js API System an Overview Based on Simplicity]] :
		- This will cover the main business logic and work and the intermediary between the users and the merchants.
		  logseq.order-list-type:: number
		- The API system should be able to make transactions and self fill-out the payments from a user.
		  logseq.order-list-type:: number
		- The system should use an Token based approach to handle users and avoid merchants making contact with the user's info.
		  logseq.order-list-type:: number
		- Finally it should orchestrate and help merchants handle shipping and logistics in a easy manner
		  logseq.order-list-type:: number
	- **Merchants Dashboard**:
		- This dashboard should handle all user subscriptions/shipping and others that the merchant might sell.
		  logseq.order-list-type:: number
		- With ruby on rails we can easily track all sells of the user, notify new subscriptions and others.
		  logseq.order-list-type:: number
		- We will make use of a nice UI uisng vue.js.
		  logseq.order-list-type:: number
	- **Hosting**:
		- To avoid wasting money while developing we will self-host all the app in a docker container which simulates real services.
		  logseq.order-list-type:: number
		- We will then host our app in storm-kit and a free-tier oracle server once this system come out live for people to use.
		  logseq.order-list-type:: number
		- To store and track all of my data I will be using Git with github for the repo and also github actions for the landing page and to test before deploying the app.
		  logseq.order-list-type:: number
- **Timeline**:
	- We won't have a strict timeline for this project since is more as a hobby. The only purpose of this app is to get high relevance and something to show in my portfolio. Being this said we will divide the app in 3 aspects to properly start and finish the project:
		- *Core feature* (Beta-model):
		  logseq.order-list-type:: number
			- In this part we will focus from going from an idea to a product, in this sense we will create a product which can be used and tested by myself. 
			  logseq.order-list-type:: number
			- The main goal here is to test the overall architecture more than the final derivable itself.
			  logseq.order-list-type:: number
			- It should take no-more than 2 months to complete but also it can take more depending on my time management.
			  logseq.order-list-type:: number
		- *Beta-Testing* (Testing and refinement):
		  logseq.order-list-type:: number
			- If the clients using the app find it helpful and if there is validation we will proceed with this part.
			  logseq.order-list-type:: number
			- In this part we will test the app and the main idea, since by this point we will have a well-organize project it should work properly by this point.
			  logseq.order-list-type:: number
		- *Official Launch* (If validation):
		  logseq.order-list-type:: number
			- If all the above goes well we will officially launch the whole based on state laws and other things that an official financial may need.
			  logseq.order-list-type:: number
			- In this part of the story we might make use of payments and pricing models for users to have. 
			  logseq.order-list-type:: number
			- We will allow the use of AI via MCP and the use of local LLMs if the user wishes for. We wil not sell any AI product or something of that style.
			  logseq.order-list-type:: number
			- The main principle is to make sure the user goes first and privacy overl-all, the user is the owner of his own data and he is on the own right to take or delete fully from the services provided.
			  logseq.order-list-type:: number
- **Takeaways**:
	- We must understand that the primary goal is to make a project where I can learn by solving a real world problem instead of just copying something that was already made. This process of learning to create something new is what will eventually make me growth as a Software Engineer and make me a well rounded developer.
	- This is not a typical project app and it is not a super complex nor impossible project to-do. By far this would be the most interesting project I've ever decided to make.
	- The stack to use is extremely efficient and make use of nice tools I like to develop on, like Vue.js, Ruby on Rails and Drizzle which will make the whole process way much easier overall.