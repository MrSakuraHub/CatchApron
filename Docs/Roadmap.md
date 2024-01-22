# License

This file is licensed both with:

- MIT license, by creator of this document Lauri Ojansivu https://github.com/xet7
- AGPL-3.0 license, original at this repo

# Roadmap

TODO:
- Move below content to different files by topic.
- L: Setup webserver to work at local computer, for public demo, available at Internet
- K:
  - LiveZero:
    - Some fees for blockchain, or get money from wallet for development
    - Tried to steal money
    - Is it at all trustworthy library?
    - Testnet, for testing applications
      - No test environment?
    - How to run local blockchain and connect to other networks?
    - Only 200 Smart Contracts
  - Smart Contracts
    - Rust programming language
      - HyperLedger
      - Polkadot
    - Partiza?, better instructions, how to use their tech
      - Automatical Zero Knowledge proofs
      - Cryptographic chunks in memory, parity bits, rules
      - Don't have any datatypes for floating point. Only Integer numbers. So it's tricky to understand.
    - Triggers to cause some automatic action
    - Some storage space to save state
    - Interface like API
    - Where should contracts be stored? Blockchain spefic docs, how it works. Stored code triggers.
    - Blockchain contracts like triggers, like SQLite database triggers, stored procs/procedures. Or time based cron.
    - Blockchain is storage space, saved data.
    - Keys to access Smart Contracts.
    - Registering of Smart Contracts? Is there some fees?
  - Ontochain => TrustChain call, applications open to Feb 7
    - Good to have prototype, website, to show when applying.
----
1) Guardian Architecture:
- wallets based on work smart contracts
- self costed access recovery
- account recovery, password reset etc, can invoke smart contract when necessary
  - like reset password
  - guardians have access to make this

2) Livezero Blockchain:
- prototype for Cordana: Lauri.
  - Android app, run feature in wallet
  - Use with mobile phone
  - To store
  - Operations:
    - Create token
    - Purchasing in test mode
    - At end of January prototype ready
- prototype for Livezero: Ukrainian man

3) The nature of token
- token is just a number or passphrase in text form, long string
- token identifies something
- identifies some resource at network
- token is something bigger, even in nature
- login token
- learn what is nft, nono fungible token
- cryptocurrency token
  - lean about what is token, what is the meaning at each cases
  - what are standards for tokens?
  - are there common standards?

4) Features:
- Consensus, high scalability
- Blockchain Consensus?
  - List/Chain structure
  - Blockchain is distributed network
  - All nodes run the same code
  - Nodes can run anywhere
  - Nodes are running on cloud
  - Blockchain can not run at ordinary computer?
    - Needs stable internet connection, a lot of bandwidth
    - Consensus process of identifying, what to write to blockchain
    - To add the data, need to select something
    - Consensus algorithms
    - Procesures to select one none
    - Proof of work, stake, etc
    - The selected node writes to blockchain
    - Probability, if someone likes to put fake data?
      - If someone identifies the difference
      - Then come verifiers
      - All nodes have queue, where data is collected how blockchain works
      - Every second new block is written, from cache of data
      - Every node can take cache content, make checksum, verify,
        response what should be written.
      - Wrongs will be discarded.
      - If no error, block is written.
      - All nodes keep all state of all blockchain cache
- Application layer of consesus
  - Making decisions between people
  - Collective opinion, do we agree
  - Feature of wallet should be consesus of people
  - Any owners of wallets can join to define options, to create this pool.
  - These could be contact interface points for smart contracts.
  - Plugin architecture:
    - All options
    - What smart contracts can be attached, what details
    - Reaction at general layer
  - Bitcoin consensus
- System level concensus techical level, different

5) Security integrity monitoring
- checksums, is data the same, or has it changed
- need to check is data still the same
- https://github.com/purpleidea/mgmt
- some messaging virus sql service
- Some cloud services have
- Can make our own integrity checking
- Add data in Docker container
- Dócker container login container, login:
  - Start of container
  - Stop of container
  - Etc => directly to blockchain
  - If something is replaced, also mention it to blockchain
  - Monitoring of infratructure to cloud
  - Verification of any integrity
  - Trigger actions to fix something?
