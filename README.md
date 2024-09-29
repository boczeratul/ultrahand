# Ultrahand
AI-Powered batch transaction platform

## Problem
DeFi space is fragmented. There are multiple AMM swap pools, staking protocols, lending protocols... etc in the space and users have to learn their way around the DeFi space. For them to accomplish an easy task, they have to go through different platforms and perform multiple transactions. E.g. Buy the three largest coins on Aptos in terms of market cap, with the 1000 USDT the user has, and them stake these tokens into respective staking pools.

## Solution
Aptos, with its resource oriented nature, is good with interaction with multiple  accounts, modules and resources in the same transaction. However, it still requires human effort to compose the transactions that interact with multiple modules.

With the LLM that powers most modern AI platforms, we can also train the intent solver with on-chain data. For example, we identify the transactions that happen in a short period, e.g. 5 minutes. And also the inputs and outputs of these transactions. Usually this means they have dependency or relevance with each other. We then have an intent solver who knows how to compose the "transaction sentence" by interacting with multiple modules in the right order.

Also, users can also manually compose the transactions and publish to the platform. Trading KOLs can easily compose a complex transaction and share the one-click-execution link with their followers. In return they get rewards for training the intent solver model and also get a cut for future similar composite transactions.

## Benefits
1. Users can easily accomplish their complex intents
2. KOLs can easily guide their followers to complete complex transactions.
3. Multiple-module operations happen in a single transaction, they leave less storage footprint onchain. Hence, better execution efficiency.

## Note
Unfortunately I don't have time to code the project this time. For reference this is the Ethereum version our team built https://ethglobal.com/showcase/4337-ultrahand-g4631 
