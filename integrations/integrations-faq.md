---
description: Frequently Asked Questions by Projects integrating with Kleros
---

# Integrations FAQ

### **If I integrate with Kleros, do I need to ask my users to hold some PNK?**

Your product users do not need to interact with PNK at all. Kleros token is completely absent from your user flows and abstracted from your product interface. PNK is only needed for jurors to be drawn for jury duty and provide the dispute resolution as a service for your application.

_**A useful analogy**:_ If your DeFi project gets its price data from Chainlink oracles, it does not mean that your users need to own LINK. The LINK token powers the service provided by the oracle middleware. Your users never see it. It is the same for PNK.

### **Can I replace Kleros with a community vote or arbitration contract comprised only of my governance token holders?**

It may be tempting to give additional utility to your project's native governance token by having it also handle the dispute resolution through voting, but it presents several weaknesses and risks:



_**Community-wide Vote Fatigue:**_ If a project uses its native governance token to have every token holder vote on every dispute ever raised, it will require a massive duplication of effort and might be plagued by low response rates progressively creating security issues in the form of claim validation vote that could easily be swayed by a single whale.

_**Biased Jury:**_ If a governance token "whale" gets into a dispute on your product and that arbitration goes through a vote with the same governance token, then this whale will be incentivized to vote with no regard to the truth and to unfairly tip the scale in its favor.

### How much does using Kleros cost?

Kleros Courts are currently only deployed on Ethereum mainnet.   
  
_**Gas fees:**_ As for any smart contract, interacting with Kleros means paying gas fees when sending a transaction. The gas price will vary 24/7 depending on the current utilization of the whole Ethereum blockchain and thus, the gas fee will also vary with it.  
  
_**Arbitration fees:**_ IN PROGRESS



### 

At this point, it is not possible to select jurors from a pre-defined pool. Anyone having tokens can self-select to be drawn randomly as a juror. However, we understand that selecting jurors from a pre-vetted pool is important in many use cases. We are also exploring the use of our Proof of Humanity registry to ensure jurors are humans and linked to a single address but having publicly identifiable jurors could link to bribe attacks. If this is a requirement for you, please contact us at [contact@kleros.io](mailto:contact@kleros.io) We would like to know more about your use case.

### Which project is currently using Kleros and how has it worked for them?

We invite you to take a look at our [Live Integrations](https://kleros.gitbook.io/docs/integrations/current-integrations) page for the answer.
