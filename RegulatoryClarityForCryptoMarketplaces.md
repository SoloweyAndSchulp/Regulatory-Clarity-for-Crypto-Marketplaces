# Regulatory Clarity for Crypto Marketplaces

### Jack Solowey and Jennifer J. Schulp  

#### December 2022

## Introduction
Marketplaces for buying, selling, and trading crypto tokens serve a diverse range of users, from sophisticated cypherpunks to casual retail customers. Some marketplaces provide intuitive onramps to the crypto ecosystem, allowing users to purchase cryptocurrencies with fiat money. Others provide technical infrastructure for decentralized finance, or “DeFi,” enabling permissionless, disintermediated global transactions. 

Like crypto tokens, the marketplaces on which they trade can be either centralized projects reliant on intermediaries (centralized exchanges, or “CEXs”), or decentralized protocols composed of code (decentralized exchanges, or “DEXs”). Tokens themselves can be centralized, exhibiting the characteristics of securities, or decentralized, functioning as commodities.**[1]**  The crypto ecosystem thus can be thought of as a two-by-two matrix consisting of both CEXs and DEXs for trading both crypto securities and crypto commodities (see Figure 1). 

This briefing paper proposes crypto marketplace regulatory policy that is sensitive to these distinctions. It calls for Congress to narrowly tailor rules to relevant risks by clearly defining what it means to be a decentralized exchange; providing centralized crypto token exchanges with a practical path to register with their respective regulators (e.g., the Securities and Exchange Commission (SEC) or the Commodity Futures Trading Commission (CFTC)); and making such registration by decentralized crypto token exchanges strictly voluntary. These proposals support informed consumer choice among different types of marketplaces based on individuals’ own needs, not legacy regulations that disserve the users, developers, and dynamism of decentralized marketplaces.**[2]**

## Background on Marketplaces and Their Regulation

Time-tested marketplaces for financial instruments have a history of evolving private rules and norms before the intervention of central governments.**[3]**  With respect to securities, the Buttonwood Agreement on stock trading—named, according to legend, for the buttonwood tree where New York’s early stock traders informally met—was signed in 1792, forming one of the bases for the New York Stock Exchange (NYSE).**[4]**  Notably, most state securities laws exempted stocks listed on the NYSE, which already provided its own stricter rules.**[5]**  The federal Securities Act would not come until 1933, and the Exchange Act until 1934. On the commodities side, the Chicago Board of Trade, incorporated in 1859, arose to help merchants regularize their trade and arbitrate disputes.**[6]**  From there, futures trading “emerged spontaneously” as a means of mitigating the risks of commodity price volatility.**[7]**  A relevant federal commodity futures law that passed constitutional muster would not come until the Grain Futures Act of 1922.**[8]**  

Modern exchange regulation in the U.S. seeks to address the “intermediary risks” posed by the middlemen that make up secondary markets for financial instruments.**[9]**  To this end, regulations under the Commodity Exchange Act (CEA) of 1936, as amended by the Commodity Futures Trading Commission Act of 1974, and the Securities Exchange Act of 1934 (Exchange Act), require, among other things, exchanges to register with and comply with the rules of their primary federal regulator (e.g., the CFTC or SEC) and to surveil and police members’ conduct.**[10]**  While the SEC and CFTC’s regulatory approaches differ, they serve similar functions.**[11]**  Both regulators seek to address risks related to asset custody, market transparency, market manipulation, and fraud. One of the core compliance responsibilities imposed on marketplaces is to protect against “trading abuses” and “price manipulation” by members.**[12]**  These include practices such as front running, wash trading, spoofing, and layering.**[13]**  The rationale for protecting against these practices is that they variously misappropriate protected information, fabricate transactions, violate duties to clients, or distort supply and demand signals.

### Defining Crypto Marketplaces

The first ever cryptocurrency tokens were mined on January 3, 2009, with the Bitcoin genesis block.**[14]**  The first secondary market cryptocurrency transaction effectively took place nine days later when Bitcoin’s pseudonymous creator, Satoshi Nakamoto, sent ten bitcoin to cryptographer Hal Finney.**[15]**  Bitcoin’s early trading was more buttonwood tree than NYSE, involving informal coordination between buyers and sellers over online message forums and using fintechs like PayPal to handle the fiat currency side of transactions.**[16]**  Early marketplaces followed, such as Bitcoinmarket.com (launched in 2010), which offered escrow trading and price data.**[17]**  

The first major centralized bitcoin exchange, Mt. Gox (founded in 2010), left an infamous legacy by filing for bankruptcy after revelations that hackers had stolen more than half a million bitcoin from the exchange.**[18]**  Its story is indicative of the risks facing exchange intermediaries, namely those related to custody, security, and the treatment of customer assets during bankruptcy. While a later generation of cryptocurrency exchanges has sought to mature the industry, the bankruptcy of centralized crypto exchange FTX demonstrates that not all have provided trustworthy solutions to intermediary risks.**[19]** 

Contemporary centralized crypto token exchanges, such as Coinbase (launched in 2012) and Binance (launched in 2017), allow users to buy, sell, and trade a variety of crypto tokens.**[20]**  While offerings vary, typical CEXs have several core attributes. They allow users to exchange cryptocurrencies for fiat currencies and typically custody assets on users’ behalf.**[21]**  In addition, CEXs typically organize sales with central limit order books, which match willing buyers and sellers at the best price (i.e., the highest bid and lowest ask touchlines).**[22]**  CEXs’ backend software and transaction histories also are not inherently public. Lastly, CEXs maintain the capacity to list or delist tokens and permit or block users’ ability to trade. Operationally, CEXs are a continuation of traditional intermediated exchanges for financial instruments. 

DEXs, by contrast, leverage smart contracts—software programs stored at blockchain addresses that self-execute when specified conditions are met—to disintermediate crypto token exchange.**[23]**  While designs vary, in their purest form, DEXs decentralize core exchange services: custody, market making or order book matching, and settlement.**[24]**  DEXs allow users to self-custody their tokens with their preferred hardware or software wallets for storing the unique private keys that control their own blockchain addresses.**[25]**  DEXs employ different solutions to organize sales, including automated market maker pools (AMMs) and on-chain order books.**[26]**  AMMs avoid order books entirely; instead of matching buyers and sellers, they incentivize the creation of standing liquidity pools composed of pairs of exchangeable tokens (e.g., USD Coin and Ether), the prices of which are determined automatically.**[27]**  On-chain order books match buyers and sellers, but unlike traditional exchanges, they host offers in smart contracts that make transactions transparent and do not rely on the good faith of middlemen for execution.**[28]**  

