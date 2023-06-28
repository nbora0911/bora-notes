## Chapter 1 

Whichever risk controls an organization implements, they’ll need to be paired with strong governance and **policies for the people** that build and maintain ML systems.

### Legal and Regulatory Landscape
1. [EU AI Act](https://artificialintelligenceact.eu/) - especially Annexes 1 and 3–8,
2. [Federal Reserve’s SR 11-7 guidance](https://www.fdic.gov/news/financial-institution-letters/2017/fil17022a.pdf) : pay special attention to the focus on cultural and organizational structures. Managing technology risks is often more about people than anything else.
3. [Washington DC’s proposed Stop Discrimination by Algorithms Act](https://dcchamber.org/algorithms-act/) attempts to replicate federal expectations for nondiscrimination and transparency, but for a much broader set of applications, for companies that operate in DC or use the data of many DC citizens.
4. Basic Product Liability: The Hand rule says that a product maker takes on a burden of care, and that the resources expended on that care should always be greater than the cost of a likely incident involving the product. 
5. In “Aiming for Truth, Fairness, and Equity in Your Company’s Use of AI,” the FTC states, “Hold yourself accountable—or be ready for the FTC to do it for you”
6. [Nist AI Rish Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)

### AI incidents
### Cultural Competencies for ML Risk Management
- Organizational Accountability
    - If no one's job is at stake when an ML system fails, gets attacked, or is abused for nefarious purposes, then it's entirely possible that no one in that organization really cares about ML safety and performances.In financial institutions, this responsibility is taken by a "Model Owner". In MRM, this involves accountable executibves and several teams that are responsible for the safety and performance of modeds and ML safety.
    - Key tenents that form cultural backbone for MRM
      - Written policies and procedures
      - Effective Challenge
      - Accountable leadership - if you boss really cares about ML system safety and performance, everyone cares about it. - similar to how Walmart's CEO in 2000s cared about sustainability; aligned it with org's core values; then everyone started caring about it
      - Incentives - Aligning timeline, performance evaluation, and pay incentives to team function helps solidify a culture of responsible ML and risk mitigation
- Culture of Effective Challenge
    - Actively challenging and questioning steps taken throughout the development of ML systems.
    - Structure helps here - Weekly meetings where current design thinkinh is questioned and alternative design choices are seriously considered. One way of doing it is to have decision matrix - rows are considerations for a decision and columns are options. 
- Diverse and Experienced Teams
    - Bottom line - have a domain expert in your team. I have felt the advantage of having a domain expert in my DS projects - example - politics
    - Generalist DS often lack the experience necessary to deal with domain-specific data and results. Misunderstand the meaning of input data and output results is a recipe for disaster that can lead to AI incidents when a system is deployed. 
- Drinking your own Champagne
    - I used this in Innovation Challenge! And I really this is the test of how much you trust your own product.
    - Also known as eating our own dog food.! - using our own software or products inside of our own organization.
    - In other words, if we're not comfortable using a system on ourselves or in our own organization, then we probably shouldn't deploy that system.
    - Few other things to consider
        - the carbon footprint of ML models
        - the possibility that an ML system could damage the environment by causing an AI incident. 
- Moving fast and breaking things
- 
###  Organizations Processes for ML Risk Management
- Forecasting Failure Modes: idea is to think through, document, and attempt to mitigate foreseeable failure models for ML systems. 
  - Known past failures -
        -  [“Preventing Repeated Real World AI Failures by Cataloging Inci‐ dents: The AI Incident Database"](https://arxiv.org/pdf/2011.08512.pdf)
        - one the most efficient ways to mitigate potential AI incidents in our ML systems is to compare our system design to past failed designs.
        - TODO | explore |  - https://incidentdatabase.ai/
        - TODO | blog | [“Overcoming Failures of Imagination in AI Infused System Development and Deployment"](https://arxiv.org/pdf/2011.13416.pdf)
        - It’s also possible that in performing the due diligence of researching and conceptualizing ML failures, we find that our design or system must be completely reworked. If this is the case, take comfort that a delay in system implementation or deployment is likely less costly than the h
- Model Risk Management Processes
  - Risk Tiering 
  - Model Documentation
  - Model Monitoring
  - Model Inventories
  - System Validation and process auditing
  - Change Management
- Beyond MRM
  - Model Audits and Assessments
  - ..


### Case Study: Zillow!
