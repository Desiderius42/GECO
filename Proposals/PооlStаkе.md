## Project Overview
**TO DO**

### Project name
PꝏlStake Slashing Insurance

### Team members 
[Marouane Hajji](https://www.linkedin.com/in/marouane-h-b876133/)  <br/>
[Emmanuel Lаnɡе](https://www.linkedin.com/in/emmanuellange/)  <br/>
Julien Klepatch  <br/>
Reza Bakhshandeh  <br/>
Muhammad Mafazine  <br/>
Jean-Baptiste Soufron  <br/>

### What project are you building 
PꝏlStake is a self-funded experiment consisting on creating series of Ethereum Smart Contracts and building tools related to pooling and staking. The idea is to provide pieces of software that allow people to leverage their number and regroup (pooling) in different kinds of settings and in a decentralized manner. Staking and staking derivatives became our main focus after numerous discussions with the different PoS blockchain projects in the space and their communities.

One of the tools that we are currently building is an insurance-like product for slashing events.
In order to implement it, we will use prediction markets and build it on top of the Conditional Token Standard (Gnosis Mercury) and connect it to the Cosmos Hub as our first PoS Blockchain to insure. This will enable our users to have access to a new type of product through an insurance like market-place while bringing a solution to a current pain point in the staking process in PoS blockchain.

To help understand what we are building and what staking derivatives are, here are some definitions that are based on the Tendermint (Cosmos) PoS consensus:
Proof of Stake (PoS): consensus mechanism that runs virtually instead of relying on miners to solve hard cryptographic puzzles using their computer power.

Validator: In PoS validators replace miners. Validators offer coin holders of a PoS blockchain the possibility to use their infrastructure to lock some coins as a stake. Validators then participate in the consensus process and get rewarded when blocks are added. The Staking Rewards are distributed to the coin holders and the validators is paid a percentage fee on these rewards. Validators are businesses who secure the network.

Slashing: The punishment that occurs in case of a misbehaviour from one or several validators. Misbehaviours can range from being offline and missing blocks to double signing and trying to conduct an attack on the network. The slashing punishment ranges from 0.1% to 5% of the staked coins (with misbehaving validator) in the case of Cosmos Hub. The punishment can vary from one blockchain to another.

Staking derivatives: coins, tokens or tools based on the staking activity.


### Why did you decide to build it 
Marouane created several communities on social media in the past, tackling real problems of particular populations/minorities (and sometimes giving birth to small movements). When he joined the first crypto and blockchain related communities, he always thought of tools that could help them gain more power, leverage the number and the crowd-knowledge / collective intelligence. So he used PoolStake as a way to try to provide tools and also to learn by building and interacting with dApp users. The first tools were related to ICOs and trading, the ones we are focusing on building now are more related to staking as PoS will come with its own sets of challenges.

While discussing with different members of staking communities (blockchain projects, delegators, validators, block explorers, wallet providers, etc ...), Marouane and Emmanuel identified series of pain points which led them to focus on staking derivatives as possible solutions. The staking derivative with the most potential appeared to be a slashing insurance. After spending 6 weeks meeting with validators and delegators from the Cosmos Network they had a strong confirmation of their initial intuition. So they managed to collect signatures of a Letter of Intent from 13 validators representing 25% of the voting power of the Cosmos Hub. They also got the support of Wallet Providers and Block Explorers. The existence of a product/market fit combined with the possibility to bring some relief to a real pain led them to decide to build it.

__The problems and pain points we tackle:__

>1) Staking is risky, let’s make it risk-free

As explained in the previous section, the slashing risk does exist even though it can be perceived as having a very low probability, it happened and can still happen.

**We want to make the staking activity as risk-free as possible for delegators.**

>2) The staking activity is perceived as a commodity, it is not

Different types of validators exist and so far the only way to differentiate between a validator and another are the fees they apply. Some validators try to be as transparent as possible regarding their setups to show they are serious and committed to providing the most secure experience for their delegators, however the transparency marketing efforts don’t seem to be enough and do not represent any actual guarantee.

