# Project Outline

> Working document. This is the project map, not a claim that every section is complete.

## 0. Executive Summary
- One-sentence product thesis
- Target user and use occasion
- Why hard-scoop robotics is interesting
- Why this should be premium rather than low-cost automation
- What success would look like after a pilot

## 1. Opportunity & Product Thesis

### 1.1 Problem
- Traditional scoop shops are labor-intensive but experience-rich
- Conventional vending is efficient but emotionally flat
- Robotic dessert systems often feel like technology demos
- Premium brands need new physical touchpoints that create attention and repeat visits

### 1.2 Product hypothesis
- A robotic hard-scoop kiosk can function as a **flavor-drop platform + physical brand experience**
- Limited menu and visible robotics can increase perceived value
- Location-specific flavors can give each deployment local relevance

### 1.3 What this product is not
- Not a cheap labor-replacement machine
- Not a full scoop-shop replacement
- Not a 20+ flavor self-service freezer
- Not a one-off trade-show robot demo

## 2. Customer Experience

### 2.1 Customer journey
1. Notice the machine
2. Understand the Robot-Dipped joke/premise
3. Browse a curated lineup
4. Choose flavor / serving size
5. Watch the robot scoop
6. Receive the product
7. Share / revisit / discover the next drop

### 2.2 Experience principles
- Visible mechanical theater
- Fast comprehension from several meters away
- Short decision time
- Clear recovery when something fails
- No industrial-equipment-bolted-into-a-kiosk appearance
- The robot movement should look intentional, not merely functional

### 2.3 Signature details to explore
- Retro neon ROBOT-DIPPED ICE CREAM
- Transparent scooping theater
- Pick-up lighting / completion ritual
- Flavor-drop countdowns
- City-specific UI
- Pick-a-Side local rivalry concepts

## 3. Flavor & Content Platform

### 3.1 3 + 3 + 1 + 2 architecture
- 3 Classics
- 3 New Releases
- 1 Robot Exclusive
- 2 Seasonal / City Exclusives

### 3.2 Robot Flavor
- Signature visual direction: silver-gray + white
- Could become a rotating collaboration slot
- Example prompt for R&D/brand teams: **What does a robot taste like?**
- Must remain an actual food product first, not only a visual gimmick

### 3.3 Local flavor model
- Avoid one-machine-only manufacturing SKUs where possible
- Prefer regional foodservice SKUs shared across nearby stores/events
- Explore base + finishing-kit strategies to lower complexity

### 3.4 Collaboration framework
- Technology brands
- Sports teams
- Local institutions
- Seasonal cultural moments

## 4. System Architecture

### 4.1 Major subsystems
- Refrigerated flavor storage
- Tub/cassette positioning
- Scoop end-effector
- Robot/gantry/SCARA motion system
- Force sensing / surface sensing
- Cup or cone handling
- Cleaning/rinse station
- POS/payment
- UI/experience software
- Remote telemetry
- Safety interlocks

### 4.2 Architecture questions
- Robot arm vs Cartesian vs SCARA
- Fixed scoop station + rotating carousel vs robot visiting every tub
- Standard commercial tubs vs purpose-designed cartridges
- Vision vs depth sensing vs force-based surface estimation
- Central controller vs modular PLC/IPC architecture

### 4.3 Product-control principle
Engineering owns safety and feasibility; product owns the intended experience. Critical experience principles should not disappear silently through implementation convenience.

## 5. Scooping Mechanism

### 5.1 Inputs that change scoop behavior
- Temperature
- Fat/sugar composition
- Overrun
- Surface geometry
- Inclusion size/hardness
- Remaining tub depth

### 5.2 Failure cases
- Missed scoop
- Oversized/undersized scoop
- Chunk collision
- Scoop sticks to tool
- Product falls outside cup
- Tub nearly empty
- Surface becomes inaccessible

### 5.3 Prototype questions
- Force/torque thresholds
- Heated vs ambient vs rinsed scoop head
- Scoop trajectory library
- Surface map update frequency
- Serving mass tolerance

