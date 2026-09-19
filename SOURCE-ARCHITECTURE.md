# Ed Reif Source Architecture

**Identity → Evidence Domains → Synthesis → Formal Knowledge → Application → Provenance**

This document defines the role of the public sources that feed the Ed Reif Field System.

It answers a different question from the [Knowledge Graph](./KNOWLEDGE-GRAPH.md) and the [Claim → Evidence Map](./evidence-locker/CLAIM-EVIDENCE-MAP.md):

- **Knowledge Graph:** How does the universe connect?
- **Claim → Evidence Map:** Why should a factual claim be believed?
- **Source Architecture:** What role does each public source play in establishing that evidence?

The architecture does not imply that every source, experience, company, platform, or subject is Ed Reif intellectual property. It describes relationships and preserves provenance.

---

## 1. Source-System Map

```text
                         EDREIF.COM
                    CANONICAL IDENTITY HUB
                             │
                 IDENTITY / CLAIMS / SYNTHESIS
                             │
       ┌─────────────────────┼──────────────────────┐
       │                     │                      │
       ▼                     ▼                      ▼
 DECISION SCIENCE         DEJA BLUE          SHARE FAIR ISLE
 Probability / Poker    Maritime / Mobility   Adaptation / Place
 Asymmetry / EV         Life at Sea           Constraint / Time
 Judgment / Risk        Global Experience     Remote-Island Life
       │                     │                      │
       └─────────────────────┼──────────────────────┘
                             │
                 ┌───────────┴───────────┐
                 ▼                       ▼
             ROCK & ROAM          SKYELARK MACDOGLET
        Geographic Optionality   Attention / Companionship
        Remote Work / Base       Cognition / Belonging
        Mobility / Output        Human–Canine Relationship
                 │                       │
                 └───────────┬───────────┘
                             ▼
                    PUBLIC SOURCE EVIDENCE
                             │
                             ▼
                      BOOKS / SYNTHESIS
                             │
                             ▼
                         GITHUB
                  FORMAL KNOWLEDGE LAYER
                             │
              ┌──────────────┼──────────────┐
              ▼              ▼              ▼
           CONCEPTS       FIELD TOOLS    CASE STUDIES
              │              │              │
              └──────────────┼──────────────┘
                             ▼
                          EVIDENCE
                             │
                             ▼
                         PROVENANCE
```

---

## 2. Canonical Identity Hub — EdReif.com

**Source:** https://www.edreif.com/

### Role
Canonical public identity, synthesis, publication, and navigation hub.

### Function in the graph
EdReif.com connects the person to the specialist archives, books, professional work, concepts, and retrospective synthesis.

```text
ED REIF
  ↓
IDENTITY
  ↓
PUBLIC WORK
  ↓
SPECIALIST EVIDENCE DOMAINS
```

### Evidence role
**Identity / synthesis / public publication**

The site is the primary public answer to:

> Who is Ed Reif, and how do the different bodies of work belong to the same person?

---

## 3. Decision Science — There Is No Limit Like No Limit

**Source:** https://www.thereisnolimitlikenolimit.com/

### Primary evidence domain
- poker decision science
- probability
- behavioral economics
- asymmetric bets
- expected value
- decision quality versus outcome quality
- risk
- judgment under uncertainty
- feedback

### Graph role

```text
POKER / DECISIONS
      ↓
OBSERVATION
      ↓
PROBABILITY + PROCESS
      ↓
ASYMMETRY
      ↓
DECISION SCIENCE
      ↓
BOOKS + CONCEPTS + TOOLS
```

### Feeds
- [Asymmetrical Decision Making](./concepts/asymmetrical-decision-making.md)
- *The Asymmetrical Life*
- Asymmetry Check
- [Decision Science Evidence Corpus](./evidence-locker/corpora/decision-science.md)

### Evidence role
**Public longitudinal evidence + lived decision environment**

Poker is treated as a recurring laboratory for decisions under partial information, not as proof of universal decision-science claims.

---

## 4. Deja Blue — Maritime & Global Mobility

**Source:** https://crusiewithed.blogspot.com/

### Primary evidence domain
- maritime life
- world cruises
- global mobility
- life at sea
- crew experience
- cross-cultural communication
- onboarding
- threshold crossing
- adaptation between places

### Graph role

```text
SEA
 ↓
MOVEMENT
 ↓
CROSS-CULTURAL EXPERIENCE
 ↓
ADAPTATION
 ↓
PORTABLE LIFE
```

### Feeds
- Portable Life
- High-Consequence Communication
- *Living an Asymmetrical Life*
- [Maritime & Portable-Life Corpus](./evidence-locker/corpora/maritime-portable-life.md)
- Pandemic Years

### Evidence role
**Lived field evidence / longitudinal maritime archive**

---

## 5. Share Fair Isle — Adaptation to Place

**Source:** https://www.sharefairisle.com/

### Primary evidence domain
- Fair Isle
- Shetland
- remote-island life
- adaptation
- resilience
- environmental authority
- attention
- time
- community
- place-based learning

