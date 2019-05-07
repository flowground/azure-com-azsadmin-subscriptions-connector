# ![LOGO](logo.png) SubscriptionClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionClient API (version 2015-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-Subscriptions/2015-11-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:36+03:00

## API Description

The User Subscription Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get the list of subscriptions.

*Tags:* `Subscriptions`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Delete the specified subscription.

*Tags:* `Subscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Id of the subscription.
* `api-version` - _required_ - Client Api Version.

### Gets details about particular subscription.

*Tags:* `Subscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Id of the subscription.
* `api-version` - _required_ - Client Api Version.

### Create or updates a subscription.

*Tags:* `Subscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Id of the subscription.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-subscriptions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
