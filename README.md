# Toy-Project-Bengal-Cart
## Project Overview

## Phase 1:
### Customers will use an online cart platform to buy different daily house-hold groceries ( as initial development).
### Customers will be able to use credit card payment or check or paypal platform for transaction.
### Customers will be able to buy the product and send it as a gift to a friend.

## Phase 2:

### Customers will be able to donate to a non-profit NGO to help people (e.g., COVID-19 patients in Bangladesh).
### The donated money will add to their cart and after transaction the money will be sent directly to the NGO.

## Phase 3:

### Owner of Bangla-Cart(the platform) will have different welfare-agencies (such as 1-taka-vat, HelpPoor!) to sponsor and will be served as Software as a Platform (SaaP).

### Bangla-Cart will receive revenue for evey transaction of the customers and for every donation customer make using the "Bangla-Cart" SaaP.

### Bangla-Cart will provide a monthly summary as invoice to evey  welfare-agencies' as a transactional charge of using the SaaS.

# Technology Recommended:
## Python, Django as backend; JavaScript as front end; third party service Stripe ( a suite of payment APIs) for the transaction or making of our own.

## Technical Challenges for Phase 1:
### Using Django Platform to register and login evey user.
### Add, remove product to the cart box before transaction.
### Database of available product in the platform (like as car rental system).

## Technical Challenges for Phase 2:
### Integrating payment API in the "buy-box"
### Ensuring transactional atomicity in the platform 
### Separate database for the donated money to different NGO's

## Technical Challenges for Phase 3:
### Scalling the system for large number of Customers as well as  welfare-agencies'
### Keeping efficient database for many-to-many transaction between customers and  welfare-agencies' (i.e., one customer can donate to several welfare-agencies and one  welfare-agencie can receive donation from several customers)
### Creating a separate invoice portal to provide monthly transaction summary for different  welfare-agencies' as well as service charge deduction from the donated money.

### N.B.: Bangla-Cart will not be a  welfare-agency, they will only serve as a platform for the  welfare-agencies.