Unlike CEXs, DEXs cannot exchange fiat currency directly, only crypto tokens (including fiat currency-pegged stablecoins). DEXs composed of auditable smart contracts written in open-source code also are public by design. DEX protocols generally allow users to list their own tokens—provided the tokens’ underlying blockchain infrastructure is compatible with the relevant DEX smart contracts.**[29]**  While the providers of certain front-end graphical user interfaces for DEX protocols can effectively delist certain tokens from their front ends, because DEX smart contracts are open-source and can be freely copied and iterated on, the choices of one front end do not determine the capabilities of an entire DEX protocol.**[30]**  In addition, DEXs can provide community governance rights, allowing holders of specialized tokens to propose and vote on changes to protocols.**[31]** 

Fundamentally, in contrast to centralized crypto exchanges that are a continuation of traditional financial intermediaries, decentralized crypto exchanges are a break with history, replacing such intermediaries with open-source software.

## Addressing Intermediary Risks

Federal financial marketplace laws are designed to address intermediary risks. At a high level, these risks relate to custody (do intermediaries safeguard customer assets), market transparency (are transactions and trading practices publicly legible), and market manipulation (do unfaithful agents or fraudulent and deceptive practices harm market participants). These risks are not presented equally by CEXs and DEXs. For example, DEXs do not present the same custodial risks as CEXs, as DEX users typically self-custody their own crypto tokens.**[32]**  DEXs also operate in public, settling transactions on public blockchains and utilizing open and auditable smart contracts.**[33]**  Thus, subjecting bona fide DEXs to measures designed to ensure proper asset custody and facilitate examination of otherwise opaque marketplaces would be inappropriate.

DEXs are not immune, however, from manipulative trading strategies.**[34]**  But the relevant question for addressing this risk is what role DEXs play in creating vulnerability to it, as well as in preventing or remediating it. Front running, for example, occurs on DEXs, but not in the conventional form of exploiting non-public information.**[35]**  Rather, on DEXs, front running typically is an artifact of certain users—not the protocol—taking advantage of public information, such as a database of pending transactions waiting to be recorded on a blockchain.**[36]**  For that reason, regulating front running as an intermediary risk is not appropriate with respect to DEXs. 

Other forms of users’ manipulative trading practices that seek to influence supply, demand, price signals, and, in some cases, exchange fee generation, also can afflict DEXs, as can cybersecurity vulnerabilities.**[37]**  But the costs of mandating that DEXs take affirmative measures to address these risks exceed the benefits. For one, as described above, the public nature of blockchains means that DEXs need not be deputized to police activity on behalf of regulatory bodies who otherwise would have no market visibility. In addition, imposing a compliance regime designed for centralized intermediaries onto DEXs, such as mandates to maintain chief compliance officers, has the counterproductive consequence of reintroducing greater intermediary risk from active personnel. As discussed further below, permitting, not constraining, rapid iteration of DEX projects can improve consumer protection through competition. 

## A Framework for Crypto Marketplaces

Centralized and decentralized exchanges present different risk profiles. Regulations ought to be tailored accordingly. 

Outright fraud should be prohibited regardless of the type of marketplace in which it occurs.**[38]**  Securities laws and regulations already address this, making it unlawful to defraud or make untrue statements or misleading omissions of material fact in connection with the purchase or sale of any security.**[39]**  The same is effectively true in the commodities context, where it is unlawful to intentionally or recklessly defraud or make any untrue or misleading statement or omission of material fact in connection with a contract of sale of any commodity in interstate commerce.**[40]**  

Beyond anti-fraud authorities, however, applying legacy securities and commodity futures exchange rules to crypto marketplaces creates regulatory uncertainty, which undermines those marketplaces and fails to distinguish between centralized and decentralized exchanges. To resolve this ambiguity and provide rules that are narrowly targeted to relevant risks, Congress should define decentralized exchanges; permit DEXs to voluntarily register with their relevant regulator—the CFTC for crypto commodities marketplaces and the SEC for crypto securities marketplaces; and provide a practical registration pathway for centralized marketplaces (see Figure 2).

### Defining the DEX

To tailor rules to relevant risks and not chill the development of decentralized marketplaces, Congress ought to define DEXs. The main criterion is whether no single person or group has discretionary control over the DEX protocol. Evaluating this means considering both technical factors (e.g., whether the DEX is composed of open-source smart contracts) and agency factors (e.g., whether a DEX provider is making promises beyond mere code that the provider’s own performance is necessary for the DEX to operate or DEX users to receive certain benefits).**[41]**  For example, Congress should amend the Securities Exchange Act at 15 U.S.C. § 78c, and the Commodity Exchange Act at 7 U.S.C. § 1a to include: 

> Decentralized crypto **[commodity/security]** exchanges mean any market places or facilities for purchasing, selling, or trading crypto **[commodity/security]** tokens, where such market places or facilities: 
> - (A)	Are materially and substantially composed of permissionless, self-executing smart contracts written in publicly auditable, open-source code;
> - (B)	Do not rely on custodial intermediaries;
> - (C)	Allow for the continuous public retrieval of their transaction histories; 
> - (D)	Do not have outstanding, or possess on behalf of the market places or facilities, administrative privileges or tokens conferring protocol governance rights, such that any person or group maintains decisive, practical control over any final determination regarding a protocol improvement proposal, request for comment, or other decision to substantially change the functionality of the market places or facilities. Notwithstanding the foregoing, ministerially implementing changes resulting from a non-discretionary governance process shall not be construed, without more, as evidence of such decisive, practical control; and
> - (E)	Do not make to end users any implicit or explicit promises of performance without which such decentralized crypto **[commodity/security]** exchanges would not operate or produce their promised benefits. Notwithstanding the foregoing, representations over a front-end graphical user interface that do not materially differ from a reasonable articulation of the functionality of the exchange’s underlying software shall not be construed, without more, as such promises of performance.

### Voluntary Registration for DEXs

