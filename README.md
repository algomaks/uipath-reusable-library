# UiPath Reusable Library
This is a reusable UiPath library that anyone can use to generate Leads and Opportunities in SalesForce. The library is written
in a generic way and it is fully configurable via arguments.

The library contains two main reusable components **LeadGeneration** and **OpportunityGeneration**.

## LeadGeneration
This highly reusable component can be used to generate Leads in SalesForce. It accepts the following configuration arguments:

- `FirstName` - the first name of the lead 
- `LastName` - the last name of the lead
- `Company` - the company of the lead
- `Email` - the email address of the lead
- `SFConsumerKey` - SalesForce consumer key
- `SFConsumerSecret` - SalesForce consumer secret
- `SFUserName` - your production SalesForce username
- `SFPassword` - your production SalesForce password
- `SFSecurityToken` - SalesForce security token

## OpportunityGeneration
This highly reusable component can be used to generate Opportunities in SalesForce. It accepts the following configuration arguments:

- `Product` - the name of the product the client is interested in 
- `SFConsumerKey` - SalesForce consumer key
- `SFConsumerSecret` - SalesForce consumer secret
- `SFUserName` - your production SalesForce username
- `SFPassword` - your production SalesForce password
- `SFSecurityToken` - SalesForce security token

## Customization
- You can easily connect this library with your SalesForce instance. You just have to provide your SalesForce credentials as arguments (see above the exact names).

- You can also easily connect this library with a different CRM system if you would like to.

## License
MIT
