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

By Pedro MC Fernandes at ![perconaLogo](../img/docs-design/percona_logo.svg)

![bg](../img/docs-design/cover.svg)

<!--
_class: sep
-->

<style scoped>
  img[alt="perconaLogo"] {
    height: 1.1875em;
    display: inline-block;
    vertical-align: -0.1875em;
  }
</style>

<!--
- Thank you for the opportunity
- Enjoying this design focused event
- Hope to be here again next year
-->

---

### Pedro

- A father and a lover
- Living in greater Lisbon, Portugal
- Hands-on creator inspired by arts
- Experience with 0–1 projects + eCommerce + operations
- All-round designer
- Product designer at Percona
- Generalist contributor in FOSS

![bg right](../img/docs-design/240122105356.png)

<!--
Who's Pedro?

- Lisbon, Portugal
- Experience in various industries
- Also eCommerce
- Designer at Percona
- Contributor in FOSS for a long while
- Support, translation, some design

Alt: Photo of a typical portuguese village street. Very narrow, with cobblestone and white painted houses.
-->

---

![Percona logo](../img/docs-design/percona_logo.svg)

- Freedom to choose ethos
- Provider of open-source database services, support, and software

#### Known for

- Open-source, drop-in replacements for **PostgreSQL/MySQL/MongoDB**
- **Percona Toolkit** command-line tools
- **PMM** database monitoring tools
- Cloud-native database **Operators**

![bg left 100%](../img/docs-design/240123084240.png)

<!--
Where is this happening?

- Born out DB services and consulting
  - For small, growing and large companies
  - Later, open-source software
- To support services, namely...
- Promote freedom to choose

Alt: 3 photos of the Percona team at gatherings and events.
-->

---

## Re-thinking product adoption through documentation design

Why would we?

![bg](../img/docs-design/cover.svg)

<!--
_class: sep
-->

<!--
Read
-->

---

### Motivations

- Databases for everyone
- Promote independence
- More and better contributions
- Optimization of Support
- Don’t break the bank

![bg right](../img/docs-design/240216094956.png)

<!--
Here are some of our motivations:

- Databases for everyone
  - Any technical bg
  - Spark creativity
  - Help learn
- Promote independence
  - Lower the entry barrier
  - Reduce effort + time
- With this
  - Better contributions
    - From anyone to anybody
  - Optimization of Support
    - Focus on bigger problem
    - Societal blockers
    - Medical industry
    - Or other sensitive area
- Don’t break the bank
  - Anyone can get in
  - Regardless of price
  - Grow at their pace
  - Scale when ready

Alt: Photo of a hairdresser saloon with two people facing each other with, probably, payment devices in front of them as if they are about to process payments with their customers.
-->

---

### Databases = Hard<br> Software = Hard<br> Design = Hard

- Technical, complex, costly
- Error 404: Design culture not found
- Rapid software dev. ≠ Rapid UX dev.

![bg right 67%](../img/docs-design/240123164507.png)

<!--
_class: v-align
-->

<style scoped>
  h3 {
    font-size: calc(var(--s3) * 0.95)
  }
</style>

<!--
Databases:
- Technical
- Intimidating
- Specific terminology
- Abstract structures
- Lack user centricity

Percona:
  - Wasn't born user-centric
  - Lack a design culture
  - Focused on technical solutions
  - Working/not working things

Concurrent rapid development
- Software dev + UX dev
- Not possible in unprepared teams
  - Needs deep integration
    - Team
    - Processes
- More time spent

Alt: Image of a meme. It's the Austin Powers movie villains laughing and then overlaid the phrase "We'll ask for estimates and then treat them as dealines"
-->

---

While we develop growth strategies in-product, what else could we do **now**?

![bg](../img/docs-design/balloon.svg)

<!--
class: sep boost
-->

<style scoped>
  section {
    padding: calc(var(--s13) + var(--s8));
  }