As described above, bona fide DEXs mitigate many intermediary risks by design. Where DEXs’ relevant risks are concerned, a competitive market for exchanges should be allowed to supply users with the level of consumer protection they demand. To achieve this, decentralized crypto commodities and crypto securities exchanges should be permitted to voluntarily register with the CFTC and SEC respectively. Voluntary, as compared to mandatory, DEX registration recognizes the capacity of DEXs to address intermediary risks through technology; promotes innovation in DEX design, including with respect to consumer protections; is adapted to the rapid pace of DEX iteration; and provides a wide berth for the capabilities of DEXs (e.g., their openness and interoperability). Nonetheless, in a world, as discussed below, where centralized exchanges register with their respective regulators, DEXs also should be afforded the option to signal that their consumer protection capabilities satisfy regulatory standards to at least the same degree as those of centralized exchanges. Users then can choose their preferred level of consumer protections.

An optional registration regime allows for greater experimentation and innovation in technical solutions for protecting users. One problem in applying legacy regulatory requirements to DEXs is that such requirements are designed for centralized intermediaries, so the simplest way for a DEX to comply with them would be to reintroduce greater intermediation. Under a mandatory registration regime, disintermediated safeguards that are unfamiliar to regulators create additional compliance risk at the margin. Making registration optional, by contrast, allows DEXs to legally operate while introducing novel consumer protective technologies. 

Optional DEX registration also promotes exchange competition, allowing consumers to choose the platforms they find to provide the optimal level of protection. Requiring DEXs to demonstrate proactive policies for their marketplaces inadvertently disadvantages DEXs inclined to deter manipulative trading practices and advantages DEXs that are not so inclined. Because DEX protocols are written in open-source code, which allows developers to permissionlessly reproduce and iterate on existing designs, the natural barriers to entry for DEXs are low. While compliance oriented DEXs would face heightened regulatory barriers in a world of mandatory DEX registration, rogue DEXs could go to market immediately, capturing the benefits of network effects. Optional registration, however, permits consumer-protection-oriented DEXs to launch on a competitive timeline, without prior restraint.

Lastly, voluntary DEX registration allows for DeFi advances generally. Among the properties that make DeFi innovative are that it is permissionless (i.e., open-source code and standards make accessing and iterating on DEX protocols free from gatekeeping by intermediaries or intellectual property restrictions) and composable (i.e., modular and interoperable protocols can be integrated with other DeFi applications). This counsels in favor of voluntary DEX registration for two related but distinct reasons. First, mandatory registration raises the compliance risk of a software application integrating the functionality of a DEX, undermining the creative potential of the DeFi ecosystem.**[42]**  Second, the permissionless and composable nature of DEXs means their iteration and development almost certainly will occur at a faster rate than the writing of new rules for registered DEXs or the invocation of exemptive authorities. Accordingly, making DEX registration optional preserves the open and iterative nature of the DeFi ecosystem. 

To avoid censoring the development and improvement of DEXs and diminishing DeFi’s creative dynamism, DEX registration ought to be strictly voluntary.

### Tailored Registration for CEXs

Rules regarding intermediary risks ought to be narrowly targeted to relevant hazards. In the case of centralized exchanges, questions exist as to what standards such intermediaries will apply for maintaining custody of customer assets, implementing cybersecurity safeguards, providing best price information, and protecting participants against fraudulent and deceptive trading practices. Existing financial regulations, however, especially when their application to crypto exchanges is left vague or inconsistent, have been obstacles to a robust crypto ecosystem replete with rational consumer protections, including those incentivized by private market competition.**[43]**  

It is a common misconception that crypto marketplaces are unregulated. At a high level, both crypto securities and crypto commodities are financial instruments, which generally are tightly controlled in the U.S. Specifically, crypto marketplaces in the U.S. currently are governed by, for instance, a patchwork of state money transmitter laws; the Federal Trade Commission and Consumer Financial Protection Bureau’s respective authorities to regulate unfair and deceptive acts and practices; and the perennial swords of Damocles of regulation by enforcement from the CFTC and SEC.**[44]** 

The multistate money transmitter regime creates, at best, compliance redundancies and, at worst, conflicting obligations. For example, New York’s requirements for maintaining crypto holdings on behalf of customers (e.g., that platforms hold crypto tokens of the same type and amount that they owe their customers) is directly at odds with Hawaii’s (e.g., that platforms hold cash, not crypto tokens, against customers’ deposits).**[45]**  Unsurprisingly, major crypto marketplaces avoid Hawaii.**[46]**  

With respect to CFTC and SEC regulation by enforcement, de jure legal ambiguity has not led to a light-touch or straightforward approach to financial markets regulated by private contract, property rights, and common law fraud remedies but rather to de facto blanket compliance risk, as regulators make ad hoc policy through enforcement actions and vague public pronouncements. The SEC takes the position that virtually all crypto marketplaces likely are operating as unregistered securities exchanges and “have an obligation to come in and register” with the SEC to avoid sanction and ongoing investigations.**[47]**  Similarly, the CFTC has levelled enforcement actions against crypto marketplaces that allegedly engaged in certain covered retail commodity or commodity derivatives transactions without registering as designated contract markets or futures commission merchants.**[48]**  Regulators apply legacy rules to crypto marketplaces but, practically speaking, have not provided means by which marketplaces can operate at scale without undue enforcement risk. 

Conflicting, unpredictable, and unworkable rules, as well as regulation by enforcement have a chilling effect on U.S. market participants.**[49]** 

#### Regulatory Clarity for Centralized Crypto Commodity Exchanges

To overcome this impediment to Americans’ ability to manage their own financial lives, Congress should alleviate the regulatory redundancy and uncertainty plaguing crypto commodity marketplaces. 

Heretofore, many proposals for regulating the crypto commodity spot market would expand the remit of the SEC to regulate commodity financial instruments in addition to securities, or subject crypto commodity exchanges to granular requirements from the CFTC.**[50]**  The latter would have the CFTC micromanage exchange personnel and policies and subject the crypto commodities they trade to oversight resembling merit-based regulation, giving the CFTC relatively broad authority to disapprove token listings.**[51]**  Neither of these approaches is desirable. As described in Cato Briefing Paper No. 140, SEC jurisdiction should be strictly limited to those crypto tokens that present risks related to managerial bodies (i.e., not crypto commodities).**[52]**  In addition, quasi-merit-based regulation of crypto commodities would lead to increased paternalism, with the CFTC having stricter standards for crypto commodities than the SEC ostensibly does for securities.

A better approach is to neither expand the SEC’s jurisdiction nor empower the CFTC to be a micromanager. Barring the replacement of the financial regulatory leviathan with uniform freedom to privately contract for financial instruments and remedy breaches of contract, property rights, and common law fraud prohibitions through private actions, if there must be a federal regulator of the crypto commodity spot market, Congress should delegate exclusive but strictly limited authority for that purpose to the CFTC.**[53]** 

