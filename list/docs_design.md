---
marp: true
lang: en
theme: pmcf
author: Pedro Fernandes
title: Re-thinking product adoption through documentation design
description: Improving software adoption by redesigning documentation. A focus on making user guides more intuitive and accessible for 17 diverse open-source products. Tackling users’ frustration and improving technical instructions’ readability by leveraging user experience design practices.
class: v-align
---

<style>
  section.sep {
    padding: var(--s8) calc(var(--s13) * 2) calc(var(--s5) + var(--s1));
  }
</style>

# Re-thinking product adoption through documentation design

By Pedro MC Fernandes at ![perconaLogo](../img/docs_design-percona_logo.svg)

![bg](../img/docs_design-cover.svg)

<!--
_class: sep
-->

<style scoped>
  img[alt="perconaLogo"] {
    height: 0.75rem;
    display: inline-block;
    vertical-align: -4.5px;
  }
</style>

---

### Pedro

- A father and a lover
- Living in greater Lisbon, Portugal
- Hands-on creator inspired by arts
- Experience with 0–1 projects + eCommerce + operations
- All-round designer
- Product designer at Percona
- Generalist contributor in FOSS

![bg right](../img/docs_design-240122105356.png)

<!--
Who's Pedro?
-->

---

![Percona logo](../img/docs_design-percona_logo.svg)

- Freedom to choose ethos
- Provider of open-source database services, support, and software

#### Known for

- Open-source, drop-in replacements for **PostgreSQL/MySQL/MongoDB**
- **Percona Toolkit** command-line tools
- **PMM** database monitoring tools
- Cloud-native database **Operators**

![bg left 100%](../img/docs_design-240123084240.png)

<!--
Where is this happening?

- Born out DB solutions
  - That wouldn't break the bank
  - For small, growing and large companies
  - Later, open-source software
- Freedom to choose
- To support services, namely...
-->

---

## Re-thinking product adoption through documentation design

Why would we?

![bg](../img/docs_design-cover.svg)

<!--
_class: sep
-->

<!--
- Why would we want to shape docs?
- Why improve them?
- Why would we care about docs 1st and software growth later?
-->

---

### Motivations

- Databases for everyone
- Promote independence
- More and better contributions
- Optimization of Support
- Don’t break the bank

![bg right](../img/docs_design-240216094956.png)

<!--
Here are some of our motivations:

- Databases for everyone
  - Any technical background
  - Spark creativity
  - Help learn databases
- Promote independence
  - Lower the entry barrier
  - Reduce effort and time
- More and better contributions
  - Increase discussion
  - Multiply solutions
  - For anyone
- Optimization of Support
  - Focus on bigger problem
  - Societal blockers
- Don’t break the bank
  - Anyone can get in
  - Regardless of price
  - Grow at their pace
  - Scale when ready

Documentation can help.
-->

---

### Databases = Hard<br> Software = Hard<br> Design = Hard

Technical, complex, costly

Error 404: Design culture not found

Rapid software implementation ≠<br> Rapid UX implementation

![bg right 68%](../img/docs_design-240123164507.png)

<!--
_class: v-align
-->

<style scoped>
  h3 {
    font-size: calc(var(--s3) * 0.95)
  }
</style>

<!--
- Technical, complex, costly
  - Intimidating
  - Specific terminology
  - Abstract structures
  - Lack user centricity
  - Increase user base = more research costs
- Error 404, Design culture not found
  - Percona
    - Wasn't born user-centric
    - Focused on technical solutions
    - Working/not working things
- Rapid software implementation ≠ Rapid UX implementation
  - If they're not synchronized
  - Needs deep integration
    - Team
    - Processes
  - More time spent
- Documentation
  - Demystify
  - Reach more people
-->

---

While we create something better in-product, what else could we do [**now**]()?

![bg](../img/docs_design-balloon.svg)

<!--
class: sep boost
-->

---

Imagine assembling this…

![bg right:50% 200% hue-rotate:180deg contrast:1.2 brightness:1.2](../img/docs_design-billy.png)

<!--
_class: boost v-align h-align
-->

<!--
Ikea Billy bookshelf with Oxberg doors.

Anyone had a chance of assembling one of these?

I nailed the back, faced the wrong direction. Wood grain, unpainted from the inside. Had to get some more of those micro nails...
-->

---

By only guessing

![bg right saturate:0.7 hue-rotate:20deg](../img/docs_design-240223155705.png)

<!--
_class: boost v-align h-align
-->

<!--
...Where each part goes.

