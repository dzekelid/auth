---
swagger: "2.0"
x-collection-name: CoinFabrik
x-complete: 1
info:
  title: Coinbase API
  description: the-coinbase-v2-api
  contact:
    name: CoinFabrik
    url: http://www.coinfabrik.com/
  version: 1.0.0
host: api.coinbase.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{account_id}/transactions:
    post:
      summary: Send or request money
      description: |-
        Type=send
        =========

        Send funds to a bitcoin address or email address. No transaction fees are required for off blockchain transactions, and Coinbase waives fees for on-blockchain transactions greater than 0.0001 BTC, up to a threshold of 25 per day. Read more about free transactions.

        When used with OAuth2 authentication, this endpoint requires two factor authentication unless used with wallet:transactions:send:bypass-2fa scope.

        If the user is able to buy bitcoin, they can send funds from their fiat account using instant exchange feature. Buy fees will be included in the created transaction and the recipient will receive the user defined amount.

        To create a multisig transaction, visit Multisig documentation.

        Type=request
        ============

        Requests money from an email address.
      operationId: typesendsend-funds-to-a-bitcoin-address-or-email-address-no-transaction-fees-are-required-for-off-bl
      x-api-path-slug: accountsaccount-idtransactions-post
      parameters:
      - in: path
        name: account_id
        description: The account id
      - in: body
        name: transaction_options
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Send
      - Request
      - Money
---