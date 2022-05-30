# Administration & Access Control

![](administration-access-control.png)

- **What**: Implement access controls that restrict the ability to call special functions that do administrative tasks—such as upgrading contracts and setting special parameters—to privileged accounts and smart contracts.
- **Why**: It is important to maintain protocols through upgrade and governance processes. This allows developers to improve the protocol by adding new features, patching security issues, and addressing changing conditions. However, if the ability to make upgrades is not appropriately controlled, this can constitute a critical security vulnerability.
- **How**: Set up a multisig or DAO contract that will administer changes on behalf of the community in a transparent manner. OpenZeppelin Contracts include modules for [Access Control](https://docs.openzeppelin.com/contracts/4.x/access-control), [Timelocks](https://docs.openzeppelin.com/contracts/4.x/governance#timelock), and [Governance](https://docs.openzeppelin.com/contracts/4.x/governance), which can be administered easily with tools in [OpenZeppelin Defender](https://openzeppelin.com/defender/). Ensure that privileged keys are stored and accessed securely in self-custodial wallets or secure custodial services.
