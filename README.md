# Awesome-Multi-Echelon-Inventory-Optimization

## Top Multi-Echelon Inventory Optimization (MEIO) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Multi-Echelon Inventory Optimization, Safety Stock Positioning, Network Inventory Planning, Service-Level Optimization & Supply Chain Working-Capital Reduction*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Multi-Echelon Inventory Optimization (MEIO)**. These systems determine optimal inventory levels and safety-stock placement across multiple stages of a supply chain (plants, distribution centers, warehouses, stores) simultaneously—balancing service levels, holding costs, and uncertainty in demand and lead times.



**Examples** include ToolsGroup, Smart Software, Blue Yonder MEIO, GAINS, Lokad, RELEX Solutions, Slimstock, Logility, OMP, and Kinaxis (the category leaders).



**Open-source emphasis**: Production-grade MEIO with probabilistic modeling, large-scale network optimization, and enterprise integration remains almost exclusively commercial. Open-source activity is concentrated in academic libraries, simulation-optimization frameworks, linear-programming examples, and reinforcement-learning research. This section lists every significant relevant project and building block found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ToolsGroup](https://www.toolsgroup.com/)**  

  Specialist in probabilistic demand forecasting and multi-echelon inventory optimization. Strong at service-level-driven safety stock across complex networks, including intermittent and long-tail demand.



- **[Lokad](https://www.lokad.com/)**  

  Quantitative supply-chain optimization platform emphasizing probabilistic forecasting, inventory, and decision automation with a programmable approach (Envision language).



- **[Blue Yonder MEIO, RELEX Solutions, Logility](https://blueyonder.com/)**  

  Enterprise supply-chain planning suites that include multi-echelon inventory optimization as part of broader demand, supply, and inventory planning capabilities.



- **[GAINS, Slimstock, Smart Software](https://www.gainsystems.com/)**  

  Inventory optimization and planning platforms focused on multi-echelon or multi-location stock positioning, service levels, and working-capital efficiency.



- **[OMP, Kinaxis](https://www.omp.com/)**  

  Advanced planning and concurrent planning platforms that support network inventory optimization within end-to-end supply-chain decision making.



- **[Other MEIO & inventory optimization platforms](https://www.toolsgroup.com/)**  

  Additional commercial solutions covering safety-stock optimization, multi-echelon positioning, and integrated inventory planning.



## Open-Source GitHub Projects



- **[Stockpyl](https://github.com/LarrySnyder/stockpyl)**  

  Open-source Python library for inventory optimization, including multi-echelon methods under the stochastic-service model (SSM) and guaranteed-service model (GSM). Supports serial and tree systems with exact and approximate algorithms.



- **[Multi-Echelon Inventory Optimization (SimPy + black-box optimizers)](https://github.com/anshul-musing/multi-echelon-inventory-optimization)**  

  Simulation-optimization framework using discrete-event simulation (SimPy) combined with SciPy, scikit-optimize, and RBFOpt to optimize inventory across multi-echelon networks while meeting service-level targets.



- **[Linear Programming MEIO examples](https://github.com/shashboy/Multi_Echelon_Inventory_Optimization)**  

  Educational / research implementations that formulate multi-echelon finished-goods inventory optimization as linear programs (e.g., via PuLP) across factories, RDCs, and customers.



- **[Reinforcement Learning for Multi-Echelon Inventory](https://github.com/singhdivyank/multi-echelon-rl-inventory)**  

  Research projects applying deep RL (A3C, PPO) to multi-echelon inventory control under stochastic demand, with comparisons to classical (s, S) policies.



- **[Broader inventory optimization & supply-chain OR projects](https://github.com/search?q=multi-echelon+inventory+OR+MEIO+OR+inventory+optimization)**  

  Academic and community repositories exploring base-stock policies, safety-stock placement, and network inventory models.



- **[Demand forecasting + inventory open libraries](https://github.com/search?q=inventory+optimization+OR+safety+stock+python)**  

  Open tools for forecasting, newsvendor models, and single-echelon optimization that can serve as building blocks for custom MEIO approaches.



- **[Simulation frameworks for supply chains](https://github.com/search?q=supply+chain+simulation+OR+SimPy+inventory)**  

  Discrete-event and agent-based simulation projects used to evaluate inventory policies across multi-stage networks.



- **[Optimization solvers & modeling layers](https://github.com/search?q=PuLP+OR+OR-Tools+inventory)**  

  General-purpose open solvers (PuLP, OR-Tools, etc.) frequently used to implement custom inventory and network optimization models.



### Additional Strong Open-Source Options



- **Stockpyl + custom data pipelines**: Academic-grade MEIO algorithms applied to real network data.

- **Simulation-optimization loops**: SimPy or similar engines wrapped with black-box or meta-heuristic optimizers.

- **LP / MILP formulations**: Explicit multi-echelon models solved with open solvers for smaller networks.

- **RL / adaptive policies**: Experimental agents that learn inventory decisions under uncertainty.

- **Forecasting libraries**: Open probabilistic or intermittent-demand forecasting tools feeding inventory models.

- Research-to-production path: Prototype with Stockpyl or custom optimizers, then evaluate commercial MEIO for scale, support, and integration.



**Frameworks for building custom systems**:  

There is no mature, production-ready open-source equivalent to commercial MEIO platforms (ToolsGroup, Lokad, Blue Yonder, RELEX, etc.).  

The strongest open foundations are **Stockpyl** (algorithmic MEIO library), simulation-optimization repositories, and general optimization/simulation toolkits.  

These are excellent for research, education, and prototyping on modest networks.  

Enterprise MEIO requires robust probabilistic demand modeling, scalable solvers, data integration, what-if scenario management, and ongoing model maintenance—capabilities that commercial platforms have industrialized.  

Most organizations use commercial MEIO for live planning and may leverage open-source components for research, benchmarking, or specialized extensions.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Inventory optimization directly affects service levels, working capital, and operational risk. Models must be validated against real demand, lead-time, and cost data; incorrect parameters can cause stockouts or excess inventory.

- Open-source MEIO and simulation tools offer transparency and learning value but generally lack the scalability, support, and production hardening of commercial systems. Evaluate data quality, computational requirements, and organizational expertise before relying on custom implementations for critical planning.



---



**Made for supply-chain planners, inventory analysts, operations researchers, and practitioners optimizing multi-stage networks.**  

Let's advance open methods and research for multi-echelon inventory optimization while recognizing the specialized probabilistic engines and enterprise capabilities that leading commercial MEIO platforms deliver.
