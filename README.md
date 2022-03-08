# emergencycard-api
This API can be used to create new orders for the emergency card [dienotfallkarte.de](https://dienotfallkarte.de). This is relevant for e.g. external resellers with an own shop.

# Before using the API
Ask in support@memoresa.de for your account. We need the following information, to setup your account:
* Your EMail
* Name of your Shop
* Your Address

Furthermore, if you would like to have your own logo on the emergency card, we need your logo in PNG or SVG.

With this information, we create your account and send you your access data and, if necessary, the name of your theme.

# Authentication
??? BASIC AUTH with name/passwd? 

# Calling the API
The call is a simple POST request to [emergency-shop-controller](swagger.html)
....

# Your Shop
The emergency card is a personalized product. So we need the following data from your customer, before we print the card:
* name
* intolerance
* main emergency contact name
* main emergency contact number

The fields must be shorter then 25 characters.

Our shop can be used as template: https://memoresa.de/product/smarte-notfallkarte-mit-digitalem-notfallkoffer/