- Doors one sided
- All either left or right
- Had to unscrew everything
- Door ugly
  - Chipped inside
-->

---

With documentation, we can promote the adoption and good use of products.

![bg right](../img/docs_design-billy_manual.png)

<!--
_class: boost v-align h-align
-->

<style scoped>
  [data-marpit-advanced-background-container] > figure {
    margin: 2.25rem 3.375rem !important;
    box-shadow: 0 0.375em 0.5em 0 rgba(0,0,0,0.3) !important;
  }
</style>

<!--
- Well designed documentation
- Like IKEA's instructions booklet
- Errors can still happen
- Improves the output
-->

---

With databases, even if you’re an expert,<br> you must keep the documentation tab open.

![bg](../img/docs_design-db_dev.png)

<!--
_class: boost h-align
-->

<!--
Database development -> complexity = high.

1. Installation
2. Development, management and monitoring
   1. An entire world
   2. Connections to make
   3. Components to upgrade
   4. Queries to optimize
   5. Security concerns
   6. Performance concerns
   7. And more
3. Application
   1. Maintain
   2. Optimize
-->

---

## Documentation design rationale

![bg](../img/docs_design-cover.svg)

<!--
_class: sep
-->

<!--
- What we did
- What we learned
- What we think
- Open discussion
- Spark ideas
-->

---

### Define a strategy

Who’s reading our documentation?
How can it help them and us achieve our goals?
How do we know if it is helping?

<!--
_class: v-align
-->

<!--
Problem:
- No clear strategy
- Not an instrument to achieve goals.

We wanted to change that and ask...
-->

---

We want documentation to reach out to more [**developers interested in open-source databases**]() for their applications so that adoption increases through [**more installations**](), [**proper retention**](), and [**evident ease of use**]().

![bg](../img/docs_design-balloon.svg)

<!--
_class: v-align boost h-align
-->

<style scoped>
  section {
    padding: calc(var(--s8) * 2.125);
  }
</style>

<!--
- Focus on developers
- Not
  - Database administrators
  - Reliability engineer
  - They continue to be our focus
- But
  - Developers need alternatives
  - Independence
  - Often lack diverse teams

Extra:
- Identify people and audit accessibility
- Set objectives
- Define the action scope
- Establish the ownership
- Set standards
- Define tech stack
- Pick health metrics
- Set feedback streams
- Plan maintenance
-->

---

### Establish co-ownership

Who could help?
Where’s the knowledge?
Who could share responsibilities?

<!--
_class: v-align
-->

<!--
Problem:
- Documentation just existed
- Bare minimum effort
- Had to exist cuz we software house

This is not enough. We asked...
-->

---

#### Kept

- Creation of content
- Management
- Data analysis

#### Added

- Speed
- Visibility
- Openness
- User’s POV
- Horizontal communication
- New methods
- New tools

![bg right 90%](../img/docs_design-ownership.png)

<!--
_class: v-align content-flush-top padding-null-right
-->

<!--
Added:
- Speed + visibility + openness
  - More people seeing
  - Recognizing importance
  - Incite contribution
- We shared all outputs
- Brought user representation
  - Technical Services
  - Account managers
  - Customer success
  - More empirical knowledge
- PMs helped
  - Communicate horizontally
  - Draw attention
  - Move things
  - Garner resources
  - Product POV
- UX team
  - New ways of doing
  - Propose solutions
  - Explored new tools
    - Posthog
-->

---

### Boost clarity

Is the content accessible to people?
Does it provide intuitive access to their needs?
Are there untapped opportunities?

<!--
_class: v-align
-->

<!--
We wanted to ask...

In practice:
- Audited websites
- Analysis from UX POV
- Found mistakes
- Found opportunities
-->

---

![](../img/docs_design-old.gif)

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-23252f?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

<!--
_class: v-align h-align
-->

<style scoped>
  img[src*="old"] {
    width: 30rem;
    box-shadow: 0 0.75em 1em 0 rgba(0,0,0,0.2);
    border-radius: 2px;
  }
  [href*="squidfunk"] {
    display: inline-block;
    transform: scale(1.125) translateX(0.25rem);
  }
</style>

<!--
- Example of what we had
- We had 17x websites like this
- Built in MkDocs + Material theme
  - Flexible
  - Practical
  - Beautiful theme
  - Open-source
  - A lot of alternatives exist
-->

---

#### Tweaked

- Applied readable fonts
- Added spacing
- Increased chromatic contrast
- Increased reading contrast (headings Vs. running text blocks)
- On-brand re-styling

![bg](../img/docs_design-accessibility.png)