## 6. Food Safety & Cleaning
- Allergen cross-contact strategy
- Tool rinse/sanitize cycle
- Drip/waste management
- Cleaning validation
- Overnight/deep-clean procedure
- Temperature excursions
- Food-contact materials
- Failure-safe behavior
- Service access without contaminating food zones

## 7. Industrial Design & Human Factors

### 7.1 Visual language
- Premium retro-futurism
- Integrated appliance, not exposed automation cell
- Robot visible only where it adds theater
- Easy-to-clean exterior
- High service access without obvious service clutter

### 7.2 Human factors
- Accessibility
- Reach heights
- Screen readability
- Queue behavior
- Child interaction
- Noise
- Pinch-point perception
- Pick-up ergonomics

## 8. Operations & Serviceability
- Refill procedure
- Daily opening/closing
- Flavor swap time
- Waste handling
- Remote diagnostics
- Predictive maintenance opportunities
- Spare-module strategy
- MTBF / MTTR targets
- Who services the robot?
- What can venue staff safely handle?

## 9. Supply Chain & SKU Strategy
- Central production constraints
- Bulk foodservice format
- MOQ risk
- Regional SKU pooling
- Seasonal SKU sunset
- Local finishing kits
- Packaging/cassette return logistics
- Cold-chain constraints

## 10. Business Model & Unit Economics
- Premium price positioning
- Capex estimate
- Labor avoided vs labor relocated
- Venue revenue share
- Maintenance cost
- Cleaning consumables
- Waste
- Payment fees
- Gross margin per serving
- Throughput assumptions
- Payback period
- Why the product should not compete on low price

## 11. Pilot Design

### 11.1 Pilot objective
Prove product desirability, mechanical reliability, food safety, and operational viability—not national-scale economics.

### 11.2 Candidate pilot environments
- Tourist destination
- Cinema
- University
- Airport
- Entertainment venue

### 11.3 Metrics
- Orders/day
- Conversion from passersby
- Repeat purchase
- Flavor mix
- Robot Flavor attach rate
- Average service time
- Scoop failure rate
- Downtime
- Cleaning burden
- Social sharing / earned media
- Customer willingness to pay

## 12. 1 → 15 Unit Learning Rollout

The preferred learning model is **not** immediate national rollout.

- Unit 1: prove the full experience
- Units 2–5: test different venue archetypes
- Units 6–15: validate service model and repeatable deployment
- After ~15 units: decide whether to hand off scale-out to a dedicated rollout/operations organization

## 13. Governance & Decision Rights

Draft model:
- Product lead owns product thesis, experience principles, prioritization, and integrated trade-offs
- Engineering owns safety, technical integrity, and feasibility evidence
- Operations owns maintainability evidence
- Food/R&D owns formulation and food-safety compliance
- Brand owns brand integrity
- Major compromises should be explicit decisions, not gradual erosion

## 14. Risk Register

Initial categories:
- Mechanical reliability
- Food safety
- Allergen management
- Cleaning burden
- Low throughput
- Poor serviceability
- Brand novelty wears off
- Venue economics fail
- SKU complexity
- Vendor lock-in
- Over-designed experience delays pilot
- Product principles become too rigid

## 15. Handoff Strategy

This project should be designed to move from high-creativity incubation into repeatable execution.

Handoff package should eventually include:
- frozen product requirements
- approved architecture
- supplier BOM
- SOPs
- service model
- deployment checklist
- acceptance test plan
- product principles
- known compromises
- operating metrics
- V2 opportunity backlog

The innovation team should not remain the permanent rollout team.

## 16. Portfolio Artifacts to Add
- System block diagram
- Customer journey
- Industrial design renders
- Functional decomposition
- Decision log
- Trade-off matrix
- Failure-mode table
- Pilot KPI dashboard mockup
- 1→15 rollout map
- Unit economics model
- Example Chicago flavor strategy
- Example AI-collaboration Robot Flavor concept

## 17. Open Questions
- How much technical detail should be simulated vs experimentally prototyped?
- Can a simple benchtop force/scooping experiment be built?
- What parts can be modeled in CAD?
- Which foodservice constraints require expert interviews?
- What evidence would be strong enough to change a core product principle?
- Where is perfection valuable, and where does it become over-design?
