# Root - an on-chain decision-making, talent sourcing and collective creation system


- **Team Name:** stated.tech
- **Payment Address:** mpbXzMgPFbKmXkb6Z6rHK7n6s1gfLJAj9f6rkLdpRjXPX5N
- **[Level]2**

## Project Overview :page_facing_up:

Root is a common good initiative which aims to tackle current issues with on-chain governance - low voter participation, lack of oversight and siloed knowledge, through a fun, collaborative and educational process that plants composable proposals (preferendums) that are nurtured by network contributors to grow decentralised teams from the ground up. 

We want to realise the potential of on-chain governance by enabling proposals and teams to be created, iterated and formed through any text environment (Discord, Telegram, Element, GoogleDocs, etc) that is then interacts directly on-chain, showing the power of graph queries to CRUD data from any API directly from/to the blockchain.

The first version of our system utilises a cutting edge 18th century voting system known as [Borda Count](https://en.wikipedia.org/wiki/Borda_count). 

### Overview

Root is born from experience gained in ongoing applied contribution to on-chain governed networks such as Edgeware and aims to address many of the current limitations of existing approaches facing Substrate based chains, when it comes to existing issues around voting engagement, ecosystem talent development and the formation of effective, efficient and reputable on-chain organisations.  

By returning to first principles we aim to standardize proposal making processes for the Substrate ecosystem, optimising for _intelligent adoption_ rather than simply gamifying governance in a way that may create unintended and undesirable outcomes over the long term. 

Root is built around a collective creation and decision making system that uses a composable voting system inspired by Borda Count to compute voting and allow contributors to create _preferendums_ drectly linked to governance pallets.

> The Borda count is a ranked voting system: the voter ranks the list of candidates in order of preference. So, for example, the voter gives a 1 to their most preferred candidate, a 2 to their second most preferred, and so on. [Borda Count - Wikipedia](https://en.wikipedia.org/wiki/Borda_count).

Our first goal is to facilitate low level consensuses for proposals from initiating teams, before they can smoothly send their proposal to gov1/2 from/to any Substrate network via XCM and instantiate a [shokunin style](https://polkaverse.com/@shokunin/let-s-use-pallet-proxy-for-chaos-and-good-32567) optimistic pure proxy organisation in the process.

Teams can now benefit from an environment where they can collaborate and reach consensus to get supported from the ground up before they send their proposals to a binary Y/N referendum.

We built this [ggdoc hack](https://docs.google.com/document/d/1-g2A387hsOcWc7_UJWwwtgr2gyE553gvFURTVXOEErE/edit?usp=sharing) to demonstrate what we would like to achieve.

If this experiment is a success, we would continue providing innovations for enhancing governance processes for Substrate.

### Project Details

### Current issues with on-chain proposal development

When addressing current issues we need to begin by focusing on the fundamental outcome we have in mind when designing new tools and processes.

We should be very clear as to what certain developments aim to optimise, for who and what purpose, since these problems are all part of a bigger picture.
Without aligning on a core motivation we are in danger of collectively making the overall system worse in aggregate.

A starting point for this is sourcing, sustaining and scaling _collective network intelligence_.

This is a very different design philosophy to simply _driving adoption / participation_.

Let’s break this down a little more by arguing for some of the current ideas that might seem on the surface to solve certain issues:

- **Problem 1 : voting systems are too complex**

  - **Outcome: there is low voter participation**

  - **Solution: we need simpler mobile app UX/UI w/ swipe / notifications**

>Making governance voting easier is definitely something we should aim for and simple more proactive UX/UI is important, but it can also optimise for increasingly poor decision-making - aka, there should be some time cost to making a _thoughtful_ decision and that should be implicit in the design principles.
>
>Other projects such as [Proof of Chaos](https://www.proofofchaos.app/) also aim to create incentive systems for encouraging voters - an idea that’s both brilliant in its simplicity, but also potentially dangerous in its current design… e.g. you earn an NFT for voting, but that NFT is not necessarily non-transferable, and so might be tradeable, which leans into the emergence of financial incentives which abstract away the actual ‘vote’ as the purpose of the interaction, ultimately making the system dumber over time.
>
>So yes we want to get people to swipe easily, but we also need to make proposals more engaging, so people will stop and read / listen / watch and make decisions in a proactive way - delegating their intelligence, as well as their vote. When seen this way, we can also understand voter participation as an entertainment problem, (something that will be addressed in other upcoming initiatives beyond the scope of this grant). 

- **Problem 2: no standardisation of proposal data**

  - **Outcome: standardised proposals**

  - **Solution: proposal forms**

>The standardising of data inputs - is something the Edgeware community have debated endlessly, since there is no lack of proposals, but a lack of data standardisation causes issues nonetheless, with everyone essentially starting from a blank sheet of paper and creating their own documents and structures leading to arguments and circular debates.
>
>The issues of no standardisation:
>
>- For proposers: a blank sheet of paper is harder to fill out than a few boxes which trends towards proposer apathy / missing info / administrative time suck.
>- For voters: it makes comparison hard when comparing two proposals on a like for like basis this effects voter engagement, participation and confuses overall sentiment.
>
>A simple form is the obvious answer to address short term issues, but when we approach this challenge from a longer term perspective of optimising for a bigger picture - sourcing, sustaining and scaling collective network intelligence we can see that some standardisation is useful, but given the diversity of talent we have the potential to fund, across many domains, who each may prefer a different medium of expression, we can then see that standardisation also constrains the intelligence of the collective - voters and proposers.

**Referendums offer binary votes on some package of information, but as we know they are very dumb tools.**

In addition, the current proposal process ends with voters approving funds into a ‘project multsig’, we essentially leave the funded team successful in one part of the process (getting funding approval) but left entirely on their own to figure out delivery of what is in essence something that almost always needs to mesh with a complex and ever changing underlying system.

This leads to proposals taking far longer, teams being paid far less, whilst voters get irate at the time taken, which leads to mistrust, which further exacerbates tensions, which further degrades the governance process. Both sides move apart, and lessons are never learned.

If we can drive forward more nuanced and interactive decision making, that leads to more imaginative proposals that enable us to share financial value and credit more fairly across a group, we can then begin to see this whole process as the pre-formation process for talent sourcing and the setup of fluid and optimistic on-chain organisational structures like shokunin’s [optimistic pure proxies](https://polkaverse.com/@shokunin/let-s-use-pallet-proxy-for-chaos-and-good-32567).

### How Root works 

We introduce a **weighted voting system** to help people participate in on-chain governance equally, no matter how many tokens they have. 

[This document](https://docs.google.com/document/d/1-g2A387hsOcWc7_UJWwwtgr2gyE553gvFURTVXOEErE/edit?usp=sharing) is our _proof of concept_ Google docs hack for building a preferendum pallet, which will act as an easy on-ramp for contributors to take part in on-chain governance via proxy accounts. 

- *As a proposer*, I can create a **draft** with as much or as little information as I am able, using whatever titles / headings / structures or even in the future mediums (code/text/gif/image/video etc).

- *As a participant*, I can create **alternatives** to a proposal’s content, structure or subject, add my own view directly on-chain, and tend to a consensus by voting for my preferences for a better decision-making process.

Suddenly we can open up proposals as **economic opportunities** for anyone to review/improve/iterate proposals and indeed the projects themselves.
Engagement can have a reputational, financial and creative upside, that aligns incentives between all parties better than the current system.

It also starts to solve other issues - namely, information asymmetry between voters (who are likely more familiar with the core chain/tech/culture) and outsiders, namely those wandering into the lion’s den - with excitement and energy ready to be pummeled out of them…

We can see how from these initial foundations we are on a path to solving issues such as **talent acquisition**, development and accreditation using the system to bootstrap the sourcing, sustaining and scaling collective network intelligence.

We’re planning to set up our first vote on Discord thanks to our native bot called boot. Boot is basically our storefront to push our logic on any UI (text editor, chat, or any publication platform).

Voting will happen on [Discord](https://discord.gg/RA2FFZuRmz). 

Link to Boot’s code: https://github.com/stated-tech/boot

The preferundum pallet has been begun, we need to continue it with the lock logic. Then, we will create a full bot that will link the command, the proxy, IPFS, the pallet and displays on Telegram/Discord.

>By pushing in exactly the opposite direction to form creation and data standardisation, we inspire more originality and opportunity, designing in a more humane way… appreciating that what works for some, will not work for all.

### Ecosystem Fit

The stated.tech team seeks to provide the ecosystem with Root as a new governance framework available to every parachain & implementable throughout any dApp on those parachains - our first implementation will be on [Kabocha](https://kabocha.network) - a Kusama parachain.  

As DotSama contributors, we've been spending this year watching teams growing and evolving into parachain owners within a federated network.

We thus identified few major issues that need to be solved ASAP in order to fix DotSama's governance. Indeed, the current centralization in decision making processes within blockchain ecosystems results in:

- Lack of communication between voters and proposal makers ensures knowledge and experience is siloed

- Lack of cooperation between curators, facilitators, building teams and voters

- Lack of composability in the proposal-making process
(I can agree to the general proposal but not to a specific part of it)

- Lack of connections to on-chain treasuries

Which leads to a lack of engagement from contributors, and billion dollars economies managed by arbitrage bots.

We want to fix these issues by leveraging engagement through the whole proposal making process to make it more human and ultimately more comprehensible. 

Our assumption is that we don't need an explicit UI to deploy our app as it can be deployed from any text environment that is connected to the blockchain via our bot. This way, we will show the power of graph queries to CRUD data from any API directly from/to the blockchain from/to any live environment.

## Team :busts_in_silhouette:

### Team members

**Lead team**
- PM: David Germanowicz
- Substrate + JS full-stack dev: Matthiew M23.

**Network Services:** 
- Richard Welsh from [Decent Partners](https://decent.partners)

### Contact

- **Contact Name:** stated.tech
- **Contact Email:** stated.tech@proton.me
- **Website:** http://www.stated.tech/

### Legal Structure

- **Registered Address:** TBD
- **Registered Legal Entity:** TBD

### Team's experience

MatthiewM is a JS full-stack developer and rust (substrate) developer. He originally was a physics engineer. He will be participating in the Polkadot Academy in Jannuary 2022 for one month in Buenos Aires.

David has a background in the Social Sharing Economy as an Impact Fintech Founder. He originally was Product Manager for an AI powered financial product.

### Team Code Repos

- https://github.com/stated-tech

You can find in this github the code of our bot linking google doc/discord. An exemple of a google template is : https://docs.google.com/document/d/1-g2A387hsOcWc7_UJWwwtgr2gyE553gvFURTVXOEErE/. 

You can find aswell the beginning of the pallet preferundum. 

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/Matthiewm23

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/matt-m-6a557b254/
- https://www.linkedin.com/in/david-germanowicz-57151a236/
- 

## Development Status :open_book:

We imagined to develop preferundum on-chain with a “console like” front end using graphQL. You will be able to call current preferundum, to list all preferundums, to make your own one, to add possibilities to those in progress and of course to vote. Everything will be able with your identity that you will get from kilt when you join the proxy. 

This “console” will be based on two pallets that we have currently began to work on.

- The first used is the pallet proxy, that will be called every time a proposal is created. Only 32 people (the maximum of a proxy) can participate in the development of the proposal. So, everyone who has participated in this will have the right to vote with the same chance (without taking into account the balances of tokens of each). This will assume a fair vote.

- The second one (pallet preferundum), will be mainly composed of Hashmap to link every preferundum with subjects and every subject with possibilities.

The data you put on the console won’t be stored in the blockchain to avoid a fees surcharge, that’s why we will only store of pallet the cid of the data stored in IPFS.

We have made a off-chain exemple by linking a google with discord through a bot. Do not hesitate to see what we have done by joining our discord : https://discord.gg/YzpUVuJz

With our console, it will be the same. We could display it everywhere, discord, telegram etc.

The code of the preferundum pallet is available in our github ; we are developing it, it is not fully working but the logic is in.

![Root Principles](https://github.com/stated-tech/Grants-Program/blob/master/Root%20principles.png)

![Technical Logic](https://github.com/stated-tech/Grants-Program/blob/master/Technical%20logic.png)

## Development Roadmap :nut_and_bolt:

- Milestone 1. Proof-Of-Concept
- Milestone 2. User Multi-Interface
- Milestone 3. MVP - Governance as a Service

### Overview

- **Total Estimated Duration:** 3 months
- **Full-Time Equivalent (FTE):**  2 FTE
- **Total Costs:** 30 000 USD

### Milestone 1 - Proof-Of-Concept — Boot - 10k

- **Estimated Duration:** 1 month
- **FTE:**  2
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | TBD |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can create a preferundum, join a team, edit and update a proposal, send to vote |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Presentation Website | We will publish a **website** that explains the philosophy, the interest and the roadmap |
| 0f. | Research on architecture, pallet integrations, proxy pallet, preferendums | done |
| 1. | Module: Boot.js | This repo will be treating both our console-like front-end for preferendums and eventually our UI. Create a preferendum, join a team, add question/possibility, and vote. From whatever UI, you can first create your preferundum through a command. First, you will prove your identity by tokengating your wallet. Which will give you the right to come in the channel. Boot will store the information of preferundum on IPFS (question of the preferundum, subjects, possibilities and quorum). Then will put the hash on-chain through the pallet preferundum. By creating it, a proxy pallet will be used to create team. In whatever UI, you can join (if the proxy is not full), you will tokengate your wallet which allows you to join the channel and the proxy. In whatever UI, you can also list all preferundums alive. When you use the command, Boot will get back the hash of all, and get back the text of IPFS and then display it to you. In whatever UI, you can also create a question (subproposal), add a possibility. Boot will store it on IFPS, add it on chain and then display it in every UI. In whatever UI, you can edit what you wrote. The logic is the same, and then it is referesh in every UI. The quorum will decide if we make a vote to choose the good one to send to the preferundum. If there is a vote, a form will be available when you will have to connect to your wallet. When the quorum decide, the vote stop and result is display. |
| 2. | Discord | We will do Discord Moderation and boot maintainance on Discord |
| 3. | Telegram | Preferendum integration and maintainance (depending on demand). |
| 4. | Element | Preferendum integration and maintainance. (depending on demand) |
| 5. | Twitter | Preferendum integration and maintainance. (depending on demand) |
| 6. | Roadmap updates, maintainance and development | Through Twitter, Discord, Telegram, Element, website and Trello |
| 7. | Hosting | Bot real time hosting and version control |


### Milestone 2 - Boot - GUI - 10k

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | TBD |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can create a preferundum, edit one, add possibility, vote, participate in the proxy |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article** that explains the philosophy, the interest and the roadmap |
| 1. | Substrate module: Identity | In the *real* world, creating a preferendum or joining a team has a impact on your identity. We would like to explore more tokengating possibilities with this logic so that is can give permissions to discord/telegram/element channels etc.  |
| 2. | Substrate module: Proxy | We will use the proxy pallet to create team. Whenever there is a join, we will add the address account to the proxy. |
| 3. | Substrate module: Preferundum pallet | The pallet preferundum will host functions described in Boot, will be linked with proxy pallet (to assume that we can use functions only we are on the proxy) |
| 4. | Substrate module: lock function | For the logic of the vote, we will implement lock function so that every time someone vote, its tokens are locked until the end of the vote. |
| 5. | Quorum | Through proxy, creation of a quorum to decide when to vote/when is the end, there will be function where you can modify the number of people to join the team |

### Milestone 3 - MVP: Root - Governance as a Service - 10k

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 10,000 USD

Our team will need an adapted computer (8 cores, 8 to 16Go RAM, 1To SSD) to run nodes efficiently.


| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | TBD |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can create a preferundum, edit one, add possibility, vote, participate in the proxy |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article** that explains the philosophy, the interest and the roadmap |
| 1. | Substrate module: Identity | In the *real* world, creating a preferendum or joining a team has a impact on your identity. We would like to explore more tokengating possibilities with this logic so that is can give permissions to discord/telegram/element channels etc.  |
| 2. | Substrate module: Proxy | We will use the proxy pallet to create team. Whenever there is a join, we will add the address account to the proxy. |
| 3. | Substrate module: Preferundum pallet | The pallet preferundum will host functions described in Boot, will be linked with proxy pallet (to assume that we can use functions only we are on the proxy) |
| 4. | Substrate module: lock function | For the logic of the vote, we will implement lock function so that every time someone vote, its tokens are locked until the end of the vote. |
| 5. | Quorum | Through proxy, creation of a quorum to decide when to vote/when is the end, there will be function where you can modify the number of people to join the team |

## Future Plans

Once we've deployed preferendums with proxies, we're planning to use Root's pallets to enhance treasury mechanisms and eventually develop our logic on several parachains as a standardized governance process. We would most likely use parathreads to deploy our logic seemlessly while remaining a **common good experiment**.

As a Network Public, Root's goal is to become a sovereign network focused on delivering Public Services related to governance and acting as a laboratory for the DotSama ecosystem. We're thus planning to develop several types of preferendums and treasury mechanisms to act as a GaaS network (Governance as a Service).

We're also planning to develop Root as a part of a broader ecosystem of publishing platforms inspired by the RMRK's architecture based on text nfts to enhance user experience and identity, as well as a publishing data ownership mechanisms.

This roadmap is explained further on our [notion](http://www.stated.tech/).

## Referral Program (optional) :moneybag: 

You can find more information about the program [here](../README.md#moneybag-referral-program).
- **Referrer:** Name of the Polkadot Ambassador or GitHub account of the Web3 Foundation grantee
- **Payment Address:** BTC, Ethereum (USDT/USDC/DAI) or Polkadot/Kusama (aUSD) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))

## Additional Information :heavy_plus_sign:

The project has been discussed in the Polkadot Forum [posts](https://forum.polkadot.network/t/a-better-treasury-system/291/18) and within the [Edgeware](https://gov.edgewa.re/discussion/7887-proposal-root-the-evolution-of-onchain-governance) community. 

**How did you hear about the Grants Program?** 

Being an active part of the Substrate ecosystem. 