The first step would be making technical amendments to the Commodity Exchange Act (7 U.S.C. § 1a) to define “crypto commodities” as those decentralized and decentralizing intangible assets that fulfill the criteria of the proposed sections 15 U.S.C. §§ 77b(a)(20), 77c(a)(15), and 78c(a)(81) provided in Cato Briefing Paper 140.**[54]**

The next step would be to provide for tailored registration by centralized crypto commodity exchanges that narrowly addresses intermediary risks. This means leveraging transparency and competition to drive consumer protection by requiring centralized crypto commodity exchanges to disclose their consumer protection standards. A disclosure-based approach allows consumers to choose their preferred level of protections and makes marketplaces’ compliance a matter of providing truthful and non-misleading information about their own practices. 

Congress should, for example, amend the CEA (7 U.S.C. § 1 et seq.) by providing a new section 5i containing the following provisions: 

> (a)	REGISTRATION. 
> - (1)	Subject to the exception provided in subsection (2), any market places or facilities for purchasing, selling, or trading crypto commodity tokens shall register with the Commission as crypto commodity exchanges.
> - (2)	Notwithstanding the requirements of subsection (1), and without prejudice to prohibitions against fraud, registration with the Commission by a decentralized crypto commodity exchange shall not be required and shall be strictly voluntary.
>
> (b)	PRINCIPLES.
> - (1)	To maintain registration as a crypto commodity exchange, such exchange shall disclose its policies regarding the core principles described in this subsection. An exchange shall be able to exercise reasonable discretion regarding the manner and design of such policies. The good-faith effort by a voluntarily registered decentralized crypto commodity exchange to disclose such policies shall not be construed as a basis on which to render such exchange ineligible for fulfilling the definition of a decentralized crypto commodity exchange.
> - (2)	TRANSPARENCY. To maintain registration as a crypto commodity exchange, such exchange shall provide an application programming interface to allow third parties, including users, to access best price and transaction volume data for traded tokens. A decentralized crypto commodity exchange under section 1a of this title shall be deemed to be compliant with this subsection. 
> - (3)	INSIGNIA. Registered crypto commodity exchanges shall be permitted to display an insignia of their registration with the Commission, which shall be unlawful to display where unregistered. 
> - (4)	PRINCIPLES. Registered crypto commodity exchanges shall disclose their standards and procedures, including such relevant automated configurations, controls, and protocols to, as applicable: 
>    - (A)	CUSTODY. Where maintaining custody over customer assets, securely custody, segregate, provide proof of reserves, liabilities, and solvency for, separately account for, and, for purposes of the U.S. Bankruptcy Code, treat as customer property, such customer assets.**[55]**
>    - (B)	SECURITY. Maintain cybersecurity, incident response, emergency preparedness, and disaster recovery configurations, controls, and safeguards.
>    - (C)	FREE MARKET. Maintain a free, open, and competitive market that protects the price discovery process from fraudulent and bad-faith trading practices, such as trades that are false, fabricated, in violation of fiduciary or agency duties, or that misappropriate protected or non-public information.
>
> (c)	Possession of tokens conferring decentralized exchange governance rights shall not, without more, be construed to create liability for the token holder for any action or omission of another token holder or of the decentralized exchange.

#### Regulatory Clarity for Centralized Crypto Security Exchanges

For years, the SEC has pursued a regulation by enforcement approach to crypto, substituting discretionary enforcement actions for formal, notice and comment rulemaking. This subjects crypto marketplaces to ill-fitting legacy regulations and makes it exceedingly difficult, if not impossible, for marketplaces to operate without undue compliance risk. 

The Securities Exchange Act defines an “exchange” as the provider of a “market place or facilities” for bringing together purchasers and sellers of securities or for otherwise performing the functions typical of a stock exchange.**[56]**  Subject to limited exceptions, the Exchange Act makes it unlawful for securities brokers, dealers, and exchanges to transact in securities using exchange facilities, unless the exchange is registered as a “national securities exchange.”**[57]**  Relatedly, only registered brokers or dealers are allowed to be members of national securities exchanges (i.e., transact on the exchange).**[58]**  In addition, securities traded on registered exchanges must themselves be registered with the exchange by their issuer.**[59]** 

The model of broker-intermediated transactions on national securities exchanges does not suit the reality of centralized, or decentralized, crypto securities marketplaces. Unlike national securities exchanges, crypto securities marketplaces provide direct access to retail customers, more closely resembling brokers than exchanges. In addition, when CEXs custody customers’ crypto tokens, it resembles the practice of broker-dealers registering securities using their firms’ “street names.”**[60]**  

In the 1990s, with the growth of network communication technologies enabling broker-dealers to provide their own trading venues to compete with the NYSE and NASDAQ, the SEC promulgated Regulation ATS to exempt alternative trading systems (ATSs) from the requirement to register as national securities exchanges, as long as they registered as broker-dealers and complied with ATS-specific requirements.**[61]**  While Regulation ATS offers a model for exempting crypto securities marketplaces from antiquated exchange rules, earlier this year, the SEC proposed a highly flawed update to the regulation. In addition to harming financial technology innovation more than it would help, the proposal arguably exceeded statutory authority in at least two ways: (1) with an overbroad expansion of the Exchange Act’s definition of exchange and (2) through a failure to sufficiently account for the economic impact of the proposal as required under the Exchange Act (e.g., by ignoring the impact on DeFi and the crypto ecosystem).**[62]**  The SEC should not promulgate these proposed amendments. 

In addition, Congress should amend the Exchange Act and instruct the SEC to tailor Regulation ATS to exempt crypto securities broker-dealers from inapt requirements and provide a streamlined registration path for crypto securities CEXs. As discussed above, registration of crypto securities DEXs, like crypto commodities DEXs, should be voluntary. 

Because crypto securities, unlike crypto commodities, involve managerial risks at the level of the token issuer, registered crypto securities marketplaces should have the capability to delist crypto securities tokens where the issuers have engaged in fraud or breached their own obligations. As proposed below, delisting standards should allow the market to provide a range of solutions, such as voluntarily registered DEXs leveraging third-party oracle nodes.

##### _Amending the Exchange Act_

