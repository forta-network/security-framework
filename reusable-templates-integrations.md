# Reusable Templates & Integrations

![](reusable-templates-integrations.png)

- **What**: Whenever possible, make use of existing smart contract standards (e.g., [OpenZeppelin Contracts](https://openzeppelin.com/contracts/)) and evaluate the security assumptions of protocol integrations that you might need to make with existing protocols (i.e., such as Uniswap, Chainlink, etc.).
- **Why**: Using existing battle-tested, community audited standards and implementations goes a long way in reducing security risks. Assessing the risks of protocol integrations helps you develop security checks to protect against attacks on external components such as oracle manipulation.
- **How**: Import trusted contract libraries and interfaces. Be sure to document your contract dependencies and their versions in the codebase. Use official interfaces for calling external protocols and be sure to take potential integration risks into account.
