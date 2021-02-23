<!--
  Copyright 2018-2021 Cargill Incorporated
  Licensed under Creative Commons Attribution 4.0 International License
  https://creativecommons.org/licenses/by/4.0/
-->

# Grid Purchase Order

Grid Purchase Order offers an industry solution for sharing purchasing
information between trade partners. The component pairs GS1 data message
standards with a perspective on business process workflow to enable
collaboration. This allows trade partners to create and update purchase orders
in a shared state, unlocking greater efficiencies within the supply chain.

## Designed with flexibility in mind

Grid Purchase Order leverages other Hyperledger Grid components in an effort to
provide a generic solution that can serve a variety of business use cases. The
design provides businesses with the flexibility to configure the solution to
meet specific needs. A trade partner can:
- Define role-based access control for purchasing actions by using Grid
  Pike.
- Opt out of the default purchase order design and configure tailored workflow
  states, constraints, and permissions by using Grid Workflow.
- Bridge activity on Grid with external systems by using the Grid Integration
  Component.

## Roadmap

Grid Purchase Order is young in its product journey. The features listed below
offer a perspective on how the capability could evolve. These features will
change as the community surfaces business needs and feedback.

### In Progress

Features currently under review by the community.

- **Default Purchase Order workflows.** Provides Grid users with out-of-the-box
  workflows for collaborating on the creation and modification of purchase
  orders. The feature supports traditional buyer/seller relationships and
  vendor-managed procurement partnerships.

### Backlog

Features captured in the backlog as ideas, awaiting prioritization and
refinement by the community.

- **Configure custom Purchase Order workflows.** Enable Grid users to configure
  workflow states, business rules, and permissions to govern specific business
  process needs.

- **Introduce additional Purchase Order data elements.** Enhance the purchase
  order data model to support additional data elements such as allowance
  charges, subline-item information, etc.

- **Support configuration of Purchase Order data model.** Enable trade partners
  to configure which of the standard data elements may/may not be used for
  purchasing transactions within their business relationship.