First, Congress should amend the Exchange Act (15 U.S.C. § 78c) to define crypto securities, consistent with the criteria proposed in Cato Briefing Paper 140, as well as define crypto securities brokers and dealers: 
- The term “crypto security broker” means a market place or set of facilities for effecting transactions in crypto securities for the account of others, including by bringing together purchasers and sellers of crypto securities, as part of a regular business.
- The term “crypto securities dealer” means any provider of a market place or facilities for buying and selling crypto securities for such provider’s own account, through a crypto securities broker or otherwise, as part of a regular business.

Second, Congress should amend the Exchange Act’s provisions on the registration and regulation of brokers and dealers and, except for anti-fraud requirements, make them optional for crypto securities DEXs. For example, Congress should create a new 15 U.S.C. § 78o-12 based on 15 U.S.C. § 78o, applying relevant standards, such as the prohibitions on fraud and deception (15 U.S.C. § 78o(c)) to crypto securities brokers and dealers, but subject, for instance, to the following amendments and deletions:
- Replace all references to “broker” and “dealer” with “crypto securities” broker and dealer, respectively. 
- Expand the registration exemption to cover DEXs by adding to the end of subsection (a)(1): _“or is a decentralized crypto securities exchange, in which case, compliance with the requirements of this section, with the exception of subsection (c), shall be strictly voluntary. Voluntarily registered decentralized crypto securities exchanges shall be permitted to effect compliance with this section and the regulations promulgated hereunder through automated configurations, controls, and protocols, including, but not limited to, (i) delisting unregistered securities by reference to an oracle node and (ii) in lieu of, where applicable, written policies.”_
- Amend subsections (b)(1)(B) and (c)(2)(A) and delete subsection (b)(8) to make clear that a crypto securities broker-dealer is not required to be a member of a national securities association or national securities exchange.
- Amend subsection (b)(7) to require that any Commission standards for training, experience, and competence, or other qualifications for crypto securities brokers or dealers or associated persons shall not be imposed in the absence of an evidence-based identification of the material risks necessitating such standards and the market failure causing qualified individuals not to be employed in such roles; and to provide a pathway such that a history of carrying out covered duties without incident may satisfy requirements related to prescribed tests or credentials.  
- Amend subsection (c)(2)(E) to replace language that the Commission may propose certain rules at odds with determinations of the Secretary of the Treasury where they are necessary and appropriate “in furtherance of the purposes of this section” with _“in furtherance of a free market for crypto securities.”_
- Amend subsection (c)(5) to exempt automated market makers from the scope of market makers described therein.
- Amend subsection (c)(6) regarding Commission prescriptions with respect to the legacy clearance and settlement system for non-tokenized securities to instead address the requirement that registered crypto securities broker-dealers disclose and adhere to their policies regarding the custody of tokenized securities, including with respect to segregating, separately accounting for, and providing proof of reserves for such customer assets.

##### _Regulation “ATS-C”: A Crypto Counterpart to Regulation ATS_

Third, Congress should provide detailed instructions to the SEC to modify Regulation ATS, as originally promulgated, such that its requirements are made optional for decentralized crypto securities broker-dealers and pared back where they are not suited to the operation of crypto securities broker-dealers generally. For example, Congress should instruct the SEC to promulgate a proposed rule regarding Alternative Trading Systems for Crypto Securities (Regulation “ATS-C”) based on and in parallel to Regulation ATS (63 Fed. Reg. No. 245) subject to, for instance, the following amendments and deletions.**[63]** 

The general rules and regulations under the Exchange Act (17 C.F.R. § 240.3a1-1) should be amended to exempt decentralized crypto securities exchanges and registered ATS-Cs from the definition of the term “exchange” under the Exchange Act (15 U.S.C. § 78c(a)(1)) and from any requirement that such marketplaces be operated by a national securities association. In addition, Regulation ATS-C itself (§§242.X01(a) and 242.X01(b)(1)) should provide that registration as a crypto securities broker-dealer under the Exchange Act (15 U.S.C. § 78o-12), registration under Regulation ATS-C, and compliance with the requirements of Regulation ATS-C shall be strictly voluntary for decentralized crypto securities exchanges.

In Regulation ATS-C, the definition of “Alternative trading system for crypto securities” (ATS-Cs) should include crypto securities broker-dealers and voluntarily registered decentralized crypto securities exchanges; the definition of “covered security” should include only crypto securities. In addition, it should be clarified that automated market makers are not considered “exchange market makers” and that the definition of “control” is not applicable in the context of decentralized crypto securities exchanges. All references to “alternative trading system” should be replaced with “covered alternative trading system for crypto securities,” all references to “shares” should be replaced with “tokens,” and all references to “subscribers” with “users.”

Filing an initial operation report, e.g., a “Form ATS-C,” (§ 242.X01(b)(2)) should be electronic, allowing exchanges to submit relevant uniform resource locators for any landing pages, as well as copies of any applicable terms of use, terms of service, bylaws, articles of incorporation, trading policies, information security programs, and policies materially related to marketplace operations, such as listing and delisting criteria and customer asset and crypto security token custodial, asset segregation, account separation, and proof of reserve procedures and arrangements. Voluntarily registered decentralized crypto securities exchanges shall provide sufficient information to allow for the audit of their constituent smart contracts.

ATS-Cs providing application programming interfaces for third parties, including users, to access best price and order size data for their crypto securities transactions, along with decentralized crypto securities exchanges, shall be deemed compliant with requirements regarding the dissemination of quotations with respect to crypto securities (§ 242.X01(b)(3)).

Further technical amendments should include removing the applicability thresholds designed for legacy, non-tokenized securities from the provisions regarding fair access, system capacity, security, and integrity (§§ 242.X01(b)(5)(i) and 242.X01(b)(6)(i)); providing that information regarding grants or denials of access shall be kept on file for access by the Commission upon lawful request but need not be provided proactively or with Form ATS-C (§ 242.X01(b)(5)(ii)(D)); and eliminating requirements to quarterly file Form ATS-R (covering non-tokenized security transaction volumes) where ATS-Cs provide application programming interfaces allowing third parties, including users, to access crypto securities transaction dollar and token volume data (§ 242.X01(b)(9)). 

In addition, ATS-Cs should be allowed to use the term “exchange” in their names; registered ATS-Cs should be permitted to display to their end users an insignia of their registration with the Commission; and it should be unlawful for unregistered exchanges to display such an insignia (§ 242.X01(b)(11)).

##### _Procedurally Sound SEC Rulemaking_

