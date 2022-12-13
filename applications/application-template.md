# Root - Governance Lab


- **Team Name:** stated.tech
- **Payment Address:** mpbXzMgPFbKmXkb6Z6rHK7n6s1gfLJAj9f6rkLdpRjXPX5N
- **[Level]**2


## Project Overview :page_facing_up:

This application is in response to several attempts at governance, starting from Polkadot Forum [posts](https://forum.polkadot.network/t/a-better-treasury-system/291/18?u=davedotsama) to a [RFP](https://gov.edgewa.re/discussion/7887-proposal-root-the-evolution-of-onchain-governance) to Edgeware DAO. It has the ambition to standardize proposal making processes for the whole substrate ecosystem and DotSama in general.

### Overview

Root is a Substrate based framework that gamifies governance to plant composable proposals and grow decentralised teams from the ground up.
It is built around a collective creation and decision making system that uses a composable voting system inspired by Borda’s Count to compute voting and allow contributors to create preferendums directly linked to the governance pallets.

Root’s purpose is to make on-chain governance fun, participatory and ultimately smarter. Our first goal is to facilitate low level consensuses within building teams before they can smoothly send their proposal to gov1/2 from/to any Substrate network via XCM. If this experiment is a success, we would continue providing innovations for enhancing governance processes for Substrate.


### Project Details

When addressing the current issues with on-chain governance, we need to begin by focusing on the fundamental outcome we have in mind when designing new tools and processes.

We should be very clear as to what certain developments aim to optimise, for who and what purpose, since these problems are all part of a bigger picture.
Without aligning on a core motivation we are in danger of collectively making the overall system worse in aggregate.
A starting point for this is sourcing, sustaining and scaling collective network intelligence.
This is a very different design philosophy to simply ‘driving adoption / participation’.
Let’s break this down a little more by arguing for some of the current ideas that might seem on the surface to solve certain issues:

- **Problem 1 : voting systems are too complex**

  - **Outcome: there is low voter participation**

  - **Solution: we need simpler mobile app UX/UI w/ swipe / notifications**

Making governance voting easier is definitely something we should aim for and simple more proactive UX/UI is important, but it can also optimise for dumb decisions - aka, there should be some time cost to making a good decision and that should be implicit in the design principles.
Other projects such as Proof of Chaos also aim to create incentive systems for encouraging voters - an idea that’s both brilliant in its simplicity, but also potentially dangerous in its current design… e.g. you earn an NFT for voting, but that NFT is not necessarily non-transferable, and so might be tradeable, which leans into the emergence of financial incentives which abstract away the actual ‘vote’ as the purpose of the interaction, ultimately making the system dumber over time.
So yes we want to get people to swipe easily, (think tinder for governance for good and bad) but we also need to make proposals more engaging, so people will stop and read / listen / watch and make decisions in a proactive way - delegating their intelligence, as well as their vote.
When seen this way, we can also understand voter participation as an entertainment problem, (something that will be addressed in other upcoming initiatives). 

- **Problem 2: no standardisation of proposal data**

  - **Outcome: standardised proposals**

  - **Solution: proposal forms**

The standardising of data inputs - is something we have debated endlessly, since we have no lack of proposals, but a lack of data standardisation causes issues nonetheless, with everyone essentially starting from a blank sheet of paper and creating their own documents and structures leading to arguments and circular debates.
The issues of no standardisation:

- For proposers: a blank sheet of paper is harder to fill out than a few boxes which trends towards proposer apathy / missing info / administrative time suck.
- For voters: it makes comparison hard when comparing two proposals on a like for like basis this effects voter engagement, participation and confuses overall sentiment.

A simple form is the obvious answer to address short term issues, but when we approach this challenge from a longer term perspective of optimising for a bigger picture - sourcing, sustaining and scaling collective network intelligence we can see that some standardisation is useful, but given the diversity of talent we have the potential to fund, across many domains, who each may prefer a different medium of expression, we can then see that standardisation also constrains the intelligence of the collective - voters and proposers.

Referendums offer binary votes on some package of information, but as we know they are very dumb tools.

Root is a collective creation and decision making system that uses a composable voting system inspired by Borda’s Count 1 to compute voting and allow contributors to create preferendums directly linked to the governance pallets.

As a proposer, I can create a draft with as much or as little information as I am able, using whatever titles / headings / structures or even in the future mediums (code/text/gif/image/video etc).

As a participant, I can create alternatives to a proposal’s content, structure or subject, add my own view directly on-chain, and tend to a consensus by voting for my preferences for a better decision-making process.

On first impression, this might sound like it will have an even greater administrative burden on proposers and voters - but this is before we consider:
Economic participation.

But suddenly we can open up proposals as economic opportunities for anyone to review/improve/iterate proposals and indeed the projects themselves.
Engagement can have a reputational, financial and creative upside, that aligns incentives between all parties better than the current system.
It also starts to solve other issues - namely, information asymmetry between voters (who are likely more familiar with the core chain/tech/culture) and outsiders, namely those wandering into the lion’s den - with excitement and energy ready to be pummeled out of them…
We can see how from here we also begin to solve issues such as talent acquisition, development and accreditation using the system to bootstrap the sourcing, sustaining and scaling collective network intelligence.

**Imaginative proposals**

We inspire more originality and opportunity. By pushing in exactly the opposite direction to form creation and data standardisation, we design in a more humane way… appreciating that what works for some, will not work for all.
Boostrapping on-chain organisations (creative collectives)
If the process just ends with voters approving funds into a ‘project multsig’, we essentially leave the funded team successful in one part of the process (getting funding approval) but left entirely on their own to figure out delivery of what is in essence something that almost always needs to mesh with a complex and ever changing underlying system.
This leads to proposals taking far longer, teams being paid far less, whilst voters get irate at the time taken, which leads to mistrust, which further exacerbates tensions, which further degrades the governance process. Both sides move apart, and lessons are never learned.
If we can drive forward more nuanced and interactive decision making, that leads to more imaginative proposals that enable us to share financial value and credit more fairly across a group, we can then begin to see this whole process as the pre-formation process for talent sourcing and the setup of fluid and optimistic on-chain organisational structures like shokunin’s proxies 3.

[This document](https://docs.google.com/document/d/1-g2A387hsOcWc7_UJWwwtgr2gyE553gvFURTVXOEErE/edit?usp=sharing) is our Proof of Concept for building a preferendum pallet, which will act as an easy on-ramp for contributors to take part in on-chain governance via proxy accounts. In this paper, we introduce a new way of comprehending on-chain governance via a cutting-edge 18th century old voting system.

For the past few months, Stated has been focusing on governance throughout DotSama and researching on developing a new proposal system to improve low-level consensuses for teams who want to participate in on-chain governance programs.

We've already spent several weeks working on this field and came up with this ggdoc hack to show DotSama what we would like to achieve.

We basically introduce a weighted system to help people participate in on-chain governance equally, no matter how many tokens they have.

Teams can now benefit from an environment where they can collaborate and reach consensus to get supported from the ground up before they send their proposal to referendum.

We built this little governance game for collaborative creativity, decision making and recruitment for teams who want to innovate and build novel Substrate applications.

We want to unlock governance onboarding from whatever web2 platform and put it directly on-chain by using any text environment (Discord, Telegram, Element, GoogleDocs, etc) to interact with the blockchain. This way, we will show the power of graph queries to CRUD data from any API directly from/to the blockchain.


### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
- What need(s) does your project meet?
- Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
  - If so, how is your project different?
  - If not, are there similar projects in related ecosystems?

## Team :busts_in_silhouette:

### Team members

- David has a background in the Social Sharing Economy as an Impact Fintech Founder. He originally was Product Manager for an AI powered financial product.
- Matthieu is a JS back-end developer and rust (substrate) developer. He originally was a physics engineer. He will be participating in the Polkadot Academy in Jannuary 2022 for one month in Buenos Aires.

**Supervisor, facilitator:** 
- Richchard Welsh from Decent Partners

### Contact

- **Contact Name:** Full name of the contact person in your team
- **Contact Email:** Contact email (e.g. john@duo.com)
- **Website:** Your website

### Legal Structure

- **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)
- **Registered Legal Entity:** Name of your registered legal entity, if available. (e.g. Duo Ltd.)

### Team's experience

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.

If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.

### Team Code Repos

- https://github.com/<your_organisation>/<project_1>
- https://github.com/<your_organisation>/<project_2>

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/<team_member_1>
- https://github.com/<team_member_2>

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/<person_1>
- https://www.linkedin.com/<person_2>

### Google Scholar Profiles (only for research projects)
- https://scholar.google.com/citations?user=<person_1>
- https://scholar.google.com/citations?user=<person_2>

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

> :exclamation: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 Example — Basic functionality

- **Estimated duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

> :exclamation: **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

...


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.

## Referral Program (optional) :moneybag: 

You can find more information about the program [here](../README.md#moneybag-referral-program).
- **Referrer:** Name of the Polkadot Ambassador or GitHub account of the Web3 Foundation grantee
- **Payment Address:** BTC, Ethereum (USDT/USDC/DAI) or Polkadot/Kusama (aUSD) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))

## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.
