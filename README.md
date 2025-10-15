# Entity-Resolution
Prototype project to demonstrate entity resolution.

Entity resolution (ER) is the process of stitching together disparate records that actually refer to the same real-world entity. In financial compliance, analysts need reliable clusters of customers, counterparties, and businesses before they can trace suspicious movement of funds. Production AML platforms ingest millions of transactions per hour, correlate them against equally large customer master files, and continuously adapt to new identifiers, aliases, and evolving fraud typologies. Getting ER wrong means missing illicit networks—or worse—flagging legitimate customers and slowing down compliance operations.

## Why entity resolution matters
- **Customer due diligence:** Financial institutions must understand who they are dealing with, even if customer data is fragmented across onboarding systems, KYC refreshes, or external data providers.
- **Network analytics:** Money laundering rarely looks suspicious in isolation. ER provides the reliable nodes that transaction monitoring, graph analysis, and case management layers depend upon.
- **Regulatory defensibility:** Audit trails are easier to justify when alert decisions rest on consistent, explainable entity groupings rather than ad-hoc record matching.

## Scaling in the real world

Large-scale AML ER systems operate under many constraints:

- **Volume and velocity:** Banks handle hundreds of millions of customers and billions of transactions. Matching requires smart blocking strategies, distributed storage, and near-real-time processing.
- **Data quality drift:** Misspellings, outdated addresses, and conflicting identifiers are common. Production-grade ER pipelines combine deterministic keys, probabilistic models, and human feedback loops.
- **Explainability and governance:** Compliance teams must articulate why two profiles were linked (or not). That calls for lineage tracking, feature logging, and policy enforcement. 

<img src="entity-graph.png" alt="Entity overview" width="700">  

*Figure 1. Graph view of an entity*

### Front End


### Back End

