### ripplectron
---
https://github.com/devjin0617/ripplectron

```js
C = User Crypto key (one-time input -> send coin, check secret, load wallet)
S = Ripple Wallet Secret

HashValue = SHA256(C)
Encryption = AES256.encode(secret:S, key:HashValue)
DecodeValue = AES256.decode(value:Encryption, key:HashValue)
```

```sh
npm install
npm run dev
npm run build
npm run lint
```

```
```


