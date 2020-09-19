# UGC Blockchain Platform

## What is UBP
UBP is a platform which is based on JavaScript and Node.js, implementing a blockchain platform for user generated content sharing and management.
## What can UBP do?
- User creates channel, as content container, user can release article or news in container.
- By releasing articles or news in the channel, user share the information to others.
- Users browse the home page content and rank the content by popularity and publication time.
- Users browse specific content, comment on or respond to content of interest.
- Users reward article authors and execute different reward settlement strategies according to different modes.
- The trustee will report the channel, article and comment, and the content will not be displayed after reporting more than three times.
## Character
### trustee
The trustee can report and manage the content in the application, and the mediator exercises the power to purify the content environment of the entire application and prevent the application from spreading bad information through the reporting function.
### publisher
The author of an article gets a reward by publishing his own content
### comment user
Users are a universal character and can comment on posts, reward posts, respond to comments and comment on thumb up. Users can play the role of publisher by creating channels and publishing articles.
## Economic models
Each write operation of smart contract execution in the blockchain system consumes computing resources of the system, which are provided by the trustee. In order to ensure the smooth execution of the contract and the stability of the network, certain incentives should be provided to the trustee.
<br>
The caller of the contract spends part of Token as the service fee for executing the contract, and the agent receives the service fee as the reward for maintaining the stability of the network. Token can also circulate between the two roles through a contract, creating a tiny economic base cycle.
<br>The invocation of a contract lacks permission restrictions, and there are some unknown risks. For example, channel creation contracts are frequently invoked, which is considered unreasonable behavior in the system, because the creation of too many channels increases the management difficulty of the trustee. We limit this by increasing the fee for creating a channel contract, and by imposing a channel management obligation on the trustee for charging a channel creation fee