# mdm-governance-toolkit
Templates and frameworks for MDM governance design - Data dictionary, STTM, governance gate checklist, survivorship design guide. Based on production Customer 360 &amp; payment MDM implementations

Master data management (MDM) is not just a tech challenge but also a governance challenge. This repo contains the exact artifacts & templates requires to move nad MDM program from a business concept to an engineering specification. It focuses on the 'Design & Governance' phase, such that every data move is documented and every conflict has a resolution rule and every stakeholder is aligned before the code is written.

# Components
1. Source To Target Mapping (STTM)
   This template includes the 8 pillars of testable STTM: ->
   a. Source & target fields: Mapping raw extracts to canonical schemas.
   b. Transformation & Null logic: Clear rules for data movement
   c. Conflict resolution: Source system priority
   d. Acceptance criteria: Testable SQL queries to validate implementation

2. Data Dictionary & Taxonomy (Centralized definition of truth)
   a. Standardized naming conventions
   b. Business difintions to ensure cross departmental alignment

3. Survivorship & Trust Framework (Documentation on how to create the golden record)
   a. Trust Score: Logic why one source system is preffered over the other.
   b. Time decay rules: Accounting for data freshness in accuracy scores.
