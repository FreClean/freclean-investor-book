# Part VI: Business Model

## Value Proposition

For customers: reliable, affordable, environmentally responsible cleaning delivered by a locally rooted brand. For entrepreneurs and distributors: a route into the cleaning business via training, wholesale access, and franchise support. For the broader ecosystem: a Web3-enabled payment option (USDm/CELO) not commonly offered by cleaning businesses. **(Confirmed** as FreClean's stated value proposition.)

## Revenue Streams

FreClean states eleven distinct revenue lines: Professional Cleaning Services (residential, commercial, industrial), Product Manufacturing, Wholesale Distribution, Retail Sales, White-Label Manufacturing, Private Label Production, Franchise Opportunities, Business Consulting, Corporate Partnerships, and Training Programs. **(Confirmed** as stated; **TBD** for the relative revenue contribution of each, none of which has been disclosed.)

## Cost Structure

**(TBD for all figures.)** The structural cost categories a company with this business model would be expected to carry are: direct labor for service delivery; manufacturing and raw materials; packaging; distribution and logistics; brand/marketing; and platform/technology costs (see the companion `freclean-admin` specification for the internal operations platform this would eventually require). No specific cost figures have been published for any of these categories.

## Distribution Model

Direct sales, retail, wholesale, and (planned) online/e-commerce channels. **(Confirmed** as stated; **TBD** for which are currently active; see Part XIII.)

## Customer Acquisition

No customer acquisition channel, cost, or conversion data has been published. **(TBD.)** The most plausible acquisition channels, based on the business as described, are local word-of-mouth/referral (typical for a residential cleaning service) and the CeloHT ecosystem relationship (Part XI), which may provide a built-in early audience. **(Assumption.)**

## Retention

No retention or repeat-purchase data exists. **(TBD.)** Structurally, cleaning is a recurring-need category, which supports a subscription/repeat-service model in principle: but this is a category-level observation, not evidence of FreClean's actual retention.

## Partnerships

FreClean states it welcomes partnerships with businesses, hotels, restaurants, retail stores, government agencies, NGOs, educational institutions, environmental organizations, community associations, international organizations, technology companies, and distribution partners. **(Confirmed** as an open invitation; **Not Yet Verified** for any specific named partnership beyond the CeloHT relationship, which is itself **Confirmed** as stated but **Not Yet Verified** in its specific legal/contractual form.)

## Scalability

The services business scales primarily with labor and local operational capacity: inherently harder to scale rapidly than a pure digital product. The products business scales with manufacturing capacity and distribution reach: currently unconfirmed (Part X). The franchise model, if executed, is the most naturally scalable revenue line, since it transfers execution to franchisees rather than requiring FreClean to directly staff every new market. **(Analytical framework: this book's own assessment, not a FreClean-published scalability claim.)**

## Business Model Canvas

```mermaid
flowchart TB
    subgraph KP["Key Partners"]
        P1["CeloHT ecosystem<br/>(Web3 & digital inclusion)"]
        P2["Wholesale distributors<br/>(Planned)"]
        P3["Manufacturing partners<br/>(TBD)"]
    end
    subgraph KA["Key Activities"]
        A1["Cleaning service delivery"]
        A2["Product manufacturing<br/>& distribution"]
        A3["Entrepreneurship &<br/>franchise enablement"]
    end
    subgraph VP["Value Proposition"]
        V1["Reliable, affordable,<br/>eco-responsible cleaning"]
        V2["Entrepreneurship &<br/>economic empowerment"]
        V3["Modern digital payments<br/>incl. USDm / CELO"]
    end
    subgraph CR["Customer Relationships"]
        C1["Direct service delivery"]
        C2["Wholesale/distributor<br/>accounts (Planned)"]
    end
    subgraph CS["Customer Segments"]
        S1["Residential"]
        S2["Commercial &<br/>hospitality"]
        S3["Institutions & NGOs"]
        S4["Distributors &<br/>entrepreneurs"]
    end
    subgraph CH["Channels"]
        H1["Direct / on-site service"]
        H2["Retail & wholesale<br/>(Planned)"]
        H3["Digital / website<br/>(Planned)"]
    end
    subgraph CST["Cost Structure"]
        T1["Labor & service delivery"]
        T2["Manufacturing & materials<br/>(TBD supplier data)"]
        T3["Distribution & logistics"]
    end
    subgraph RS["Revenue Streams"]
        R1["Service contracts"]
        R2["Product sales<br/>(retail & wholesale)"]
        R3["White/private label<br/>manufacturing"]
        R4["Franchise fees<br/>(TBD terms)"]
    end

    KP --> KA --> VP --> CR --> CS
    KA --> CH --> CS
    CST -.funds.-> KA
    CS -.generates.-> RS
```

*(Diagram source: [`../../diagrams/business-model/business-model-canvas.mmd`](../../diagrams/business-model/business-model-canvas.mmd).)*

## Continuing

Part VII shows how products and services are designed to reinforce each other within this model.