The fact that some validators offer a 0% fee is a continuous hot topic within the Cosmos Hub community. The moment when one of the 0% validators became the biggest validator in the network for a short time crystallized a mix of frustrations and worries. Followed a debate over the long term implications with regard to the individual validators’ infrastructure security and the network’s level of decentralization / concentration of voting power and influence in the hands of a few.

The slashing insurance allows to create a second level of differentiation that will be based on the risk score of each validator and the transactions that price it. For example, validators with 0% fees are likely to be perceived as not investing in their infrastructure and committing necessary human resources to make sure their operations run as smoothly and securely as possible. An investor who is interested in buying the risk of this validator would price it higher than the risk of another validator who’s team is specialized in setting “military grade” type of infrastructure and who is making all the necessary investments to get regularly audited, have back-up set-ups etc …

**Our aim is to provide the delegator community with a new indicator (Risk Score) that will allow them to choose more wisely and take into account the risks related to choosing one validator over another.**

In the spirit of differentiation, validators could also use the insurance product as a means to attract more delegations. One way of doing it can be to offer free insurance as part of their validation activity (for new delegations over a limited period of time for example). In this case validators could be buying their own risk or buying the premium from an investor and distributing the insurance token to delegators who meet certain criteria. The same reasoning could be applied to attract ICF/AiB delegations (InterChain Foundation and All in Bits represent around 20% of Atoms in circulation and are therefore the biggest delegators in existence).

**We want validators to use the insurance as an additional service proposal that could help them increase their fees and differentiate in an already crowded market.**

>3) Liquidity of Delegation Vouchers or Bonded Atoms:

Right now the delegation process implies a lock-up period of 21 days after unbonding before a delegator could move his Atoms. Unbonded Atoms can still be slashed during the 21 days lock-up period. Since the launch of Cosmos Hub, a need has been expressed by the community to have an alternative that gives more liquidity to delegators, either by using Delegation Vouchers (whenever someone stakes Atoms with a validator, he would receive a voucher representing staked Atoms + staking rewards to be retrieved from said validator) or bAtoms which is a similar solution. Both options create illiquid assets, each asset being linked to one particular validator and his slashing risk. Combining the resulting asset with an insurance would allow to neutralize the slashing risk and create a slashing-risk-free asset which will be more liquid.

**We want the insurance to help make representations of staked (bonded) Atoms more liquid by neutralizing the slashing risk.**

### How long will it take 
4 months with grants from both ICF (InterChain Foundation) and GECO, 6 months with a grant from GECO alone.


### How much funding are you requesting  
+ Approx. 50K€ 
+ a one million Dai credit line over one year (to kick off the project)
+ PR / Marketing assistance

### How did you hear about the GECO
> Website, Twitter, Conference and others

## Your Proposal 

### Team description

### Project description
_Outline a detailed description of your project, why you chose to build this project, the overall goal and future outlook of your project and why we should fund you._
### Features
_How do you plan to implement your project, which tools and framework will you use? Optional: Architecture, Mockups, etc._
### Team description
**Marouane Hajji: Product / Business Lead**

Marouane first experience with code started when he was 13 years old. Later, his interest in the business world led him to get a degree from ESSEC Business School where he first studied Finance then Entrepreneurship.

He became an entrepreneur after an experience in Strategy Consulting and Finance. His time at CDO Invest in 2007 (a 4 Billions euros fund managed by AXA-IM) and the fall of Lehman Brothers while he was at Citigroup allowed him to have a hands on experience within a system that was completely broken.
As an entrepreneur he took part in the launch of WeTrillions (formerly Looly’s and Lecupboard). The impact-driven food start-up was later backed by 500 startups.

As a former smoker, he created and launched a connected vaping device to help smokers quit and get rid of their nicotine addiction, the venture later became the leading european monthly subscription box for vapers (LіquіdΒοх).

Starting from 2016 he started exploring Ethereum and pretty quickly the technology and the subsequent possibilities became an obsession for him. This led him to create and self fund PꝏlStake, a 4 people team experimenting using smart contracts to provide different sets of tools for the crypto community. After Emmanuel joined him they started focusing on staking derivatives.