Lastly, Congress should make clear that no rule or regulation regarding brokers or dealers as originally defined under the Exchange Act or new rule or regulation promulgated under the proposed 15 U.S.C. § 78o-12 shall apply to crypto securities brokers or dealers without additional notice and comment rulemaking specifically ensuring such rules’ relevance and necessity. 

Currently, for example, SEC Rule 15c2-11, which bars broker-dealers from transacting without certain information being available, can hinder broker-dealers transacting in crypto tokens, given the SEC’s argument that the relevant information does not exist for certain crypto tokens.**[64]**  In addition, the SEC’s Customer Protection Rule (SEC Rule 15c3-3) raises obvious questions for intangible asset intermediaries by requiring broker-dealers to maintain customer securities in their “physical possession or control” or at an adequate third-party control location, such as the Depository Trust Company.**[65]**  Centralized and decentralized ledger technologies offer ample tools for maintaining adequate custodial control, and regulations should suit this reality.

To ensure well-adapted regulations, Congress could, for instance, pass into law instructions that:
- No regulation promulgated under the Commission’s direct or delegated authority, including such rules for traditional broker-dealers, shall apply to crypto securities broker-dealers where such regulations: (i) inhibit the development of a free secondary market for crypto securities; and (ii) are not, as applicable, first introduced or re-introduced for express application to crypto securities broker-dealers as proposed rules that provide at least 90 days for accepting public comment thereon. 
- For each obligation under such rules, the Commission shall provide an estimate of its economic cost and impact, including with respect to both registered crypto securities broker-dealers and voluntarily registered decentralized crypto securities exchanges. 
- No obligation shall be imposed without a clear, evidence-based articulation of how and why the benefits thereof exceed the economic costs and do not substantially inhibit a free secondary market for crypto securities. Further, no such obligation shall be imposed that does not directly address an identified: (i) intermediary risk or (ii) market failure.
- The Commission shall not impose any obligation on a decentralized crypto security exchange that undermines such exchange’s ability to qualify for the definition of a decentralized crypto security exchange at 15 U.S.C. § 78c.

## Conclusion

To allow consumers to choose the marketplaces that best serve their needs, whether those venues be centralized or decentralized exchanges, regulations ought to be tailored to relevant risks. Subjecting decentralized exchanges, which leverage the core innovation of cryptocurrencies to disintermediate secondary markets, to regulations designed for intermediaries is inappropriate and hinders free and open innovation in the development of decentralized marketplaces. Accordingly, Congress should define what it means to be a decentralized exchange, offer an optional registration framework for decentralized crypto marketplaces, and provide a tailored registration framework for centralized crypto marketplaces.

## Endnotes

**[1]** See generally Jack Solowey and Jennifer J. Schulp, “Practical Legislation to Support Cryptocurrency Innovation,” Cato Institute Briefing Paper no. 140, August 2, 2022.

**[2]** The term “exchange” is used throughout this paper consistent with the convention for referring to crypto marketplaces as exchanges. It is not meant to imply that any marketplace is necessarily an exchange as defined by securities laws. 

**[3]** See Edward P. Stringham, Private Governance (New York: Oxford University Press, 2015), 95-99.

**[4]** “The History of NYSE,” International Exchange, Inc., last visited Sept. 26, 2022. 

**[5]** Elisabeth A. Keller, “Introductory Comment: A Historical Introduction to the Securities Act of 1933 and the Securities Exchange Act of 1934,” Ohio State Law Journal 49 (1988): 333.

**[6]** John H. Stassen, “The Commodity Exchange Act In Perspective: A Short and Not-So-Reverent History of Futures Trading Legislation in the United States,” Washington and Lee L. Rev. 39, no. 3 (1982): 827.

**[7]** Id. at 826 citing Holbrook Working, “Futures Trading and Hedging,” cited in B. Goss & B. Yamey, The Economics of Futures Trading (1976): 68-69.

**[8]** Id. at 829-830.

**[9]** See Kristin N. Johnson, “Decentralized Finance: Regulating Cryptocurrency Exchanges,” William & Mary Law Review 62, no. 6 (2021): 1922, 1925-1926, 1933-1934, and 1961.

**[10]** See Jerry W. Markham, “Commodity Exchange and Regulation” in Commodities: Markets, Performance, and Strategies, ed. H. Kent Baker (Oxford, UK: Oxford University Press, 2018): 41-46, 49, 50; 17 C.F.R. § 1.1 et. seq.;  Elisabeth A. Keller, “Introductory Comment: A Historical Introduction to the Securities Act of 1933 and the Securities Exchange Act of 1934,” Ohio State Law Journal 49 (1988): 347-351; and 15 U.S.C. §§ 78e, 78f, and 78l. See also “File No. 4-566: Surveillance, Investigation, and Enforcement of Insider Trading Rules,” Securities and Exchange Commission, modified October 1, 2020; and 15 U.S.C. § 78f(b)(1)-(5).

**[11]** See Heath P. Tarbert, “Rules for Principles and Principles for Rules: Tools for Crafting Sound Financial Regulation,” Harvard business L. Rev. 10 (2020). 
 
**[12]** 5 U.S.C. 78i; Jerry W. Markham, “Commodity Exchange and Regulation” in Commodities: Markets, Performance, and Strategies, ed. H. Kent Baker (Oxford, UK: Oxford University Press, 2018): 48-49. See also 15 U.S.C. Section 78f(b)(1)-(5).

**[13]** Front running is executing a transaction (whether buy or sell) based on non-public information in advance of a client’s intention to execute that transaction in order to take advantage of the anticipated price change. See “CFTC Glossary,” Commodity Futures Trading Commission, last visited Sept. 26, 2022. Wash trading is when traders give the false impression that they have moved into or out of a position but have not incurred actual risk (e.g., by selling on one exchange and buying on another), which can distort supply and demand signals or generate additional fees. See id. Spoofing is when sell or buy orders that ultimately will be cancelled are entered in order to generate the false appearance of greater buy or sell pressure, entice other market participants, and take advantage of the price movement. See “Potential Manipulation Report,” FINRA, last visited Sept. 26, 2022. Layering is similar to spoofing and involves the use of multiple orders at different price levels, which ultimately will be cancelled, in order to create the false appearance of movement in supply or demand, entice other market participants, and take advantage of price changes. See id.

**[14]** Daniel Phillips, “The Bitcoin Genesis Block: How It All Started,” Decrypt, Feb. 10, 2021. 