- GitHub actions
  - Automatic builds
  - Automatic restarts, etc
  - Framework for making a build
  - And upload builds to servers automatically
  - immutable infrastructure? cows, not snowflakes?
  - system is not left unattended
  - automatic monitoring
- Access recovery
  - True self custody process
  - Consensus, should it be used
    - 
  - Database triggers: If something happens, it causes something else to happen
  - How to store access keys?
  - Or how passwords should be stored?
  - If system is shutdown, how to recover info?
  - Multilayer security, keys store safe
  - There is realtime backups. 
    If server goes down, it is automatically setup back online
    from backups.
----
riscardam
----

cordona network better, business accelerator, better than ontochain, recruitment for accelerator
=> Lauri contact ontochain hackathon people?
cortana foundation, https://cardano.org still optimistic about their projects
smart contracts. better than bitcoin. develop cordano native.
Architecture to be network independent, serverless, support any different currencies,
any network can be utilized style development,
conceptual framework, very good arcitecture, abstraction of operations.

Kenya: universal applications, super apps, tickets, airways, ordering, delivery, taxi, etc with one app.
Future is such apps, look like wallets, put some applications there.
Different kind of apps for any purpose, work also other than blockchain.
Any tools add there.

Future of creating any kind of apps.

Still should not be the main task. Can be possible, to integrate anything,
put into wallet, functionality.
At wallet, anything can be added: smart contract, nft, money, etc. class of entity.
From there derive some application, etc.
Make better more flexible architecture.

Ability to clone any app. Make super apps, keep them private, until feature needed.

Protection:
- E2E encryption?
- DataBunker?
- RAM/Disk encryption?
- Maybe EU not current at most advanced encryption?
- Good protection of everything.
- Currently: Key encryption, token encryption, RSA ?
- Longer encryptions
- Checksums of binaries, RAM etc
- Deno: Deny file access, etc. Or WASM.
- Map of all users, and what they are doing.
- Protection of logs that are written into blockchain, verify the data
  - In the form of coins
  - Check is block correct
  - If not correct, is not accepted
  - Competition. Reward: Ensure nobody put any false information.
  - Protection in form of social principles
  - Consensus:
    a) Proof of Work - computational tasks - it is a problem, when it takes too much electricity.
    b) Proof of origin - what is it? Authority? Public acceptance, etc proofs.
    c) Fire blocks, concordium, institutional ficance management tool, MCP mechanisms, delacore, some method for concensus
    => Try to be energy efficient. And different concensus.
    - API.
    - Monitoring of runtime, to avoid replacement of them (purpleidea mgmt check that checksum is not changed).
      => Logging, that nothing has changed, data be read only, and only additions possible.
      Make in technical document, draft about experimental version.
      Future support of different blockchains.
      Some abstractions can be still done. Some basic operations still the same.
      => converter proxy
      Existing tools for development and testing.

Cardano. Look at docs, find all that is required for developing this basic version.
Specify what is at Azure etc, password storage, Look how it works, how fast, how
- what tools they provide

Plugins how to verify
login from some city and country
provide email address
support different blockchains
generation of tokens
use tokens to store some personal information into wallet
select very good cloud provider, Azure etc
- confidential computing
- what others do provide 
- Google Cloud happens automatically actions to delete
- Microsoft SQL server maybe somewhere cheaper than PostgreSQL. But self-hosted, no license costs in PostgreSQL.
- Install software with database encrypted
- Tetcloud https://tetcloud.com/en/ - Cloud
- Depends what cloud providers have newest CPUs, Lauri will find out, confidential computing encrypted
- Testing periods, free credits for development purposes, what are available?
- Use free dev servers that WeKan have.
- commit to github account that he provided previously, Lauri accepted invitation.

Next meeting next monday.

aidas project

digital identity network - ?
-------
Lauri makes secure prototype
-------
Validate XSS only at serverside.