</style>

<!--
Read
-->

---

Imagine assembling this…

![bg right:50% 200% hue-rotate:180deg contrast:1.2 brightness:1.2](../img/docs-design/billy.png)

<!--
_class: boost v-align h-align
-->

<!--
Ikea Billy bookshelf with Oxberg doors
-->

---

By only guessing

![bg right saturate:0.7 hue-rotate:20deg](../img/docs-design/240223155705.png)

<!--
_class: boost v-align h-align
-->

<!--
... Where each part fits!

Alt: AI generated image of a realistic depiction of a lot of furniture pieces, ready to be assembled.
-->

---

With documentation, we can promote the adoption and good use of products.

![bg right](../img/docs-design/billy_manual.png)

<!--
_class: boost v-align h-align
-->

<style scoped>
  [data-marpit-advanced-background-container] > figure {
    margin: 2.25rem 3.375rem !important;
    box-shadow: 0 0.1875rem 0.25rem 0 rgba(0,0,0,0.3) !important;
    outline: 1px solid rgba(0,0,0,0.05) !important;
  }
</style>

<!--
- Well designed documentation
- Like IKEA's instructions booklet
- Errors can still happen
- But it improves the experience

Alt: Cover of the Ikea Billy instructions booklet.
-->

---

With databases, even if you’re an expert,<br> you must keep the documentation tab open.

![bg](../img/docs-design/db_dev.png)

<!--
_class: boost h-align
-->

<!--
Development, management and monitoring of databases:
- An entire world
- Connections to make
- Components to upgrade
- Queries to optimize
- Security concerns
- Performance concerns
- And more

Alt: Diagram showing the phases of databases use in software developement: installation, development and upkeeping of the application. Below a screenshot detail of the browser tabs showing the documentation open.
-->

---

## Documentation design rationale

![bg](../img/docs-design/cover.svg)

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

![bg right:40%](../img/docs-design/snap-03.svg)

<!--
_class: v-align padding-null-right
-->

<!--
Problem:
- No strategy in docs
- Not an instrument to achieve goals
- Just existed...

We wanted to change that and ask... Read
-->

---

We want documentation to reach out to more **developers** interested in open-source databases for their applications so that adoption increases through more **installations**, proper **retention**, and evident **ease of use**.

![bg](../img/docs-design/balloon.svg)

<!--
_class: v-align boost h-align
-->

<style scoped>
  section {
    padding: calc(var(--s8) * 2.125);
  }
</style>

<!--
You can go deeper, like with:
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

![bg right:40%](../img/docs-design/snap-01.svg)

<!--
_class: v-align padding-null-right
-->

<!--
Problem:
- Documentation just existed
- Bare minimum effort to exist in parallel
- Had to exist cuz we software house

This is not enough. We asked... Read
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

![bg right 100%](../img/docs-design/ownership.png)

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
  - Problem-solving techniques
  - Propose solutions
  - Explored new tools
    - Posthog

Alt: Diagram of the various departments that were already working on the documentation and the other departments that were invited into it to add expertise.
-->

---

### Boost clarity

Is the content accessible to people?
Does it provide intuitive access to their needs?
Are there untapped opportunities?

![bg right:40%](../img/docs-design/snap-02.svg)

<!--
_class: v-align padding-null-right
-->

<!--
We wanted to ask... Read
-->

---

<!-- ![](../img/docs-design/old.png) -->
<!-- ![](../img/docs-design/old.gif) -->
<video width="858" height="483" autoplay controls mute loop src="../img/docs-design/old.mp4"></video>

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-23252f?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

<!--
_class: v-align h-align
-->

