# IntelligentOS Engagement Model

**Audience:** Account teams, delivery teams, product managers

**Purpose:** Understand how our three IntelligentOS views work together at different resolutions to guide AI transformation engagements.

---

## The IntelligentOS Approach

We look at a company through three lenses, providing a view into different altitudes of the business. Think of them as zoom levels on a map—same territory, different detail.

**The Three Views:**

1. **Strategic Foundation Model** - Strategic foundation and organizational readiness
2. **Target Operating Model** - Value streams, workflows, and operational execution
3. **Agentic Platform Architecture** - Technology infrastructure enabling AI transformation

All three views map to a common architectural stack:
**Business → Value Streams → Orchestration → Workflows → Agents → Semantic Layer → Data → Infrastructure**

---

### 1. Strategic Foundation Model
**Purpose:** Client-facing strategic communication  
**Audience:** C-suite, leadership teams  
**Resolution:** Strategic Foundation Mapping

This is what we show leadership teams to frame the engagement. It's the simplest, clearest view of our approach.

**Strategic Foundation Mapping:**

1. Vision, Mission, Purpose (VMP)
2. Brand Identity & Positioning
3. Culture & Values
4. Strategic Priorities & OKRs
5. Business Model

**Architectural Stack Mapping:**
- **Strategic Foundation Mapping** → Business Layer

**When to use:** Initial client conversations, executive presentations, strategic alignment sessions

---

### 2. Target Operating Model
**Purpose:** Structural definition and data schema  
**Audience:** Delivery teams, platform engineers, transformation consultants  
**Resolution:** Four-level hierarchy

This defines the data structure we use to document the operating model. It's the container that holds all the details we discover and the recommendations we make.

**Four Levels:**
1. **Value Stream** - Strategic view
2. **Workflow Group** - Coordination view
3. **Workflow** - Execution view
4. **Steps** - Action display (shown within workflows, not a separate level)

**What's captured at each level:**
- Business view (always visible): owners, purpose, dependencies, governance, pain points
- Engineering view (collapsible): data model, state management, integration requirements

**Architectural Stack Mapping:**
- **Value Stream Level** → Business + Value Streams Layers
- **Workflow Group Level** → Orchestration Layer (coordination)
- **Workflow Level** → Workflows Layer (execution specifications)
- **Steps** → Actions (human or agent-executed)
- **Engineering Spec View** → Agents + Semantic + Data + Infrastructure Layers

**When to use:** Workshop documentation, platform requirements gathering, detailed process mapping

---

### 3. Agentic Platform Architecture
**Purpose:** Technology infrastructure and AI enablement  
**Audience:** Platform engineers, AI/ML teams, technical architects  
**Resolution:** Four-layer technical stack

This defines the technical foundation that enables AI-native operations. It specifies the infrastructure, agents, semantic layer, and data architecture required to deliver intelligent workflows.

**Four Technical Layers:**

1. Agents Layer
2. Semantic Layer
3. Data Layer
4. Infrastructure Layer

**Architectural Stack Mapping:**
- **Agents Layer** → Agents Layer
- **Semantic Layer** → Semantic Layer
- **Data Layer** → Data Layer  
- **Infrastructure Layer** → Infrastructure Layer

**When to use:** Platform design, technical architecture, AI implementation planning, infrastructure requirements

---

## Discovery Methodology

**Purpose:** Assessment and design methodology that works across all three views  
**Audience:** Transformation consultants, product managers  
**Resolution:** Eight phases (0-7)

This is our methodology for HOW we gather data, assess current state, and design future state. These phases represent the discovery and design process, not the structure of the output.

**Eight Phases:**
- **Phase 0:** Current State Assessment
- **Phase 1:** Success Model & KPIs
- **Phase 2:** Value Streams (Enterprise Flow Architecture)
- **Phase 3:** JTBD, Journeys, and Workflow Blueprint
- **Phase 4:** Decision Architecture
- **Phase 5:** Roles, Org Design, and Capabilities
- **Phase 6:** Workflow to Platform Translation
- **Phase 7:** Change Enablement and Adoption

**Key insight:** These phases don't map 1:1 to the other views—they cut across them. Multiple Discovery Methodology phases work across different layers of the architectural stack.

