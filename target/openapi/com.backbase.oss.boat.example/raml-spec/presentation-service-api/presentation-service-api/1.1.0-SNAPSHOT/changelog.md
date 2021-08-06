# Changelog
## 1.0.0-SNAPSHOT - 1.1.0-SNAPSHOT
**Note:** API has incompatible changes!!
#### What's New
---

##### `GET` /service-api/v1/wallet/admin/{userId}/paymentcards

> Returns available payment card details for user, optionally filtered by nameOnCard.

##### `POST` /service-api/v1/wallet/admin/{userId}/paymentcards

> Adds a payment card to the user's wallet.

##### `GET` /service-api/v1/wallet/admin/{userId}/paymentcards/{cardId}

> Returns details of a specific payment card.

##### `DELETE` /service-api/v1/wallet/admin/{userId}/paymentcards/{cardId}

> Deletes a payment card with a given id.

##### `GET` /service-api/v1/testQuery/required-boolean-query-param


#### What's Deleted
---

##### `GET` /client-api/v1/customer-kyc-info

> Returns available items, optionally filtered by name.

##### `PUT` /client-api/v1/customer-kyc-info

> UpdateCustomerKycInfo.