<style scoped>
  p {
    max-width: unset !important;
  }
  img[src*="old"],
  video {
    display: block;
    box-shadow: 0 0.1875rem 0.25rem 0 rgba(0,0,0,0.2), 0 0.375rem 0.5rem 0 rgba(0,0,0,0.1);
    border-radius: 0.125rem;
    outline: 1px solid rgba(0,0,0,0.05);
  }
  img[src*="old"] {
    width: 858px;
    height: auto;
  }
  [href*="squidfunk"] {
    display: block;
    transform: scale(1.125) translateX(0.25rem);
  }
</style>

<!--
In practice, we did:
- Audited websites
- UX analysis
- Identify mistakes
- Detect opportunities

We had 17x websites like this

Built in MkDocs + Material theme
- Flexible
- Practical
- Beautiful theme
- Open-source
- A lot of alternatives exist
  - Docusaurus
  - Vitepress
  - Starlight
  - Markdoc
  - Docsify

Alt: Video showing the old website. The particularity here is that is text heavy and dense.
-->

---

#### Tweaked

- Applied readable fonts
- Added spacing
- Increased chromatic contrast
- Increased reading contrast (headings Vs. running text blocks)
- On-brand re-styling

![bg 101%](../img/docs-design/access.png)

<!--
_class: content-flush-top
-->

<!--
Read

Alt: Screenshots of documentation websites showing the before and after the tweaking.
-->

---

#### Added

- Guidelines and resources to place icons, buttons, dividers, and tabs
- Guidelines to flag critical bits of content and decision-making points

![bg 101%](../img/docs-design/call.png)

<!--
_class: content-flush-top
-->

<!--
Problem:
- Not using the full potential
- Maintainers: not versed in visual arrangement
- UX team open to help

Alt: Screenshots of documentation websites showing the before and after adding functionalities.
-->

---

#### Extended

- New custom components
- Use of more out-of-the-box components

![bg right:60% 101%](../img/docs-design/components.png)

<!--
_class: v-align padding-null-right
-->

<!--
MkDocs:
- Great out of the box

But we wanted more:
- New components
  - Tiny Admonitions
    - When you want more subtle
  - Framed Content
    - When you wish to disrupt
    - Announce
- Shaped out-of-the-box components
  - Feedback module

Alt: Screenshot showing the documentation website page where we added new components.
-->

---

### Unify the experience

Imagine using the documentation.
How does it look? How might we improve it?
Does it feel whole and credible?

![bg right:40%](../img/docs-design/snap-05.svg)

<!--
_class: v-align padding-null-right
-->

<!--
Read
-->

---

![bg](../img/docs-design/site.png)

<!--
_class: h-align
-->

<!--
Problems:
- Documentation left by chance
- Disconnected experience
  - Force user to jump
  - Main site to docs
  - Docs to main site
- Hard maintenance
  - 2 places
  - 2 departments
  - 2 tech stacks
  - 2 UX

Solution:
- Move Docs Home to Docs field
- Easy maintenance
- 1 ownership
- Cohesive experience
  - Same navigation
  - Same styling
- Feeling of whole

Alt: Diagram showing the before and after change we did to unify the experience. The major difference is the creation of a new page called "home", exclusively for the documentation, to help drive users that land anew there.
-->

---

<!-- ![](../img/docs-design/home.png) -->
<!-- ![](../img/docs-design/home.gif) -->
<video width="1120" height="630" autoplay controls mute loop src="../img/docs-design/home-long.mp4"></video>

<!--
_class: v-align h-align
-->

<style scoped>
  p {
    max-width: unset !important;
  }
  img[src*="home"],
  video {
    display: block;
    box-shadow: 0 0.1875rem 0.25rem 0 rgba(0,0,0,0.1), 0 0.375rem 0.5rem 0 rgba(0,0,0,0.2), 0 0.75rem 1rem 0 rgba(0,0,0,0.3);
    border-radius: 0.125rem;
    outline: 1px solid rgba(0,0,0,0.05);
  }
  img[src*="home"] {
    width: 1120px;
    height: auto;
  }
</style>