**Architectural Stack Mapping:**
- **Phase 1** → Business Layer (Success Model & KPIs)
- **Phase 2** → Value Streams Layer (Enterprise Flow Architecture)
- **Phase 3** → Workflows Layer (JTBD, Journeys, Workflow Blueprint)
- **Phase 4** → Orchestration Layer (Decision Architecture - who decides what, when)
- **Phase 5** → Business + Workflows Layers (Roles, Org Design, Capabilities)
- **Phase 6** → Agents + Semantic + Data + Infrastructure Layers (Platform Translation)
- **Phase 7** → Business Layer (Change Enablement and Adoption)

**When to use:** Planning discovery work, structuring workshops, designing transformation roadmaps

---

## How They Work Together

```
┌─────────────────────────────────────────────────────────────────┐
│              STRATEGIC FOUNDATION MODEL                         │
│                 (Strategic Foundation)                          │
│                                                                 │
│  Strategic Foundation Mapping:                                 │
│  • VMP (Vision, Mission, Purpose)                              │
│  • Brand Identity & Positioning                                │
│  • Culture & Values                                            │
│  • Strategic Priorities & OKRs                                 │
│  • Business Model Canvas                                       │
└─────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────┐
│                  TARGET OPERATING MODEL                         │
│                  (Operational Structure)                        │
│                                                                 │
│  Four-Level Hierarchy:                                         │
│  • Value Streams     →  Strategic containers                   │
│  • Workflow Groups   →  Coordination units                     │
│  • Workflows         →  Execution specifications               │
│  • Steps             →  Action details                         │
└─────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────┐
│              AGENTIC PLATFORM ARCHITECTURE                      │
│                 (Technology Foundation)                         │
│                                                                 │
│  Four-Layer Technical Stack:                                   │
│  • Agents            →  AI capabilities, orchestration         │
│  • Semantic Layer    →  Knowledge graph, business logic        │
│  • Data              →  Model, integration, governance         │
│  • Infrastructure    →  Cloud, compute, networking             │
└─────────────────────────────────────────────────────────────────┘

                              ⤷
                    All three views informed by
                              ⤴

┌─────────────────────────────────────────────────────────────────┐
│                   DISCOVERY METHODOLOGY                         │
│              (Cross-Cutting Assessment Process)                 │
│                                                                 │
│  Eight Phases (0-7) working across all views and layers:      │
│  Phase 0 → Current State Assessment                            │
│  Phase 1 → Success Model & KPIs                                │
│  Phase 2 → Value Streams Architecture                          │
│  Phase 3 → JTBD, Journeys, Workflows                           │
│  Phase 4 → Decision Architecture                               │
│  Phase 5 → Roles, Org Design, Capabilities                     │
│  Phase 6 → Workflow to Platform Translation                    │
│  Phase 7 → Change Enablement & Adoption                        │
└─────────────────────────────────────────────────────────────────┘
```

## The Architectural Stack

All three IntelligentOS views align to a common 8-layer architectural stack:

```
┌─────────────────────────────────────────────────────────────────┐
│ 1. BUSINESS                                                     │
│    Vision, strategy, KPIs, org design                          │
├─────────────────────────────────────────────────────────────────┤
│ 2. VALUE STREAMS                                                │
│    End-to-end flows delivering business value                  │
├─────────────────────────────────────────────────────────────────┤
│ 3. ORCHESTRATION                                                │
│    Human-agent collaboration, approvals, governance            │
├─────────────────────────────────────────────────────────────────┤
│ 4. WORKFLOWS                                                    │
│    Step-by-step processes with owners and metrics              │
├─────────────────────────────────────────────────────────────────┤
│ 5. AGENTS                                                       │
│    Specialized AI agents performing specific tasks             │
├─────────────────────────────────────────────────────────────────┤
│ 6. SEMANTIC LAYER                                               │
│    Knowledge graph, business logic, intelligence layer         │
├─────────────────────────────────────────────────────────────────┤
│ 7. DATA                                                         │
│    Data model, systems of record, integrations                 │
├─────────────────────────────────────────────────────────────────┤
│ 8. INFRASTRUCTURE                                               │
│    Compute, storage, networking, cloud services                │
└─────────────────────────────────────────────────────────────────┘
```

**View Relationships:**

