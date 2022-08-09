# useful-solidity-patterns
---
This repo is an ongoing collection of useful and (sometimes) clever solidity patterns, many of which are used in the wild, ranging from basic to advanced, demonstrated with concise examples. I (@merklejerk) will be adding new patterns daily-weekly but contributions are absolutely welcome!

The code examples herein are meant to be educational. Most have not been audited and are not intended to be deployed as-is without an independent security review.

## Current Examples
- [Factory Proofs](./examples/factory-proofs)
    - On-chain proofs that a contract was deployed by a trusted deployer.
- Stay tuned for more 😉

## Installing, Building, Testing

Make sure you have [foundry](https://book.getfoundry.sh/getting-started/installation) installed and up-to-date first.

```bash
# Clone the repo
$> git clone git@github.com:Dragonfly-Capital/useful-solidity-patterns.git
# Install foundry dependencies
$> forge install
# Run tests
$> forge test -vvv
```