<!--
_class: content-flush-top
-->

---

#### Added

- Guidelines and resources to place icons, buttons, dividers, and tabs
- Guidelines to flag critical bits of content and decision-making points

![bg](../img/docs_design-cta.png)

<!--
_class: content-flush-top
-->

<!--
- Not using the full potential
- Maintainers: not versed on visual arrangement
- UX team open to help
-->

---

#### Extended

- New custom components
- Use of more out-of-the-box components

![bg right:60%](../img/docs_design-new_components2.png)

<!--
_class: v-align padding-null-right
-->

<!--
MkDocs — great out of the box, but we wanted more:
- New components
  - Tiny Admonitions
    - When you want more subtle
  - Framed Content
    - When you wish to disrupt
    - Announce
- Use of more
  - Feedback module
-->

---

### Improve the user experience

What can we do for people?
How might we anticipate their needs?
How can we make them succeed?

<!--
_class: v-align
-->

---

#### Invested in

- Understanding people’s needs
- Experimenting
- Creating guidelines
- Forming quickstart guides
- Visual prominence for what matters the most

![bg right:60%](../img/docs_design-quickstart.png)

<!--
_class: v-align padding-null-right
-->

<!--
- Research
  - Talked with
  - Talked with experts
  - Garnered the needs
- Experimentation
  - Navigation
  - Top navigation added unnecessary confusion
    - In our case
    - When overlaid with side navigation
    - 2 different patterns don't work
- To improve side navigation
  - Guidelines
  - Make navigation slimmer
  - Streamlined
  - Clear
  - Uncluttered
- Form narratives
  - Guides
  - Quickstart experience
  - Guide to obvious paths
  - Lead to value of product through docs
- To reinforce storytelling
  - Highlighting steps
-->

---

We crafted journeys and [**woven them together**]() so we could guide people into [**discovering the value**]() of our software.

<!--
_class: 
-->

![bg](../img/docs_design-storytelling.png)

<!--
We used all of these visual cues we have created.

We applied them were it made sense.

The objective was to signpost the most likely journey to the user. While always providing alternative routes.
-->

---

### Unify the experience

Imagine using the documentation.
How does it look? How might we improve it?
Does it feel whole and credible?

<!--
_class: v-align
-->

---

#### Changed things

- Documentation Home Page placement
- Main website → Documentation websites
- Kept link from Main Website Home Page

#### Gained

- Documentation Home feels similar to other documentation sites
- Navigation patterns are similar
- It feels like the same space
- It’s whole and professional

![bg right 100%](../img/docs_design-sitemap.png)

<!--
_class: v-align padding-null-right content-flush-top
-->

<!--
Our elephant in the room: Because we left documentation kind of left by chance, its sitemap was disconnected.

Actually, the homepage for the documentation was in the main website.

It was one of the website pages.

To navigate between 2 products, you had to jump websites. You could notice the huge difference.

We decided to move the actual homepage for the docs to the same area where all other documentation websites were.

We wanted the homepage to feel part of the documentation and not part of the main website. Share the same styling and usability patterns.

This would help make it feel whole.

This would boost the aesthetic-usability effect by making users perceive our documentation as a solid and effective one. This is our hypothesis.
-->

---

### Overview

#### Done

- Defined a strategy for the documentation
- Established the co-ownership
- Made it clear and accessible
- Shaped a better user experience
- Unified the website

#### To do

- Outdated documentation
- Inconsistent content across products
- Lack of practical examples

<!--
_class: v-align content-flush-top
-->

<!--
- Defined a strategy for the documentation
  - Generate consensus
  - Understand the usefulness
- Established the co-ownership
  - Share responsibility
  - Garner expertise
- Made it clear and accessible
  - Readable
  - More visible
  - Tweaked where needed to meet needs
- Shaped a better user experience
  - Researched
  - Experimented
  - Created guidelines
  - Made the obvious journeys clearer
- Unified the experience
-->

---

### Thank you!

#### Re-thinking product adoption<br> through documentation design

By Pedro MC Fernandes at![perconaLogo](../img/docs_design-percona_logo.svg)

pedro@pmcf.xyz
freenandes@mastodon.social

![bg](../img/docs_design-cover.svg)

<!--
_class: v-align h-align
-->

<style scoped>
  h3 {
    margin-bottom: 1.5em;
  }
  h4 {
    margin-bottom: 0.375em;
  }
  img[alt="perconaLogo"] {
    height: 0.75rem;
    display: inline-block;
    vertical-align: -4.5px;
    margin-left: 5px;
  }
</style>
