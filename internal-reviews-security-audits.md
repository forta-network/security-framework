# Internal Reviews & Security Audits

![](internal-reviews-security-audits.png)

- **What**: Dedicate time to finding bugs through both internal and external code reviews.
- **Why**: Stepping away from feature development to focus on security concerns gives developers time to find potentially obscure issues. External audits can be especially helpful in this, as they can bring outside perspectives and expertise that the development team does not have.
- **How**: At an appropriate juncture in project development, schedule a feature freeze to allow time for an internal review, followed by an external audit. This should take place prior to any live deployments and upgrades. OpenZeppelin developed a [Comprehensive Smart Contract Audit Readiness Guide](https://learn.openzeppelin.com/security-audits/readiness-guide), which provides developers with a checklist of matters to consider when preparing for an audit, including audit timing. Be sure to also review deployment transactions to ensure they use the audited code version and have the appropriate parameters, especially when upgrading.
