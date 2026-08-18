# Part XI: Technology

## Principle

This chapter treats technology as a business enabler to be evaluated on the same evidentiary standard as any other operational capability: not as a marketing narrative. Web3 and blockchain elements, in particular, are described only to the extent they are actually confirmed, with no amplification of their business significance beyond what the evidence supports.

## Website

FreClean's public-facing digital presence, as of this book's preparation, consists of a GitHub Pages–hosted static site and the linked `freclean.com` domain. **(Confirmed** to exist; **TBD** for functionality: no confirmed e-commerce, booking, or account system has been verified as live on it.)

## Digital Commerce

**(TBD.)** No confirmed online checkout, cart, or order-processing capability exists today.

## Administrative Platform

A complete functional specification and a working **UI prototype** exist (`freclean-admin`), covering customer management, sales/orders, inventory, and reporting/analytics modules. The prototype uses bundled fictional sample data, has no backend, no database, and no authentication, and is explicitly documented as a design reference rather than a production system. **(Confirmed** to exist in this form; **Planned/TBD** for any production build.)

## Inventory & Customer Management Systems

Specified (in `freclean-admin`) but not built as live systems; see Part X.

## Analytics

**(TBD.)** No analytics platform, dashboard, or KPI tracking system currently operates on real FreClean data. A reporting module specification exists, using the same prototype/sample-data caveat as above.

## Digital Payments

FreClean states it accepts cash, bank transfer, mobile money, debit and credit cards, digital wallets, USDm, and CELO. **(Confirmed** as a stated payment-acceptance policy. **TBD** for actual transaction volume through any digital or crypto channel, which has not been disclosed.)

## CELO and USDm Integration

This is the part of FreClean's public materials that most needs restrained, non-promotional framing, and this book applies that restraint deliberately.

**USDm** is a US-dollar-pegged stablecoin issued through the Mento Protocol on the Celo blockchain. It carries the same practical role FreClean originally described under the name cUSD: a way to move money that tracks the dollar closely, without the price swings of a typical cryptocurrency. The Mento Protocol renamed cUSD to USDm (Mento Dollar) in late 2025 as part of a broader rebrand of its stablecoin family, and USDm is the name in active use across the Celo ecosystem today. FreClean's stated rationale for preferring it, price stability, low transaction fees, and the ability to send money across borders without a bank, is consistent with what USDm is designed to do. This book has not independently verified the specific fee or settlement-speed figures FreClean cites, and treats them as FreClean's claim rather than as tested fact.

**CELO**, unlike USDm, is the network's native asset and fluctuates in price like any other cryptocurrency. FreClean's public materials do not explain how that volatility would be handled at the point of sale: who absorbs the gap between what a customer pays and what FreClean receives, or how a refund would work if the price moved in between. That gap is real and unresolved, not a detail this book is choosing to skip.

**Valora** is the mobile wallet FreClean recommends to customers for sending, receiving, and holding USDm and CELO. It supports QR-code payments, which is the practical mechanism by which a customer would actually pay a FreClean invoice in USDm at a till or during a service visit. Beyond this stated recommendation, no data exists on how many customers have used Valora with FreClean or how frequently.

No KYC or anti-money-laundering policy, no refund process for crypto payments, and no jurisdiction-by-jurisdiction review of accepting cryptocurrency for consumer transactions in Haiti or the Dominican Republic has been published. **(TBD.)**

FreClean states it is powered by **CeloHT**, a Haitian Web3 initiative focused on financial inclusion, blockchain education, digital payments, and practical adoption within the Celo ecosystem. CeloHT and FreClean are distinct: CeloHT is the ecosystem initiative, and FreClean is a business that draws on it for payments infrastructure and, by association, some of its credibility and reach. FreClean is not CeloHT, and CeloHT is not a FreClean product. **(Confirmed** as a stated relationship. **Not Yet Verified** in its specific legal or contractual form.)

This book's assessment: the USDm and CELO integration is a real, stated capability with a plausible rationale, particularly given the diaspora-payments angle discussed in Part VIII, but it currently raises more open compliance and consumer-protection questions than it answers. It belongs on the page as an early-stage payment option under active development, not as a finished differentiator.

## Future Technology Opportunities

Once `freclean-api` exists to connect the admin platform to real data, and once a real website/e-commerce layer is built, the technology stack described in this chapter could meaningfully reduce operational overhead relative to a purely manual/paper-based cleaning business. This is a reasonable, non-hyped expectation for what good execution on the existing specifications could deliver: not a promise of when it will happen.

## Continuing

Part XII turns to FreClean's brand: the one area of the ecosystem with the most mature, professionally developed foundation already in place.
