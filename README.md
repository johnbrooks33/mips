# MCDEX Improvement Proposals (MIPs) 

## Introduction

MIP stands for MCDEX Improvement Proposal. We intend to use MIPs as the main mechanism for proposing new features, improving MCDEX Governance and the Mai Protocol, collecting community technical opinions, and making decisions for the Mai Protocol to be able to sustain itself.

It is important to provide a governance mechanism, while MIPs can track the progress of the issues and provide a transparent perspective for the long-term planning of the community.

## Contributing

1. Fork the repository by clicking "Fork" in the top right.
2. Add your MIP to your fork of the repository. The markdown file and image files should be included in /mips/mip-N/ (where N is to be replaced with the MIP number).
3. Submit a Pull Request to [MIPs repository](https://github.com/mcdexio/mips).

## Life cycle

1. Draft stage
   1. Submit a Pull Request to [MIPs repository](https://github.com/mcdexio/mips). Make sure you include the URL to an issue where people can discuss the MIP as a whole. Your first PR should set the state of your MIP to `draft`.
   2. An editor will manually review the first PR and assign it a number and then merge it.
   3. Request for comments. MIPs have a feedback period of 1 month.
2. Submission stage
   1. Open a PR changing the state of your MIP to `submission`.
   2. The team starts a **voting** process. In this phase, the governance token holders vote on whether to include the MIP in the governance poll.
   3. If the vote passed, the team will change the state of the MIP to `accept`.
3. Accept stage (non-Core): if the MIP is not related to executing code on chain, the governance cycle ends here.
4. Accept stage (Core)
   1. The author deploys a deployment contract that includes the functions described in MIP and verifies the code at etherscan.
   2. The team starts the 2nd **voting** process. In this phase, the governance token holders vote on whether to execute the deployment code.
   3. If the vote passed, the team will change the state of the MIP to `execute`.
   4. The author calls the deployment, the contract will temporarily get the admin privilege.
   5. Open a PR changing the state of your MIP to `final`.
    
