# ride-faucet
Faucet smart contract for Acryl testnet made using RIDE

### Acryl testnet
https://nodestestnet.acrylplatform.com/

### Get tokens
Send Invoke script transaction

```json
{
  "type": 16,
  "version": 1,
  "senderPublicKey": "YOUR_PUBLIC_KEY",
  "dApp": "3JD4thvVVmzRRynaYHbdnUpv9QF7b1bFf4Y",
  "call": {
    "args": [
      {
        "type": "string",
        "value": "YOUR_WALLET"
      }
    ],
    "function": "faucet"
  },
  "payment": [],
  "fee": 1000000,
  "feeAssetId": null,
  "timestamp": 1584162212399,
  "chainId": 75,
  "proofs": [
    "5wBhMuzU3rC1Zz5KtGWC92RByhANaktMKWobkjYkHQZ76XtiYragh5oCqFriwgKe5LXT5GvuwvHrXJRVZhrGNZtg"
  ],
  "id": "H2QzUtJugH3AynQ1AofUR7JVouMMThDeLBF3TGMYNfzW"
}
```
