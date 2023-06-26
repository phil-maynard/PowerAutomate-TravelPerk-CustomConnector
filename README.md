# PowerAutomate-TravelPerk-CustomConnector
A Power Automate custom connector for Power Automate

This is a basic Power Automate connector to provide Oauth conenction to a test Travel Perk integration.

The connector was created from the Travel Perk Postman colelction:

- https://developers.travelperk.com/docs/postman-collection
- https://learn.microsoft.com/en-us/connectors/custom-connectors/define-postman-collection

For more information on Mcirosoft custom conenctions see:
- https://learn.microsoft.com/en-us/connectors/custom-connectors/define-blank

# Basic instructions to use

Set up Custom Integration in Travel Perk sandbox with read access for the following scopes:
-  Expenses: Read
-  Trips: Read
-  Bookings: Read
-  Travellers: Read

In Power Automate Custom Conenctor:
- Import and OpenAPI from URL
- For URL use: https://raw.githubusercontent.com/phil-maynard/PowerAutomate-TravelPerk-CustomConnector/main/Travel-Perk.swagger.json
- Add Client Secret and Client ID to security information
- For Rediret URL use: https://app.sandbox-travelperk.com/accounts/oauth2/token/