| From → To | How They Connect | Impact |
|-----------|------------------|--------|
| **Strategic Foundation Model → Target Operating Model** | Strategic priorities define which value streams to optimize | OKRs cascade into workflow-level metrics; Culture assessment informs change approach |
| **Target Operating Model → Agentic Platform Architecture** | Workflow specifications define agent requirements | Decision architecture determines orchestration; Data flows identify semantic layer needs |
| **Agentic Platform Architecture → Target Operating Model** | Agent capabilities enable new workflow designs | Technical constraints shape operational feasibility; Platform maturity determines scope |
| **Discovery Methodology → All Views** | Phases 1-2 populate Strategic Foundation Model; Phases 2-4 populate Target Operating Model; Phase 6 populates Agentic Platform Architecture | Phases 0, 5, 7 span all views with assessment, org design, and change enablement |

**Typical Deliverables:**

| View | Key Artifacts | Format |
|------|---------------|--------|
| **Strategic Foundation Model** | • VMP Statement<br>• OKR Cascade (Company → Function → Team)<br>• Brand Positioning Map<br>• Culture Assessment (Current vs. Desired)<br>• Business Model Canvas | Presentations, Workshop outputs |
| **Target Operating Model** | • Value Stream Maps<br>• Workflow Specifications<br>• RACI Matrices<br>• Process Documentation<br>• SLA & Governance Framework | Operational Schema docs, Process diagrams |
| **Agentic Platform Architecture** | • Technical Architecture Diagram<br>• Agent Specifications<br>• Data Model & Schema<br>• Infrastructure Requirements<br>• Integration Architecture | Technical specs, Architecture docs |
| **Discovery Methodology** | • Current State Assessment<br>• Gap Analysis Report<br>• Transformation Roadmap<br>• Workshop Synthesis<br>• Recommendations Deck | Reports, Presentations, Roadmaps |

---

## Practical Example

Let's say we're working with a client on their permit approval process:

**Using Discovery Methodology:**
- Phase 0: Document their current permit workflow in existing systems
- Phase 3: Map the JTBD and end-to-end journey
- Phase 4: Identify decision points (who approves, when, with what data)
- Phase 6: Define platform requirements for the target system

**Strategic Foundation Model View:**
- Strategic Priorities & OKRs: "Reduce permit cycle time by 30% as a Q2 key result"
- Business Model: "Improved NPS and faster time-to-revenue impact our value delivery"
- Change Readiness: "Team has demonstrated capacity for process transformation"

**Target Operating Model View:**
- Value Stream: Design & Entitlement
- Workflow Group: Permitting
- Workflow: Submit Permit Application
- Steps: Each action with owner, system, dependencies

**Agentic Platform Architecture View:**
- Agents: Document extraction, package assembly, status monitoring
- Semantic Layer: Permit requirements by jurisdiction, approval patterns
- Data: Permit object, jurisdiction rules, submission history
- Infrastructure: Cloud hosting, API gateway, document storage, notification services

---

## Quick Reference

| View | When to Use | Who Sees It | What It Does |
|-----------|-------------|-------------|--------------|
| **Strategic Foundation Model** | Client presentations | Leadership | Frames strategic foundation and readiness |
| **Target Operating Model** | Workshop documentation | Delivery teams | Defines operational structure |
| **Agentic Platform Architecture** | Technical architecture | Platform/AI teams | Specifies technology foundation |
| **Discovery Methodology** | Engagement planning | All teams | Guides assessment across all views |

---

## Cross-Track Alignment

**Our Delivery Model:**
IntelligentOS engagements typically run with three parallel workstreams (tracks) that coordinate to deliver end-to-end transformation:

- **Track 1 (Strategy)** - Leadership alignment on vision, business model, and success metrics
- **Track 2 (Transformation)** - Discovery, process design, and operating model definition  
- **Track 3 (Platform & AI)** - Technical architecture, platform build, and AI implementation

**How Tracks Use the Views:**

- **Track 1 (Strategy)** uses Strategic Foundation Model view to align on vision, feeds Discovery Methodology Phases 1-2
- **Track 2 (Transformation)** uses Discovery Methodology, documents in Target Operating Model structure
- **Track 3 (Platform & AI)** uses Agentic Platform Architecture specifications to build the target platform

**The Complete Flow:**
1. Track 1 defines business strategy and success model (Business layer)
2. Track 2 discovers value streams, workflows, orchestration (Value Streams → Workflows)
3. Track 2 designs agent opportunities and data requirements (Agents → Data)
4. Track 3 builds the platform based on Agentic Platform Architecture specs
5. All tracks measure success using Strategic Foundation Model metrics and OKRs

---

**Version:** 1.0  
**Last Updated:** December 30, 2025  
**Questions?** Contact the Product team