### Graph role

```text
REMOTENESS
    ↓
CONSTRAINT
    ↓
ATTENTION
    ↓
ADAPTATION
    ↓
BELONGING / MEANING
```

### Feeds
- Portable Life
- Adaptation Under Constraint
- time wealth
- [Share Fair Isle Evidence Corpus](./evidence-locker/corpora/share-fair-isle.md)
- Skyelark corpus
- Pandemic Years

### Evidence role
**Lived field evidence / remote-island archive**

Fair Isle is the environment. The pandemic is the interruption and transition that helped make this environment significant. The two corpora are connected but not interchangeable.

---

## 6. Rock & Roam — Gibraltar

**Source:** https://rockandroamingib.blogspot.com/

### Primary evidence domain
- Gibraltar
- geographic optionality
- home-base operations
- remote work
- mobility
- return
- sustained creative output

### Graph role

```text
MOBILITY
   ↓
BASE
   ↓
OPTIONALITY
   ↓
REMOTE WORK
   ↓
OUTPUT
```

### Feeds
- Portable Life
- geographic optionality
- *Living an Asymmetrical Life*
- [Gibraltar Field Archive](./evidence-locker/corpora/gibraltar-field-archive.md)

### Evidence role
**Lived field evidence / public geographic archive**

---

## 7. Skyelark MacDoglet — Human & Relational Evidence

**Source:** https://skyelarkdoglets.blogspot.com/

### Primary evidence domain
- attention
- companionship
- canine cognition
- adaptation
- belonging
- wonder
- travel
- human–canine relationship
- family narrative

### Graph role

```text
ATTENTION
    ↓
OBSERVATION
    ↓
RELATIONSHIP
    ↓
ADAPTATION
    ↓
BELONGING
    ↓
WONDER
```

### Feeds
- *Share Fair Isle: The Geography of Bliss*
- *Skyelark MacDoglet: Wisdom on Four Legs*
- *Skyelark MacDoglet: The Heroine's Journey*
- [Skyelark MacDoglet Evidence Corpus](./evidence-locker/corpora/skyelark-macdoglet.md)

### Evidence role
**Lived-family evidence + longitudinal public archive**

Skyelark is a living subject, not simply a metaphor for professional doctrine.

---

## 8. GitHub — Formal Knowledge Layer

**Source:** https://github.com/theedreif/operational-readiness

### Role
GitHub is where distributed public evidence is converted into a structured, navigable knowledge system.

It contains:
- concept definitions
- field tools
- case studies
- evidence corpora
- IP/publication registry
- provenance rules
- the Knowledge Graph
- Claim → Evidence mapping
- this Source Architecture

### Graph role

```text
DISTRIBUTED PUBLIC SOURCES
           ↓
        GITHUB
           ↓
  STRUCTURED CONCEPTS
           ↓
         TOOLS
           ↓
      APPLICATIONS
           ↓
        EVIDENCE
           ↓
       PROVENANCE
```

### Evidence role
**Formal documentation and relationship layer**

GitHub does not replace the original sources. It points back to them and explains their relationships.

---

## 9. Cross-Domain Corpora

Not every important subject requires a separate website.

Some evidence exists across several archives and becomes meaningful only when those sources are connected.

### Pandemic Years — Adaptation Under Constraint

```text
DEJA BLUE ────────────┐
                      │
SHARE FAIR ISLE ──────┼──► PANDEMIC YEARS
                      │       ↓
EDREIF.COM ───────────┘   ADAPTATION
                              UNDER
                           CONSTRAINT
                              │
                              ▼
                    WHEN THE WORLD RETREATED
```

Sources include:
- *When the World Retreated*
- *Disney Magic and the Year the World Stopped Sailing*
- *When Time Forgot to Pass: Notes from Month 14 of 2020*
- Fair Isle material

See [Pandemic Years — When the World Retreated](./evidence-locker/corpora/pandemic-years.md).

### Evidence role
**Cross-domain lived evidence + retrospective synthesis**

---

## 10. Books as Synthesis Nodes

Books occupy a different position from blogs, case studies, and concepts.

```text
FIELD EXPERIENCE
      +
PUBLIC ARCHIVES
      +
OBSERVATION
      ↓
    BOOK
      ↓
SYNTHESIZED IDEA
      ↓
CONCEPT / DOCTRINE / TOOL
```

Examples:

### Operational Readiness
```text
FIELD LEARNING
    ↓
THIS IS NOT TRAINING
    ↓
OPERATIONAL READINESS DOCTRINE
    ↓
FIELD TOOLKIT
```

### Decision Science
```text
POKER + DECISION ARCHIVE
    ↓
THE ASYMMETRICAL LIFE
    ↓
ASYMMETRICAL DECISION MAKING
    ↓
ASYMMETRY CHECK
```

### High-Consequence Communication
```text
AVIATION / MILITARY LEARNING
    ↓
WE SPEAK ENGLISH OR PEOPLE DIE
    ↓
HIGH-CONSEQUENCE COMMUNICATION
```