**Emmanuel Lаnɡе: Tech Lead**

Emmanuel has 15 years experience as a software developer. During his years in engineering school he had a deep interest in cryptographic technology and what is now called post-quantum communication was the subject of his final year thesis. He started his career as a developer and coded the first MPEG-4 HD encoder in the world (still in use today after more than 9 years). Then he co-founded BrightLoop, the company designed and manufactured software driven  power supplies for large companies and implemented industry leading software development processes. He partially sold his shares in the company and joined SoftBank Robotics as a Project Manager then SES-Imagotag (world leader in IoT deployments) as VP of Strategic program.

Being a passionate entrepreneur he became a Station F Selection Board Committee Member and co-founded Quizflip, an EdTech developing the world’s first electronic flashcard. The lack of product/market fit led him to put the project on hold and start to explore the blockchain technology.
He spent 6 months working on Tendermint and Ethereum as a CTO of H2O, a blockchain driven startup focusing on the entertainment industry, the company got quickly acquired. As an external consultant, he was lately a part-time CTO for UNESS, a ministry of higher education backed EdTech. The entrepreneurship and blockchain passions got Emmanuel and Marouane to join forces and start exploring staking derivatives.

Emmanuel holds Masters degrees from Ecole supérieure d’électricité, Georgia Tech and an MBA from INSEAD where he is also a member of the Business Angel Selection committee.

**Julien Klepatch: Lead Dev**

Julien used to work as a Financial Engineer in banking, and he switched to software development 5 years ago, as a contractor. He built dozens of web applications with Node.js/Javascript. He also setup the technical infrastructure of several token sales. Finally, He created Ethereum DAPPS and smart contracts for several crypto projects.

Julien was Employee #1 at Lendingblock, where he built the prototype of a crypto exchange in Node. and he also teaches Ethereum Dapps & Blockchain (Blockchain training / coaching) on his youtube channel EatTheBlocks.

Beside a solid experience in full stack web development and blockchain technologies, Julien have also setup continuous integration environments, ranging from simple setups with git hooks and bash scripts to more complex deployment scenarios with Jenkins, Ansible and Terraform.

Julien holds an MSc Engineering Degree from Ecole des Mines d’Albi and a MSc in Finance Degree from HEC.

**Reza Bakhshandeh: Back-end and smart contracts**

Software Engineering bachelor and AI master degree. Reza worked previously at Boosto.io and since june 2018 on PꝏlStake, he has 14 years experience in software development and spent the last 36 months designing Tokens and Solidity Smart Contracts. He will be working part-time on the slashing insurance product under Emmanuel’s supervision.


**Muhammad Mafazine: CSS, JS and HTML wizard**

Muhammad worked with Marouane on both LіquіdΒοх and PꝏlStake, he will be working part-time on the integration part of the front-end under Marouane’s supervision.


**Jean-Baptiste Soufron: Legal Advisor**

Lawyer and writer, he is known for his high expertise in the digital realm. His mastership and passion led him to be the Chief Legal Officer of the Wikimedia Foundation and director of the think tank Cap Digital. He was also General Secretary of the Conseil National du Numérique after being an advisor to french President François Holland.

(https://en.wikipedia.org/wiki/Jean-Baptiste_Soufron)
(https://www.fwpa-avocats.com/jean-baptiste-soufron)

UI/UX : 
Depending on when the project starts, we will be working with either :
[Julie Brasset](https://www.linkedin.com/in/julie-brasset-27211a71/)

Or :

[Julien Coudert](https://www.linkedin.com/in/julien-coudert/)

### Timeline, Milestones and Deliverables
_Detailed description of your timeline milestones and the corresponding payouts_

**Phase I**  			_Outline the different phases_

**Deliverables** 			_What features will be implemented_

**Time and Price Estimate**	_How long will it take and what is the estimated price_

**Phase II**  			_Outline the different phases_

**Deliverables** 			_What features will be implemented_

**Time and Price Estimate**	_How long will it take and what is the estimated price_

**Phase III**  			_..._


### Others	 
Anything else you want to share with us