**[15]** Shaurya Malwa, “The First Bitcoin Transaction Was Sent to Hal Finney 12 Years Ago,” Decrypt, Jan. 12, 2021.

**[16]** See “New exchange (Bitcoin Market),” bitcointalk.org, Jan. 15, 2010; Martti Malmi (@marttimalmi), “Found the first known bitcoin to USD transaction from my email backups. I sold 5,050 BTC for $5,02 on 2009-10-12. https://blockchain.info/tx/7dff938918f07619abd38e4510890396b1cef4fbeca154fb7aafba8843295ea2,” Twitter post, Jan. 15, 2014, 9:04 a.m., https://twitter.com/marttimalmi/status/423455561703624704?s=20&t=dLjW8NriDqeFoWiOtlp4Kg; Kai Sedgwick, “Bitcoin History Part 6: The First Bitcoin Exchange,” Bitcoin.com, Dec. 25, 2018.

**[17]** Kai Sedgwick, “Bitcoin History Part 6: The First Bitcoin Exchange,” Bitcoin.com, Dec. 25, 2018; humanjets, “A Brief History Of Cryptocurrency Exchanges,” The Capital, Medium, Apr. 1, 2020.

**[18]** See Robert McMillan, “The Inside Story of Mt. Gox, Bitcoin's $460 Million Disaster,” Wired, Mar. 3 2014; Matthew Kimmell, “Mt. Gox,” CoinDesk, Jul. 22, 2021. 

**[19]** Jack Solowey, “Did Something Happen in Crypto This Week?” Cato at Liberty (blog), Cato Institute, November 11, 2022; Jack Solowey and Jennifer Schulp, “Don’t punish crypto for the sins of SBF’s FTX,” New York Daily News, November 29, 2022.

**[20]** In addition to their centralized exchanges, Binance also has offered its own DEX product and Coinbase has offered a self-custody wallet. Esat Dedezade, “Binance DEX Review: A Decentralized Exchange for Experienced Users,” Decrypt, February 5, 2021; “Coinbase Wallet,” Coinbase, last visited December 2, 2022. 

**[21]** Benedict George and Toby Bochan, “Centralized Exchange (CEX) vs. Decentralized Exchange (DEX): What’s the Difference?” CoinDesk, November 15, 2022.

**[22]** Will Kenton, “Limit Order Book,” Investopedia, modified May 2, 2022. See “Coinbase Markets Trading Rules,” Coinbase, last visited Sept. 26, 2022.

**[23]** See Jack Solowey, “Crypto’s Useful Future Was Vivified By the Correction,” RealClearMarkets, August 23, 2022.

**[24]** See “What is a DEX,” Coinbase, last visited Sept. 26, 2022.

**[25]** “What Is a DEX? How Decentralized Crypto Exchanges Work?” CoinDesk, February 11, 2022. See also Jack Solowey and Jennifer Schulp, “Don’t punish crypto for the sins of SBF’s FTX,” New York Daily News, November 29, 2022.

**[26]** Some “DEXs” use off-chain order books. The relevant qualities of decentralization for purposes of risk mitigation are outlined in the legal definition provided in the “Defining the DEX” section. 

**[27]** Matt Levine, “The Crypto Story,” Bloomberg Businessweek, October 25, 2022. While price mechanisms differ, the classic form relies on a constant product formula, by which the relative price of a token rises as its supply in the pool decreases. “Impermanent Loss in Decentralized Finance,” Cryptopedia, modified May 17, 2021. 

**[28]** See “History of DEXs: Phase 1,” IDEX, November 9, 2020.

**[29]** “What are decentralized exchanges, and how do DEXs work?” Cointelegraph, last visited December 1, 2022.

**[30]** Martin Young, “Uniswap delists 100 tokens from interface, including options and indexes,” Cointelegraph, Jul. 26, 2021; Ollie Leech, “What Is Uniswap? A Complete Beginner’s Guide,” CoinDesk, modified Sept. 22, 2021.

**[31]** moreReese and DJ, “What are Governance Tokens? How Token Owners Shape a DAO’s Direction,” Decrypt, March 29, 2022.

**[32]** Engaging in a token trade should not be confused with contributing tokens to a liquidity pool. The latter typically involves locking tokens in a smart contract. See “What Are Liquidity Pools?” Cryptopedia, modified Nov. 30, 2021. See also Jack Solowey and Jennifer Schulp, “Don’t punish crypto for the sins of SBF’s FTX,” New York Daily News, November 29, 2022.

**[33]** “What Is a DEX? How Decentralized Crypto Exchanges Work?” CoinDesk, February 11, 2022; “What is a DEX,” Coinbase, last visited Sept. 26, 2022; “Introduction to smart contracts,” Ethereum.org, last modified November 29, 2022. Certain order book-based decentralized exchanges also include off-chain trade logic. See Corey Miller, “What is on-chain vs. off-chain?” dydx.com, last visited November 11, 2022.

**[34]** See Onkar Singh, “What is front-running in crypto and NFT trading?” Cointelegraph, Mar. 26, 2022.

**[35]** Id. “CFTC Glossary,” Commodity Futures Trading Commission, last visited Sept 26, 2022. See Kristin N. Johnson, “Decentralized Finance: Regulating Cryptocurrency Exchanges,” William & Mary Law Review 62, no. 6 (2021): 1970-1971.

**[36]** See Onkar Singh, “What is front-running in crypto and NFT trading?” Cointelegraph, Mar. 26, 2022. “Mempool,” Binance Academy, last visited Sept. 26, 2022. Certain DEXs are built to counter this form of front running. One of these strategies involves hidden or encrypted mempools. See “Secret Network,” Messari.io, last visited Sept. 26, 2022. While it may raise questions about a DEX’s transparency, where settlement is on public blockchains and smart contracts remain open and auditable, this particular design choice need not be counted against a DEX’s ability to facilitate public inspection.

**[37]** Andrey Shevchenko, “For Some Reason, Wash Trading Happens on Decentralized Exchanges Too,” Cointelegraph, Jul. 25, 2020. See also Kristin N. Johnson, “Decentralized Finance: Regulating Cryptocurrency Exchanges,” William & Mary Law Review 62, no. 6 (2021): 1968-69. See Jack Solowey, “Dissent Is a Part of Crypto,” Cato at Liberty (blog), Cato Institute, August 19, 2022.