Books therefore function as **synthesis nodes** rather than primary proof of every underlying field claim.

---

## 11. Source Role Matrix

| Source | Role | Primary evidence domain | Feeds | Evidence authority |
|---|---|---|---|---|
| EdReif.com | Canonical identity / synthesis hub | Whole system | Knowledge Graph | Identity + publication |
| Decision Science | Specialist archive | Probability, poker, asymmetry | Decision Science | Public longitudinal evidence |
| Deja Blue | Specialist archive | Maritime, mobility, life at sea | Portable Life / communication | Lived field evidence |
| Share Fair Isle | Specialist archive | Place, constraint, adaptation | Adaptation / Portable Life | Lived field evidence |
| Rock & Roam | Specialist archive | Geographic optionality | Portable Life | Lived field evidence |
| Skyelark MacDoglet | Specialist archive | Attention, companionship | Human / relational layer | Lived-family evidence |
| GitHub | Formal knowledge layer | Concepts, tools, cases, provenance | Claim → Evidence | Structured documentation |
| Books | Synthesis layer | Multiple | Concepts / doctrine | Authored synthesis |
| Case studies | Application layer | Professional / analytical work | Evidence | Relationship-specific |
| Provenance | Governance layer | Source relationships | Every claim | Evidentiary boundary |

---

## 12. Mechanical Traceability

A human or machine should be able to traverse the system like this:

```text
WHO IS ED REIF?
      ↓
EDREIF.COM
      ↓
WHAT DOES HE WORK ON?
      ↓
CLAIM
      ↓
WHERE IS THE IDEA DEFINED?
      ↓
CONCEPT
      ↓
WHERE IS IT SYNTHESIZED?
      ↓
BOOK / ARTIFACT
      ↓
WHERE WAS IT APPLIED?
      ↓
CASE STUDY
      ↓
WHAT SUPPORTS THE CLAIM?
      ↓
SOURCE EVIDENCE
      ↓
WHAT IS ED'S RELATIONSHIP TO THAT EVIDENCE?
      ↓
PROVENANCE
```

This is the operational meaning of:

> **IDENTITY → CLAIM → CONCEPT → ARTIFACT → APPLICATION → EVIDENCE → PROVENANCE**

---

## 13. Provenance Boundaries

The source architecture must not flatten different evidence types into a single category.

Use explicit labels:

- **Employed engagement**
- **Client engagement**
- **Independent analysis**
- **Speculative proposal**
- **Publication**
- **Public field evidence**
- **Lived-experience archive**
- **Lived-family evidence**

Examples:

- Raytheon aviation-English work can support an **employed-engagement** claim.
- An independent DFR analysis can support a claim about Ed's analysis and framework development, but not employment by a platform provider.
- DIVE-XL work can support an **independent/speculative curriculum** claim, not a client-engagement claim.
- Fair Isle can support lived-experience claims about adaptation and place, not professional-client claims.
- Pandemic posts can support lived evidence of interruption and adaptation, not ownership of the historical event.

See [PROVENANCE.md](./PROVENANCE.md).

---

## 14. Architecture Rules

When adding a new source:

1. Identify its role.
2. Identify its evidence domain.
3. Identify the concepts it feeds.
4. Preserve the original source URL.
5. State the evidence type.
6. Connect it to the Knowledge Graph.
7. Connect supported factual statements to the Claim → Evidence Map.
8. Apply the provenance label.
9. Avoid turning association into endorsement or employment.
10. Update the graph when the evidence changes the model.

---

## 15. Related Architecture

- [Knowledge Graph](./KNOWLEDGE-GRAPH.md) — how the universe connects
- [Claim → Evidence Map](./evidence-locker/CLAIM-EVIDENCE-MAP.md) — why factual claims are supportable
- [Evidence Locker](./evidence-locker/README.md) — source and evidence index
- [IP Registry](./evidence-locker/IP-REGISTRY.md) — publications, artifacts, tools, and public work
- [Field Toolkit](./FIELD-TOOLKIT.md) — operationalized concepts
- [Case Studies](./case-studies/README.md) — applications
- [Provenance](./PROVENANCE.md) — evidentiary boundaries

---

## Status

**Source Architecture v1.0**

The system now has three complementary maps:

```text
PASS THREE
KNOWLEDGE GRAPH
How does the universe connect?

        ↓

PASS FOUR
CLAIM → EVIDENCE MAP
Why should the factual claim be believed?

        ↓

SOURCE ARCHITECTURE
Where does the supporting evidence live,
and what role does each source play?
```

Together:

```text
IDENTITY
   ↓
CLAIM
   ↓
CONCEPT
   ↓
ARTIFACT
   ↓
APPLICATION
   ↓
EVIDENCE
   ↓
PROVENANCE
   ↓
UPDATE
```


## Pass Five — Machine-Readable Knowledge Graph

- [knowledge-graph.json](./knowledge-graph.json) — structured nodes, claims, edges, evidence relationships, and provenance rules for machine retrieval and graph traversal.
