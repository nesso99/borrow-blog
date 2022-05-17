# solana account

- Storing State between Transactions
- In Solana, they use accounts as a persistent layer, you can use them as database tables. Addresses in solana can be executable, store data, or only hold SOL.
- Solana does not have mapping like Solidity, you must use PDA to replace this function.
- To call a method, you need accounts, method signature and parameters.
- rent-exempt is a concept that an account has forever lifetime if it has a threshold of SOL, or you can say lamports

### Rent exemption

An account is considered rent-exempt if it holds at least 2 years worth of rent.
If the rent fee rate increase, rent-exempt account is still rent-exempt

## References

- https://docs.solana.com/developing/programming-model/accounts