**[38]** In addition to specialized fraud statutes, the common law evolved to create civil liability for fraud. While case law and codified tests can vary by jurisdiction, representative elements of common law fraud (also known as fraudulent misrepresentation) are: (1) a false representation of a material fact; (2) made with knowledge of its falsehood or without knowledge of its truth; (3) with the intention to induce reliance; (4) that induced reliance; and (5) that resulted in financial harm due to that reliance. See, e.g., Valspar Refinish, Inc. v. Gaylord’s, Inc., 764 N.W.2d 359 (Minn. 2009). 

**[39]** 17 C.F.R. § 240.10b-5. See also 15 U.S.C. § 78j.

**[40]** 17 C.F.R. § 180.1. See also 7 U.S.C. § 9(1).

**[41]** See Jennifer Schulp and Jack Solowey, “DeFi Must Be Defended,” CoinDesk, October 26, 2022.

**[42]** See id.

**[43]** See Jennifer J. Schulp, “The SEC's Consistent Ambiguity,” National Review: Capital Matters, Sept. 28, 2022; Edward P. Stringham, Private Governance (New York: Oxford University Press, 2015), 98. See also Tim Copeland, “A DEX on Cosmos is working on a way to prevent front running,” The Block, November 5, 2021.

**[44]** See The White House, “FACT SHEET: White House Releases First-Ever Comprehensive Framework for Responsible Development of Digital Assets,” Press Release, September 16, 2022.

**[45]** Dennis Chu, “Broker-Dealers for Virtual Currency: Regulating Cryptocurrency Wallets and Exchanges,” Columbia Law Review 118, no. 8 (2018): 2342-2343; N.Y. Comp. Codes R. & Regs. tit. 23, § 200.9(b) (2017); Haw. Rev. Stat. §§ 489D-8, D-4 (2018). See Chelsee Yee, “Is cryptocurrency dead in Hawaii?” KHON2, May 2, 2022.

**[46]** See, e.g., “What countries and US states are supported for Coinbase and cash balances?” Coinbase, last visited October 14, 2022.

**[47]** Nikhilesh De, “SEC’s Gensler Holds Firm That Existing Laws Make Sense for Crypto,” CoinDesk, September 13, 2022. See “Crypto exchange Coinbase faces SEC probe over securities,” Reuters, July 26, 2022.

**[48]** See Complaint, CFTC v. Oooki DAO, Civil Action No. 3:22-cv-5416 (N.D. Cal. Sept. 22, 2022); “CFTC Charges 14 Entities for Failing to Register as FCMs or Falsely Claiming to be Registered” Commodity Futures Trading Commission, Release Number 8434-21, September 29, 2021.

**[49]** See Carol R. Goforth, “Critiquing the SEC’s On-Going Efforts to Regulate Crypto Exchanges,” William & Mary Business Law Review 14, (forthcoming 2022): 7-8.

**[50]** See Carol R. Goforth, “Cinderella’s Slipper: A Better Approach to Regulating Cryptoassets as Securities,” Hastings Business Law Journal 17, no. 2 (February 2021): 318; Digital Commodities Consumer Protection Act, S. 4760, 117th Cong. (2022).

**[51]** Merit-based regulation, unlike disclosure-based regulation, prohibits investment in instruments that regulators believe present too much risk. See Ronald J. Colombo, “Merit Regulation via the Suitability Rules,” Journal of International Business and Law 12, no. 1 (2013): 1. See Joseph A. Grundfest, “The Most Curious Rule Proposal in Securities and Exchange Commission History,” Harvard Law School Forum on Corporate Governance, May 17, 2022.

**[52]** Jack Solowey and Jennifer J. Schulp, “Practical Legislation to Support Cryptocurrency Innovation,” Cato Institute Briefing Paper no. 140, August 2, 2022, p. 2.

**[53]** 7 U.S.C. § 2(c)(2) of the CEA could be amended to provide the CFTC with exclusive jurisdiction over crypto commodity tokens.

**[54]** Jack Solowey and Jennifer J. Schulp, “Practical Legislation to Support Cryptocurrency Innovation,” Cato Institute Briefing Paper no. 140, August 2, 2022, pp. 2, 4.

**[55]** See Vitalik Buterin, “Having a safe CEX: proof of solvency and beyond,” Vitalik.ca, November 19, 2022.

**[56]** 15 U.S.C. § 78c(a)(1).

**[57]** 15 U.S.C. § 78e.

**[58]** 15 U.S.C. § 78f(c)(1).

**[59]** 15 U.S.C. § 78l.

**[60]** Registering a security under a “street name” is the practice of a broker holding the security in its own name instead of the owner’s. See “Street Name,” Investopedia, modified April 27, 2022. For the avoidance of doubt, references herein to “broker-dealers” refer to either brokers or dealers. See Dennis Chu, “Broker-Dealers for Virtual Currency: Regulating Cryptocurrency Wallets and Exchanges,” Columbia Law Review 118, no. 8 (2018): 2340.

**[61]** Carol R. Goforth, “Critiquing the SEC’s On-Going Efforts to Regulate Crypto Exchanges,” William & Mary Business Law Review 14, (forthcoming 2022): 11; 17 C.F.R. § 240.3a1-1.

**[62]** Carol R. Goforth, “Critiquing the SEC’s On-Going Efforts to Regulate Crypto Exchanges,” William & Mary Business Law Review 14, (forthcoming 2022): 25-27, 32-34.

**[63]** Section references for the proposed Regulation ATS-C in this paper are based on the original section numbers from Regulation ATS to allow for cross-referencing but replace the “300” numbering for relevant subsections of 17 C.F.R. Part 242 with an “X00” label as a placeholder.

**[64]** Carol R. Goforth, “Critiquing the SEC’s On-Going Efforts to Regulate Crypto Exchanges,” William & Mary Business Law Review 14, (forthcoming 2022): 37-38.

**[65]** 17 C.F.R. § 240.15c3-3(b)-(c); Division of Trading and Markets and Financial Industry Regulatory Authority Office of General Counsel, “Joint Staff Statement on Broker-Dealer Custody of Digital Asset Securities,” Securities and Exchange Commission, July 8, 2019. See Dennis Chu, “Broker-Dealers for Virtual Currency: Regulating Cryptocurrency Wallets and Exchanges,” Columbia Law Review 118, no. 8 (2018): 2352-2353. See also Elizabeth H. Baird, “ATS Role in the Settlement of Digital Asset Security Trades,” Securities and Exchange Commission, September, 25, 2020.
