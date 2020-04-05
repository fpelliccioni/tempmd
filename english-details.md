# Knuth node Flipstarter Campaign

# Contents
1. [Introduction](#1-introduction)
2. [Customer Segments](#2-customer-segments)
3. [Value Proposition and Technical Accomplishments](#3-value-proposition-and-technical-accomplishments)
4. [Development Plan and Proposal](#4-development-plan-and-proposal)
5. [Deliverables and Schedule](#5-deliverables-and-schedule)
6. [Budget](#6-budget)
7. [Backup Plans](#7-backup-plans)
8. [Policies, Processes and Culture](#8-policies-processes-and-culture)
9. [Accountability](#9-accountability)
10. [Funding and Revenue Streams](#10-funding-and-revenue-streams)
11. [Team](#11-team)
12. [Document Revision](#12-document-revision)

---

# 1. Introduction
Our vision is to bring Bitcoin Cash to everyday life. Our proposition to do so is by building a monetary platform which offers one service and one service only —money, in the form of electronic cash.

While analyzing Bitcoin Cash status quo we cannot avoid doing it from a business perspective. This means having a good grasp and understanding of the competition of wants that are represented in the arena. Bitcoin Cash is competing with the most powerful monopoly of all times: fiat money. A system with its many edges honed by centuries of experience, reinforced by thousands of nodes and end points connected to its network, and empowered by at least 70 years of computing power.

How can Bitcoin Cash compete with that?

# 2. Customer Segments
Building a monetary system that challenges the current financial apparatus, that brings economic freedom for everybody, would require quite an effort, and many people involved. Not just a few, but a solid mass of people. That is because, to compete with the current monetary system, we need to replace millions of lines of code, thousand of applications and solutions that are in use today, every day.

We must evolve and take naivety out of the equation. Bitcoin Cash is a newcomer in a market that is fully mature. The share Bitcoin Cash wants needs to be conquered, taken, not by force, not by social posting, not by ripping the community appart. But with hard work, with thought applied to action, with infrastructure that works, that is scalable, and performant. Bitcoin Cash needs more people. We need to attract them.

Knuth is convinced the path of simplicity is best suited for that attraction. Avoiding unnecessary complexity as much as possible the better for Bitcoin Cash. Knuth stands firmly with that perspective recognizing in accessibility the best option for stakeholders of the ecosystem. Delivering a readable and easy to understand platform, for them to orient energy and work over aspects more relevant for their solutions and operations.
In the same way we recognize that Bitcoin Cash must improve its efforts on allowing qualified people to come and enter its environments. For some reason, things become difficult and hard for newcomers.

With Knuth we want to pave the way for newcomers. We want to make their experience easy and exciting. We want to help a new generation of software developers to create amazing solutions, a new generation of business developers to take crossborders trade to unprecedented levels. 

Working with an attitude that encourages complexity for the sake of complexity itself, that dismisses newcomers with haughtiness will make us fail, fail as a project, fail as a monetary system and fail as electronic cash.
 
For that reason Knuth promotes the attraction, training and retention of developers of different levels and areas. Our value proposition is a platform particularly designed for them, built upon a modular architecture, simple to modify, simple to expand and simple to learn. On following this path Knuth does his best on attracting software and business developers, and therefore the companies behind them, with the mere intention of impulsing massive Bitcoin Cash adoption. They are the key on how we think Bitcoin Cash should move forward. They are the stakeholders for bringing the future to the present.

And beware, these developers are not just programmers. Bitcoin Cash needs to include people that may not have technical programming skills, but understand what users need or want, that can analyze user experience, that can understand what companies require to become part of the ecosystem, and those guys need to be an integral part of the process.

In short, Knuth is designed for a segmented market that includes:
Miners and mining pools with the clear objective of having a high performance mining node.
Exchanges with the need of dependable full indexation.
Companies and businesses with the intentions of building applications over a modular and reliable platform.
Developers who want to take their projects to new levels with a market-ready solution.
Newcomers who crave to take their first steps in the blockchain world through a direct and easy to understand route.

# 3. Value Proposition and Technical Accomplishments
As Bitcoin Cash technology evolved it calls for a variety of disciplines such as cryptography, programming, databasing, networking, marketing, economics and more. There is no way to have people with the sufficient level of expertise on all these domains, probably in one or two plus a general understanding of the rest or even less. As opposed to softwares built with a monolithic architecture, modularization as proposed with Knuth helps in the sense of opening doors for a diverse ecosystem, where the code becomes interactive, reusable and reliable, easy to read and easy to debug.

Our value proposition summarizes in:

> Knuth is a full-node implementation focused on extra performance and flexibility, which makes it best for wallets, exchanges, block explorers, and miners. It is characterized by its modular architecture and beautiful code. Knuth is also a development platform that offers a set of libraries in several programming languages as a foundation for building applications.

Our technical achievements up to date are:

### High Performance
As already mentioned, Knuth is in essence a high performance implementation of the Bitcoin protocol. It is a full node but also a development platform. Its core is written in C++. On top of it several libraries and modules are provided, written in several programming languages.

### Cross-Platform
Knuth is a cross-platform solution. It can be used in any computer architecture and operating system. It only requires a 64-bit machine. Its code can be compiled and natively used on Linux, Windows, macOS, FreeBSD, and others with no fuzz.

### Build system
Our build system is designed with several advantages in mind. In general these advantages are related to Knuth’s ability to automatically detect processors’s microarchitecture and optimize the binary generated at build time.

The advantages are, first, Knuth automatizes the administration of external dependencies, offered to save time and effort but also to guarantee that only the correct dependencies are installed. This sums up in correctness and security for users.

Second, Knuth also automatizes the administration of internal modules. When installing Knuth, our build system will download, or in its defect, compile each of the required modules, and then it will proceed to build the executable. This results in an economy of compilation time.

Last, with performance in mind Knuth counts with two installation modes:

- Extra-performance mode: Our build system will download Knuth’s complete code and compile it taking maximum advantage of platform/processor’s characteristics in use.  Compilation times can take longer but the end result is a super optimized binary, ideal for users in need of extra performance.

- Easy-rider mode: Pre-compiled Knuth node binaries for mainstream operating systems (Linux, macOS and Windows). These binaries are ideal for prospective users. This mode focuses on timing and a solution ready to-go. These precompiled  binaries are ready for the following instructions and extensions: `64-bits, movbe, mmx, sse, sse2, sse3, ssse3, sse41, sse42, popcnt, lzcnt, avx, avx2, aes, pclmul, fsgsbase, rdrnd, fma3, abm, bmi, bmi2, f16c, xsave, xsaveopt, cx16`.

### Database modes
Designed to offer a high level of specialization for particular use cases, Knuth node can be initialized under 3 different database modes at installation time.

- Normal: It provides full mempool, full UTXO set, full indexed blocks. This mode is ideal for users wanting to be collaborative with the network, just following the chain and making blocks/transactions relay.

- Pruned: It provides full mempool and full UTXO set but it only includes the last n blocks (n being configurable by the user). This mode is designed to be ideal for mining operations and pool operators in need of performance and reliability.

- Full-indexed: It provides full mempool, full UTXO set, full indexed blocks, full indexed transactions and full indexed addresses. This mode is ideal for exchanges, block explorers and for everyone who needs direct access to blockchain encapsulated information and unleash its full potential efficiently.

- Read-only: It is an orthogonal mode that can be used in combination with any of the aforementioned. This execution mode provides users with reading rights but not writing on the database. This mode is ideal for scaling queries capabilities by offering the possibility of several nodes in read-only mode connected to the same database.

### JSON-RPC
Knuth supports JSON-RPC protocol which is a de facto standard on the market.

### Second layer protocols
Knuth provides internal support for second level protocol including full indexation for related transactions. In particular this support was designed for Keoken protocol developed in 2018. Although Keoken ended up not being commercially available, the same concept can be implemented within Knuth for other similar protocols such as Simple Ledger Protocol (SLP).

### Modularization
Knuth is built following an architecture completely modular. Furthermore, each module is a library that can be used independently or together with the other libraries forming what we call “the node”. This, in addition to the usability advantage, adds a neat and readable code organization that follows the single-responsibility principle, and more importantly any protocol change can be introduced in Knuth much faster and more efficiently than in any other implementation.

![ModularArchitecture](http://kth.cash/images/knuth-architecture.png)

The main modules are:

- **Secp256k1**: Optimized C library for ECDSA signatures and private/public key operations on curve secp256k1.

- **Infrastructure**: Domain-driven-design infrastructure layer. It acts as a supporting library for all the other modules. It is in charge of logging, unicode support, encoding formats, big integers support, cryptographic algorithms, and more.

- **Domain**: Domain-driven-design domain layer. It contains information about the Bitcoin domain. It is the heart of the business software. The state of business objects is held here.

- **Consensus**: It includes source code considered to be Bitcoin Cash script consensus-critical.

- **Database**: A high performance blockchain database based on LMDB. This is ideal for a high performance blockchain server as reads are significantly more frequent than writes and yet writes must proceed without delay. The Blockchain module uses the database as its blockchain store.

- **Blockchain**: It defines an API to access blockchain domain objects.

- **Network**: It is a partial implementation of the Bitcoin P2P network protocol. Excluded are all protocols that require access to the blockchain. Node module extends the P2P networking capability and incorporates Blockchain in order to implement the full node.

- **Node**: Bitcoin Cash full node as a C++ library. It is the front door for accessing Blockchain and Network APIs.

- **Exe**: Bitcoin Cash full node executable.

- **Programming language APIs**: in addition to providing a full node as an executable program, a node is also offered as a library. This is designed so that any user can build applications using the libraries in the supported languages. The created application becomes a node since Knuth's libraries operate in the same memory space as the node. This allows efficient access to domain objects (such as blocks and transactions) without going through the networking layers that make access slower. Libraries are offered in the following languages: C, C++, C#, Eiffel, Go, Javascript, Python and Rust. Even more, given the provided tools users can create their own library in the language of their preference.  

- **RPC**: This module provides support for the JSON-RPC protocol.

- **Rest-API (Insight style)**: For those who prefer a Rest-API, Knuth has its own implementation of Bitpay’s Insight API. It is written using our C# API and has every advantage of running Knuth node underneath. As a note, this implementation signals the potential of Knuth’s programming language APIs to create a variety of applications on top of it.

### Processes and industry standards
Knuth is projected by having the best processes and standards available. It is written in C++, a language characterized by its efficiency, specifically in C++17, the latest official C++ standard available. As a note, our policy is to use the latest available standard with at least 2 years of maturity.

Knuth uses the best C and C++ libraries on the market, like Abseil, Boost, GMP, ICU, among others.

In relation to the toolchain, Knuth uses the most valued ones by C++ community: GCC, Clang, MSVC, CMake, Conan, clang-tidy, clang-format.

Knuth also uses the following continuous integration services guaranteeing the highest conformity degree within multiple operating systems: Travis-CI, Appveyor, Cirrus-CI. And in the continuous integration scripts Knuth uses the following tools: clang-tidy, clang-format, sanitizers, and profile guided optimizations.

### Multi currency
From the early days of Knuth (and his main ancestor, Bitprim) its developers were  distinguished by having an inquisitive and curious mind with a characteristic driver in programmatic and protocol experimentation. This is why Knuth, although focused on Bitcoin Cash, also supports Bitcoin (BTC) and Litecoin (LTC).

Over time this proved to be of relevant importance. On one hand it shows Knuth’s flexibility in the sense of how easy it is to add a new coin to our codebase, and particularly how fast it can be done. On the other, it was discovered that by adapting the code, to support another coin, edge cases were spontaneously created which in turn helped in fixing unreported potential errors related to the Bitcoin Cash (BCH) code.

As a result of this Knuth nowadays supports all three currencies which can be interesting for exchanges and multi-currency wallets when using a single node software instead of several.

# 4. Development Plan and Proposal
Knuth understands that the main objective of Bitcoin Cash is to become electronic money at a global scale. For this reason we are convinced that every feature and functionality to be added to the code, no matter what it may be, has to work in favor of that objective.

Knuth is inline with the idea to avoid any change with the potential to make Bitcoin Cash more complex, furthermore any protocol change must be oriented to:

1. Fixing a confirmed security flaw.
2. Helping everyday Bitcoin Cash user experience.
3. Making tasks for developers easier.

If there is the slightest doubt of otherwise, that functionality must go through longer maturation and analysis in backlog and exposition to the Bitcoin Cash community for proper feedback. In simple terms, digital money is the primary vision.

At Knuth we think that for a Bitcoin Cash implementation to be successful must go through several important steps. At first it needs to run as a full node without mining, proving that the node can perform the Initial Block Download (IBD), catch up to the latest state and follow the right consensus rules and the right chain, which means the node do not accidentally introduce consensus rules changes that may lead to forking away of the main chain.

Second the implementation needs to be able to create new blocks that are validated by the network by mining.

Third and no least important for implementations, is to bring improvements and innovations to the protocol, and being able to convince the community to accept these innovations and upgrade, helping in this way the community to grow.

In this way Knuth’s long term plan includes the following proposal:

1. **Implementation of Block Template Conformance Tests for mining**
One of Knuth's main goals for 2020 is to demonstrate to the community its potential as a mining node. The various tests we carried out so far are consistent with the idea that Knuth is in a state of enough maturity for this purpose. However, we want to take that consistency and security to the extreme, reducing any possible risk to its minimum expression and being able to demonstrate it reliably to the community.  
To put that into practice we believe the best way is to ensure conformity with dominant implementations (Core, BCH Node, ABC, BU). For doing so we want to be able to run the extensive test batteries of the respective implementations on Knuth.  
In order to run these tests we must proceed with relevant adaptation tasks on the test code itself as well as Knuth's. We are fully confident that this effort will result in minimizing the financial risk of unintended chain splits, alerting other implementations of possible incompatibilities and a solid recognition by the community and our users regarding the correctness of our node.  
The tasks related to this project are:

    - Research and analysis of main implementations' —Core, ABC, BU and BCHN— mining tests. Extraction of all possible forms of intercommunication between test battery and nodes. Enumeration of those interfaces. Estimated time: 80 hours.

    - Adapt Knuth to support RPC commands that are not implemented but necessary to run the tests. Estimated time: 160 hours.

    - Adapt Knuth to support other inspection variants —contained in the test battery— on the node (i.e.: inspection of log files)). Estimated time: 160 hours.

    - Incorporate all relevant tests into Knuth's current test suite. Estimated time: 80 hours.

    - Corroborate and adapt test battery tests to be run on Knuth. In case of incompatibility, return to the first step. Estimated time: 80 hours.

    - Create a high performance API to be able to run test batteries replacing JSON-RPC. Note: Running tests takes a relevant amount of time delaying development and maintenance, as well it brings a cost in CI services (Continuous Integration). Developing a more performant API will reduce testing times. Estimated time: 320 hours.

    - Adapt test battery to work with the new testing API. Estimated time: 160 hours.
 
2. **Remove the limitation of 25/50 chained transactions**
We understand that removing this limitation is desired by a good part of the Bitcoin Cash community. So we take it as a priority for our development team. But we also understand that removing this limitation is not simply changing a constant value for another one, but improving the algorithm by which new transactions are added to the Mempool.  
Reference implementations use a quadratic order algorithm. We think we can develop a more efficient approach to the problem.This task is 60% advanced. Estimated remaining time: 400 hours.

3. **High performance SLP full indexer**
Single Ledger Protocol (SLP) has gained momentum in the Bitcoin Cash community as a second layer protocol. We believe having an efficient full indexer within the node would be very useful for the community as a whole and particularly for applications built on top of our platform or that use it as a service. Estimated time: 480 hours.

4. **High performance mining API**
Knuth focuses on performance. One of the areas where performance becomes a differentiating factor is mining. Our analysis indicates that although JSON-API protocol may be of relevant utility for certain processes, it is not so much for mining. This is because it is built on HTTP, a very high-level networking protocol for this type of activity. Furthermore, JSON encoding can be seen as generalistic and inefficient compared to an encoding specifically designed for mining use. Estimated time: 480 hours.

5. **Implement Xthinner**
Block propagation is of great importance to the network in general, but in particular for miners and pool operators. Xthinner has shown a significant enhancement in block propagation, and its implementation in Knuth would be valuable. Estimated time: 320 hours.

6. **Implement fast synchronization**
Having a node ready to be used for mining as quickly as possible is one of our goals.
That is why we want to implement UTXO commitments or any other technology that allows rapid node synchronization for use in mining. Estimated time: 480 hours.

7. **Double-SHA256 algorithm optimization**
The SHA256 (double-SHA256) algorithm is of utmost relevance in a Bitcoin Cash node. We have been exploring how to improve it substantially by taking advantage of vector instructions present in modern processors. This will significantly enhance block validation and merkle-root calculation. Estimated time: 320 hours.

8. **Merkle root algorithm optimization**
As Bitcoin Cash scale and adoption increase, the ecosystem will see more transactions per block. It is worth mentioning that Merkle root algorithms are not entirely efficient in memory consumption when the number of transactions rises. We have been exploring how to improve this behavior, also obtaining an improvement in block validation times and block template creation. Estimated time: 240 hours.
 
9. **Improve libraries and languages’ APIs**
Maintenance and continuous improvement of libraries and APIs. Although this is continuous work, we would like to be able to dedicate at least 160 hours to it in the next 6 months. Estimated time: 160 hours.
 
10. **Improve documentation**
Documentation is a fundamental tool for Knuth's exposure and proper use. Although this is also a continuous job, we would like to be able to dedicate at least 80 hours to it in the next 6 months. Estimated time: 80 hours.

11. **Research projects**:
In addition to the specifically targeted tasks, we have in backlog a series of research projects that will be beneficial not only for Knuth but for the entire ecosystem. They are large-scale projects that involve excellent communication and interaction with the community and other implementations.
		
    - **Bitcoin Cash formal specification and automated testing**
Although having a Bitcoin Cash specification written in human language is important, since it facilitates a mutual understanding between developers involved, whether working in node implementation or other infrastructure services, we believe that Bitcoin Cash would greatly benefit by more rigorous specification.  
For this reason, Knuth proposes to write a formal specification in a logical programming language designed precisely for automated mathematical verification of software correctness.  
The ultimate goal is to demonstrate that a given Bitcoin Cash implementation works as expected just automatically by running a computer program. Long-term plan: minimum 2 years.

    - **Research on DAA and alternatives**
    The current difficulty adjustment algorithm (DAA) has been perceived from various perspectives by the Bitcoin Cash ecosystem since its inception, some positive and others negative. At Knuth, we want to participate in the research process of what are the real effects of this algorithm on mining and pool operations and, if required, propose improvements or even an alternative development. We know this is a project that requires great transparency and community participation.

    - **Research and implement Graphene**
    Our initial analysis of Graphene shows it as an interesting option for block propagation mechanism. Nevertheless, it is a technology that requires more research and testing before being implemented. Our proposal to improve block propagation would go by implementing Xthinner first while doing the required research on Graphene and then, in case of a positive outcome, proceed with its implementation.

Note: all estimated times in this long-term plan are based on technical approximation and calculations using resources available to date. If any change, it will be duly informed in a timely manner with required justifications through Knuth's official channels, in this way, maintaining transparency with the community.

# 5. Deliverables and Schedule
All the tasks mentioned above represent an ambitious plan that, while bringing benefits to the Bitcoin Cash ecosystem, we know, is far-reaching.

Given the current market conditions, it seems relevant to make use of the Flipstarter proposal in the best possible way. In our case, this translates in presenting a campaign with limited scope, but that allows us to showcase the value already invested in Knuth as well as its future potential.

For this reason, we are presenting a campaign to fund 960 man-hours (approximately 6 months) to be distributed along the 2020 cycle. From this perspective, our deliverables clearly cannot exhaustively include the entire list shown above as a general plan. Although we have our preferences, we would like to allow potential contributors to choose, according to their criteria, how their funding should be used.

When making their respective pledges to Knuth project, contributors may add as comments —within Flipstarter platform— the ordinal number of the proposed tasks they would prefer the most. In the happy case of getting funded, Knuth will do everything in its power to accomplish the most voted tasks first. If not details provided, Knuth will assume the presented order.

Given this proposed methodology, it is difficult for us at this time to present a list of deliverables under a fixed schedule. But we believe this is an excellent method that provides the community with an exciting space for participation. Our funders will be able to express their opinions concerning what task they would prefer to see first materialized clearly and transparently.

![Tasks](http://kth.cash/images/knuth-tasks.png)

In parallel, there are other associated tasks and activities that we do not consider relevant to be included exhaustively in this document, nor were they independently accounted for at the time of making a budget that makes sense. These activities are related to the preparation of the Flipstarter campaign, website update, node bug fixing and maintenance, release management, devops, small equipment, and minor expenses.

# 6. Budget
The great challenge of any fundraising campaign to date is the complex socio-economic context in which we find ourselves where the effects of COVID-19 virus are ravaging society. In parallel to that, projects related to Bitcoin Cash ecosystem have their challenges by the status quo that our community is passing.

Although these two factors do not demoralize us - because we are certain we are helping to build a better society - it is important to take them into account. This is especially true when it comes to presenting a financial budget like the one we are doing.

We are clear about the costs of a project of this sort. We are very clear about the international rate of senior software developers, as well as the costs of doing business and driving an organization forward. But we are also very clear about the situation that Bitcoin Cash is going through, and in Knuth, we do not feel comfortable imposing an extra burden. But it is also true we are keen to show the potential of our work and our solution, and mainly collaborate with the community.

For all these reasons, we have decided to present a limited campaign in terms of deliverables and financial resources. The budget that we are requesting for the 960 man-hours of work, is USD 100,000 (BCH 460 at the time of writing) that we know is way below international standards.

This is our way of collaborating in times of crisis, of showing our value, of starting small to grow afterward as strong as possible. Give us the opportunity to prove it.

# 7. Backup Plans
In the event that our campaign does not obtain requested funds, we plan to make other ways available to receive funds from potential contributors. Those mediums will be informed shortly by official channels.

Regarding Knuth's technical development, in case of a not successful campaign, our team will enter in maintenance mode and will do everything in their power to keep the node updated and under consensus rules as it has been doing to date. Any new development/research and the time required to put it into practice will go through the lens of detailed analysis and context.

Either way, Knuth is an open-source venture and welcomes any voluntary collaboration to put the presented plan into practice. We welcome anyone who feels like collaborating.

Apart from all that, Knuth is in the evaluation of new revenue streams that do not depend exclusively on fundraising but on delivering specific services to Bitcoin Cash Ecosystem. More details in the Revenue Streams section.

A non-trivial aspect at the time of considering a fundraising campaign is the volatility of Bitcoin Cash in the short term. In the event of our Flipstarter campaign having a successful end, we would like nothing more than to keep raised funds in BCH as a unit of account, and to be able to consume them directly without exchanges involved, but we know this represents not few challenges and can compromise negatively obtained funds.

A possible solution is to keep 50% of obtained funds in BCH and the remaining 50% in some stable coin such as USDH. Any matter related to this topic will be duly informed in a timely manner and with adequate feedback from the community.

As an important note it is worth mentioning that under any possible scenario during the next update on May 15th 2020, Knuth will follow the most-proof-of-work chain.

# 8. Policies, Processes and Culture 

### Channels

Knuth is an open-source project that strives for adding value to the Bitcoin Cash ecosystem with healthy ambition but also anchored to reality. For this reason, we want to be close to our users and clients.

Soon we will have our website updated and running. We also have our resources on GitHub, which are open to anyone who feels oriented to participate and collaborate. We encourage not only community members to do so but newcomers, believing that our strength is in diversity and in sharing knowledge under a code of mutual respect and cooperation.

Our website and read.cash account are the intended channels for official communications and periodical reports, whether financial or technical. We also count with Telegram, Slack and email available to the public, if necessary, do not hesitate and drop us a line. If you are interested in running Knuth, building something cool with it or just give it a try, leave us a message and we will do our best to help you.

website: [kth.cash](http://kth.cash/)  
github: [github.com/k-nuth/kth](https://github.com/k-nuth/kth)  
email: [info@kth.cash](mailto:info@kth.cash)  
telegram: [t.me/knuth_cash](https://t.me/knuth_cash)  
read.cash:  [read.cash/@kth](https://read.cash/@kth)  
slack: [k-nuth.slack.com](https://k-nuth.slack.com/)

### User Relationships
We would like to have a fluid relationship with our users, with other node implementations and with the community in general, where under the precepts of collaboration and co-creation we can lay the foundations for a lasting professional relationship.

We want to be particularly present for the new developers of the ecosystem. We want to grow with them onboard, learn and find solutions together. Knuth was designed with them in consideration and that path will not be abandoned but motivated. 

### Key Partnerships
Collaboration among node implementations is of fundamental importance for the benefit of the Bitcoin Cash ecosystem. This concept is deeply rooted in Knuth's philosophy. It is also quite clear for us that healthy competition is beneficial, and from every point of view inspiring as it is an interesting reflection of forces that govern a free market.

Based on principles of collaboration and healthy competition, we want to learn from other node implementations and share experiences, whether technological or business strategies. We know this path will result in benefits for the community. To compete, it is necessary to maximize user experience, stay in continual innovation while not sacrificing reliability, understand where we are, and the way forward.

That is our commitment, which is subscribed to the Bitcoin Cash ethos.

Note: Knuth is part of a group of node implementations that practices responsible disclosure of potential security issues.

### Timing, Politics and Interest
The challenge to take Bitcoin Cash to its maximum potential is at reach, but our understanding signals that we —as ecosystem— do not have much time to do it. At Knuth we perceive Bitcoin Cash as a product. As a product, it needs users, and users will come just with improved user experience. Within Knuth, we are deeply concerned with that aspect, and how we can ease the way in that direction.

We need at least a hundred times more users in the next couple of years. If we cannot do that, we will never see bitcoin’s true vision realized. And this is nothing related to technical, but with business. The fiat financial system already knows Bitcoin Cash. It has a clear picture of Bitcoin Cash objective, we have shown them what we want, we have declared it to the four corners of the planet. And yet from the strategic point of view, we are failing.

When a strategy has been declared, there is not much time to execute it. There is no time to think and wait. No, you command and operate, because if not any potential opponent —fiat financial system— will adapt. By the time the target is attained, it becomes evident that the same opponent is already there, waiting, stronger. This is the game we are in. A game we will not win if we continue in this way. A game that, we like it or not, has politics and interests vested in its very core.

Politics because it involves people —economy is social, and its medium is a network. And where there are people there is politics. Interest because it involves money —our product is money. And where there is money, there is interest. Politics and interest are part of the game. It is impossible to remove politics because if we do so, we would need to remove people. Samwise, it is impossible to remove interest because if we do so, we will lose the monetary system we want to build. So we need to wake up, Bitcoin Cash is built around people and money, and involves politics and interests. If Bitcoin Cash ecosystem does not realize that fast enough, it will never reach its goal.

Knuth has a clear direction, attracting more people and money to Bitcoin Cash ecosystem. If we succeed, we expect more politics and more interest. It is undoubtedly challenging but needed to create the system we want on a global scale.

# 9. Accountability
Knuth understands the significance of transparency towards the community and intends to be fully compliant with that standard. Knuth will publish monthly progress reports detailing relevant aspects of the operation.

These reports will be made available through the official channels mentioned above. They will include, among other things, general metrics, progress of tasks, deliverables offered, and financial statements related to the funds provided by the community. Each of these aspects will include its corresponding verification forms, such as commits from Github for technical aspects —software development— and addresses/wallets/transactions for financial aspects.

Bitcoin Cash community will have access to this material, and we encourage any interested party to use it as a base for any related concern or question. We want to grow with accountability and transparency.

# 10. Funding and Revenue Streams

At Knuth, we have the highest respect for voluntarism and self-established initiatives. We know that they are of great importance in the open-source community. And while we accept help from those who are willing to offer it, we are clear that the road ahead is high-demanding in terms of resources, even more so under the aforementioned time conditions. We are in a race against time and our great opponent is neither more nor less than the fiat financial system.

To sustain that race, we need a cash flow that is not negligible at all. At the same time, we do not want to become a burden to the ecosystem we intend to help, that would make us parasites, and it is not the path we have planned for Knuth.

On the other hand, we want to avoid at all costs obscure initiatives that give rise to a bad image for our organization or unleash conspiracy theories regarding how Knuth obtains its funds. Our commitment is to transparency. We intend to maintain an openness policy concerning our business plan and that it be accelerated in line with the corporations in the ecosystem.

Our plans can be grouped under two aspects: funding stream and revenue stream.

### Funding Stream
At first instance, we have public funding as a primary mechanism to obtain funds to carry out our operations. Knuth participates in the Flipstarter campaign of April 2020 which we consider a significant step forward in the evolution of fundraising in Bitcoin Cash.

We would love to have the resources to integrate Flipstarter technology to proceed with our own campaigns, but for the moment, that goal is beyond our budget.

Without detriment to that, Knuth also has a direct form of funding per requirement/feature through its website (kth.cash), where each item includes detailed information and the amount required both to start and finish the task.

Also, we are analyzing the option of launching a software consortium under the commitment of being fundamentally decentralized. This consortium will welcome companies, universities, and research institutes that wish to:
- Advance the state of the art of node implementations.
- Contribute to research in Bitcoin Cash technology integration.
- Support training of students in Bitcoin Cash technology.

Participation in the said consortium would have a membership fee in exchange for benefits such as:
- Early access to research outputs through consortium reports and/or software.
- Collaboration on topics of mutual interest.
- Participate and vote at the consortium committee.

This idea is still under development and analysis. Any relevant update will be informed in a timely manner through official channels.

### Revenue Stream
In the second instance, Knuth, with demanding growth objectives, wants to conquer its space as a commercial organization, in which Bitcoin Cash-related innovation ventures take us to new frontiers while fulfilling the vision of electronic money for the world.

We hope our common sense of purpose will bring people together, wanting to be part of the development of quality Bitcoin Cash products and services. This will bring a revenue stream that will be submitted to increase our offer for the benefit of the ecosystem.

These commercial plans, which will be notified on time, will not interfere in any way with our open-source philosophy. Our flagship product, Knuth, will continue to be open to the world, always.

Our emphasis is on performance, not only on the products and services offered but also on the way we operate.


# 11. Team

While Knuth may seem like a newcomer to the node implementations scene, this is only a superficial impression. Going deeper, the technological lineage of which Knuth is part becomes evident. Knuth is a direct descendant of Bitprim node, which in turn, is a descendant of Libbitcoin, created in 2011, being the second full implementation of the Bitcoin protocol, after the original client, created in 2011. Although there are considerable differences between Knuth and its predecessors, the former attempts to get the most out of its genetic memory —in a manner of speaking— embedded in its code.

The team is formed by people with two main backgrounds, software development, and corporate business, in both cases with vast experience. To date, the team is both lean and functional, with the explicit intention of gaining speed and expedition without compromising robustness.

For more information regarding our team, check out our website at [kth.cash/team](http://kth.cash/team).

# 12. Document revision

Version: 0.7

Revision Date: 05 April 2020

### Authors: 

- Leandro Di Marco, [leandro@kth.cash](mailto:leandro@kth.cash)
- Fernando Pelliccioni, [fernando@kth.cash](mailto:fernando@kth.cash)