<!--
- Now you'd be in 1 place only
- Docs URL leads to sub docs
- Boost aesthetic-usability FX
  - Perceived professionalism
  - Perceived functionalism
  - "Things will work"

Alt: Video showing the new version of the documentation website and how it is more clear that every page belongs to the same website.
-->

---

### Improve the user experience

What can we do for people?
How might we anticipate their needs?
How can we make them succeed?

![bg right:40%](../img/docs-design/snap-04.svg)

<!--
_class: v-align padding-null-right
-->

<!--
We asked... Read

Research:
- Talked with customers
- Talked with experts
- Identified problems w/ nav
- Garnered the needs
-->

---

#### Invested in

- Experimenting
- Creating guidelines
- Forming quickstart guides
- Visual prominence for what matters the most

![bg right:60% 101%](../img/docs-design/quickstart.png)

<!--
_class: v-align padding-null-right
-->

<!--
- Experimentation
  - Navigation
  - Top nav added confusion
  - In conjuntion w/ side nav
- To improve side nav, created guidelines
  - Make it slimmer
  - Streamlined
  - Clearer
  - Uncluttered
- Formed narratives to navigate users
  - Guides
  - Quickstart installation
  - Highlight obvious paths
  - Lead to the value

Alt: Screenshot of the documentation website page where we highlighted the quickstart guides with prominent bullet points.
-->

---

We crafted journeys and woven them together so we could guide people into **discovering the value** of our software.

<!--
_class: 
-->

![bg 101%](../img/docs-design/storytelling.png)

<!--
- We used visual cues
- Apply where needed
- Signpost main journeys
- While providing alternatives
- Avoid roadblock feeling in users

Alt: Screenshot of the documentation website pages where we show the use of icons, buttons and other elements to help guide the user.
-->

---

### Overview

- Defined a strategy for the documentation
- Established the co-ownership
- Made it clearer and accessible
- Improved the user experience
- Unified documentation websites’ experience

<br><br>

### To do

- How users are experiencing
- Review outdated content
- Weed out inconsistencies
- Add practical examples/recipes

![bg](../img/docs-design/overview.svg)

<!--
_class: v-align content-flush-top
-->

<style scoped>
  section {
    padding: var(--s8) calc(var(--s13) + var(--s1));
  }
</style>

<!--
Overview:
- Defined a strategy
  - Generate consensus
  - Value of docs for the team goals
- Established the co-ownership
  - Share responsibility
  - Garner expertise
  - Stronger collab
- Made it clear and accessible
  - Readable
  - Visible
  - Tweaked to meet needs
  - Extended to better serve
- Improved the user experience
  - Researched
  - Experimented
  - Created guidelines
  - Highlighted/fixed main journeys
  - Cross-linking between journeys
- Unified documentation websites’ experience
  - Made it feel whole
  - Ease navigation
  - Professional looking

To do:
- How users are experiencing it
  - Is it effective?
  - Do we have more adoption?
- Review outdated content
  - A lot of bloat left
  - Needs thorough review
- Weed out inconsistencies
  - Make 17 instances closer to each other
  - Similar
  - Intuitive
- Add practical examples/recipes
  - People benefit from examples
  - Create more solutions through time
-->

---

## Thank you!

##### Re-thinking product adoption through documentation design

By Pedro MC Fernandes at![perconaLogo](../img/docs-design/percona_logo.svg)

pedro@pmcf.xyz
freenandes@mastodon.social

Rendered with [Marp](https://github.com/marp-team/marpit) and [Lexend](https://github.com/googlefonts/lexend)

![bg](../img/docs-design/cover.svg)

<!--
_class: v-align h-align
-->

<style scoped>
  h3 {
    margin-bottom: 1.25em;
  }
  h5 {
    margin-bottom: 0.3125em;
  }
  img[alt="perconaLogo"] {
    height: 1.125em;
    display: inline-block;
    vertical-align: -0.1875em;
    margin-left: 0.25em;
  }
</style>