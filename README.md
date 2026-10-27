# Climate Risk Transmission and Decision Simulator

## Project overview

This project explores how physical climate risks translate into operational and financial consequences for businesses, and how those consequences can inform investment and risk-management decisions.

The initial application focuses on **extreme heat and data centres**. As temperatures rise, facilities may face greater cooling requirements, higher electricity consumption and potential constraints on operating performance. These impacts can create financial exposure through increased operating costs, service disruption and lost revenue. The extent of that exposure depends on the facility's characteristics, its location and the measures available to manage the risk.

The project aims to connect these relationships in a single analytical framework, tracing climate hazards through asset-level vulnerability and operational impacts to financial outcomes and potential adaptation decisions.

## Conceptual approach

The proposed model follows five main stages:

1. **Climate hazard:** Represent extreme-heat exposure under different climate scenarios and time horizons.
2. **Asset vulnerability:** Examine how characteristics such as facility age, cooling technology, capacity and redundancy influence the asset's response to heat.
3. **Operational consequences:** Estimate potential changes in cooling demand, electricity consumption, operating constraints and downtime.
4. **Financial transmission:** Translate operational impacts into financial measures, including additional operating expenditure, lost revenue and changes in cash flow.
5. **Risk-management decisions:** Compare potential responses, such as maintaining existing infrastructure, retrofitting equipment or replacing systems, in terms of cost, potential risk reduction and residual exposure.

The central idea is that climate exposure alone does not determine financial risk. The same hazard can produce different outcomes across assets, and those outcomes may change depending on the investments made to improve resilience.

## Intended outputs

The project is intended to produce a model that allows users to compare how climate scenarios, asset characteristics and investment decisions influence operational and financial outcomes.

An eventual interactive application could let users select a data centre profile, vary the climate scenario and time horizon, and compare alternative interventions. Results could include estimated operating impacts, financial exposure, intervention costs and residual risk, with assumptions and uncertainty made visible.

The broader objective is to connect climate-risk analysis with decisions about capital allocation and asset management, rather than treating hazard exposure as an end in itself.

## Current scope and status

The initial scope is deliberately narrow: one sector, one physical hazard and a small set of representative asset profiles. Data centres and extreme heat provide a defined setting in which to explore the transmission of physical climate risk into financial outcomes before extending the framework to other hazards or sectors.

The project is currently at the **conceptual design stage**. The model architecture and proposed relationships have been outlined, but the underlying datasets, engineering relationships, financial calculations and intervention assumptions have not yet been fully specified or validated. Any future estimates will need to distinguish sourced evidence from illustrative assumptions.

The intended implementation is a Python-based analytical model with a Streamlit interface. The longer-term ambition is a transparent, adaptable framework for examining how climate risk propagates through assets and operations, how it affects financial performance, and where interventions may change the outcome.
