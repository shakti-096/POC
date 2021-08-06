# Changelog
## 1.0.0-SNAPSHOT - 1.0.0-SNAPSHOT
**Note:** API has incompatible changes!!
#### What's New
---

##### `GET` /integration-api/v1/items

> Retrieve list of all items.

#### What's Deleted
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


