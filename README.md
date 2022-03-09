# emergencycard-api
This API can be used to create new orders for the emergency card [dienotfallkarte.de](https://dienotfallkarte.de). This is relevant for e.g. external resellers with an own shop.

# Before using the API
Ask in [support@memoresa.de](mailto:support@memoresa.de) for your account. We need the following information, to setup your account:
* Your EMail
* Name of your Shop
* Your Address

Furthermore, if you would like to have your own logo on the emergency card, we need your logo in PNG or SVG.

With this information, we create your account and send you your access data and, if necessary, the name of your theme.

# Authentication
Resellers can authenticate at the order API using a Baerer Token. This token will be provided by memoresa once you are set up as a reseller.
In order to authenticate yourself and authorize your order requests simply add the Authorization header with the respective token to your request:

``
Authorization: Baerer <<Token>>
``

# Calling the API
The call is a simple POST request to [emergency-shop-controller](swagger.html)
....

# Your Shop
The emergency card is a personalized product. So we need the following data from your customer, before we print the card:
* name
* intolerances
* main emergency contact name
* main emergency contact number

Those fields must consist of a maximum of 24 characters.

Our [shop](https://memoresa.de/product/smarte-notfallkarte-mit-digitalem-notfallkoffer/) can be used as template.
