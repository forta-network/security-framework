# Testing & Documentation

![](testing-documentation.png)

- **What**: Create clear, comprehensive documentation of the code, and set up a fast, thorough, easy-to-run test suite.
- **Why**: Writing out assumptions for a codebase’s expected behavior helps to ensure that risks in threat models are being addressed and that users and external auditors understand the development team’s intentions. Creating a test suite for the code helps to prove—or disprove—development assumptions and facilitates thinking more deeply about threat models. This should include tests of mechanism designs that check the tokenomics of a project in extreme market scenarios, along with unit testing and integration tests.
- **How**: Implement known testing framework and security checkers—such as Hardhat, Truffle, Slither, Foundry, etc.—in the Continuous Integration/Continuous Delivery (CI/CD) pipeline that provide different testing techniques, such as fuzzing, property-checking or even formal verification. Use NatSpec comments extensively. Produce live documentation using tools such as [Solidity DocGen](https://github.com/OpenZeppelin/solidity-docgen) alongside high-level design explanations.
