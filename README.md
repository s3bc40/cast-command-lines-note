# Cast command lines note

## Ethernaut - Token

Overflow and underflow arithmetic issue

```sh
cast send 0xCONTRACT_ADDRESS $FUNCTION_ENCODED --rpc-url $SEPOLIA_URL --account MY_ENCRYPTED_ACCOUNT
```

## Ethernaut - Delegation

Usage of delegatecall

```sh
cast send <CONTRACT_ADDRESS> "pwn()" --rpc-url $SEPOLIA_URL --account <MY_ENCRYPTED_ACCOUNT>
```
