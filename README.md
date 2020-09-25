# hive-engine-transactions
JSON for all the transactions possible on hive-engine sidechain. Transactions are broadcasted on hive blockchain through `custom_json` operations.

- json_id: `ssc-mainnet-hive`
- required_authority: `active`

## transfer
```js
{
  "contractName": "tokens",
  "contractAction": "transfer",
  "contractPayload": {
    "symbol": '',
    "to": '',
    "quantity": '',
    "memo": ''
  }
}
```

## stake
```js
{
  "contractName": "tokens",
  "contractAction": "stake",
  "contractPayload": {
    "to": '',
    "symbol": '',
    "quantity": ''
  }
}
```

## unstake
```js
{
  "contractName": "tokens",
  "contractAction": "unstake",
  "contractPayload": {
    "symbol": '',
    "quantity": ''
  }
}
```

## cancelUnstake
```js
{
  "contractName": "tokens",
  "contractAction": "cancelUnstake",
  "contractPayload": {
    "txID": ''
  }
}
```

## delegate
```js
{
  "contractName": "tokens",
  "contractAction": "delegate",
  "contractPayload": {
    "to": '',
    "symbol": '',
    "quantity": ''
  }
}
```

## undelegate
```js
{
  "contractName": "tokens",
  "contractAction": "undelegate",
  "contractPayload": {
    "from": '',
    "symbol": '',
    "quantity": ''
  }
}
```

## buy
```js
{
  "contractName": "market",
  "contractAction": 'buy',
  "contractPayload": {
    "symbol": '',
    "quantity": '',
    "price": ''
  }
}
```

## sell
```js
{
  "contractName": "market",
  "contractAction": 'sell',
  "contractPayload": {
    "symbol": '',
    "quantity": '',
    "price": ''
  }
}
```

## cancel
```js
{
  "contractName": "market",
  "contractAction": "cancel",
  "contractPayload": {
    "type": '',
    "id": ''
  }
}
```

## enableStaking
```js
{
  "contractName": "tokens",
  "contractAction": "enableStaking",
  "contractPayload": {
    "symbol": '',
    "unstakingCooldown": '',
    "numberTransactions": ''
  }
}
```

## enableDelegation
```js
{
  "contractName": "tokens",
  "contractAction": "enableDelegation",
  "contractPayload": {
    "symbol": '',
    "undelegationCooldown": ''
  }
}
```

## updateMetadata
```js
{
  "contractName": "tokens",
  "contractAction": "updateMetadata",
  "contractPayload": {
    "symbol": '',
    "metadata": ''
  }
}
```

## updatePrecision
```js
{
  "contractName": "tokens",
  "contractAction": "updatePrecision",
  "contractPayload": {
    "symbol": '',
    "precision": ''
  }
}
```

## create
```js
{
  "contractName": "tokens",
  "contractAction": "create",
  "contractPayload": {
    "symbol": '',
    "name": '',
    "precision": '',
    "maxSupply": ''
  }
}
```

## issue
```js
{
  "contractName": "tokens",
  "contractAction": "issue",
  "contractPayload": {
    "symbol": '',
    "to": '',
    "quantity": ''
  }
}
```
