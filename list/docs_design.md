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
    vertical-align: -4px;
    margin-left: 4px;
  }
</style>

---

### Pedro

- A father and a lover
- Living in greater Lisbon, Portugal
- Hands-on creator inspired by arts
- Experience with 0–1 projects, eCommerce and operations
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
- Provider of open-source database software, support and services

#### Known for

- Open-source, drop-in replacements for **PostgreSQL/MySQL/MongoDB**
- **Percona Toolkit** command-line tools
- **PMM** database monitoring tools
- Cloud native database **Operators**

![bg left 100%](../img/docs_design-240123084240.png)

<!--
Where is this happening?

- Born out DB solutions
- That wouldn't break the bank
- For small, growing and large companies
- Freedom to choose
- Services came 1st
- Softwares later
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
- In this space
- With these services + open source products
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

- We want databases for everyone
  - Any technical background
  - Spark their creativity
  - Help them learn how to do databases
- Promote independence
  - Lower the entry barrier
  - Get users happy
  - Reduce effort and time spent with databases
- More and better contributions
  - Increase the discussion
  - Multiply solutions
- Optimization of the Support
  - Support focused on bigger problem
  - Urgent problems
  - Societal blockers
- Don’t break the bank
  - Anyone can get in
  - Grow at their pace
  - Scale when ready

Documentation can help.

Easier to consume docs -> soothe the experience = more users.
-->

---

### Databases = Hard<br> Software = Hard<br> Design = Hard

- Databases are technical and complex
- Expanding the user base means increasing research costs
- Error 404, Design culture not found
- Rapid software implementation ≠<br> Rapid UX implementation

![bg right 68%](../img/docs_design-240123164507.png)

<!--
_class: v-align
-->

<!--
- Databases = technical + complex
  - Intimidating
  - Specific terminology
  - Abstract structures
  - Complexity <- user centricity
  - Documentation can
    - Demystify
    - Reach more people
- Increase user base = + research costs
  - More people to know
  - More talk
  - More opinions
  - More synthesis capacity
  - More time spent
  - Research is
    - Crucial for software dev
    - Crucial for user-centricity
    - Crucial for adoption
- Error 404, Design culture not found
  - Percona
    - Wasn't born user-centric
    - Focused on technical solutions
    - Working/not working things
  - A UX team is (again) costly
    - UX outputs does not directly correlate to biz numbers
    - Needs holistic evaluation
    - Needs deep integration
      - Team
      - Processes
    - + Time spent
- Rapid software implementation ≠ Rapid UX implementation
  - If they're not synchronized
  - UX design
    - More iterative by nature
    - Invests in accuracy
    - Shoves in more value

With all of this...

Capacity is limited and growth is a gradual process, not immediate.

- Time is short
- UX teams can't get everywhere at the beginning
- A lot of groundwork is due
-->

---

While we create something better in-product, what else could we do **now**?

![bg](../img/docs_design-balloon.svg)

<!--
class: sep boost
-->

<!--
Thinking...

- Growing software takes time
- Capacity is limited
- A lot of UX debt
- Time is (always) short

What else?
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

Was it hard?

Did you had to go back because you were doing it the wrong way?

I did. I nailed the back, faced the wrong direction. Wood grain, unpainted from the inside.

Had to get some more of those micro nails...

So, imagine assembling this...
-->

---

By only guessing

![bg right saturate:0.7 hue-rotate:20deg](../img/docs_design-240223155705.png)

<!--
_class: boost v-align h-align
-->

<!--
...Where each part goes.

It would be a lot of work, from my lazy handyman POV.

I also made all the doors one sided.

When i was about to install them, i couldn't.

They were all either left or right doors, don't remember.

I had to unscrew everything, leaving the door a little big ugly, chipped from the inside.
-->

---

With documentation, we can promote adoption and good use of products.

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
So, even with well designed documentation, like IKEA's, errors can still happen.

I still think it's a beautifully designed instructions booklet.
-->

---

With databases, even if you’re an expert,<br> you also need to keep the documentation tab open.

![bg](../img/docs_design-db_dev.png)

<!--
_class: boost h-align
-->

<!--
With database development -> complexity = high.

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
Share:

- What we did
- What we learned
- What we think
- Open the discussion
- Spark ideas
-->

---

### A strategic asset

Who’s reading our documentation?
How can it help them, and us achieve the goals?
How do we know is it helping?

<!--
_class: v-align
-->

<!--
We didn't have a clear strategy.

Documentation was not an instrument to achieve goals.

We wanted to change that and ask...
-->

---

We want documentation to reach out more **developers interested in open-source databases** for their applications, so that **adoption increases** through **more installations**, **reasonable retention**, and **clear ease of use**.

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
Focus on developers.

Not database administrators nor reliability engineers.

They continue to be our focus, but we wanted to reach this user base.

We understand that more a more developers need these alternatives and some independence.
-->

---

- Identify people and audit accessibility
- Set objectives
- Define the action scope
- Identify ownership
- Set standards
- Define tech stack
- Pick health metrics
- Set feedback streams
- Plan maintenance

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-23252f?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

![bg right](../img/docs_design-old.gif)

<!--
_class: v-align content-flush-top padding-null-right
-->

<style scoped>
  [data-marpit-advanced-background-container] > figure {
    margin: 5.5rem 1rem !important;
    box-shadow: 0 0.75em 1em 0 rgba(0,0,0,0.3) !important;
    border-radius: 1px !important;
  }
  [href*="squidfunk"] {
    display: inline-block;
    transform: scale(1.125) translateX(0.25rem);
  }
</style>

<!--
Strategy: You can go as detailed or as lightweight as you wish.

We believe the important is an form of agreement of what we are doing.

Sometimes a simpler but mature, sucinct sentence is sufficient to help motivate.

List of topics: This is also a load of work, but shows a bit more of the strategic spectrum.

You could go as far as needed.

On the right hand side, a preview of our old documentation.

We inherited the documentation in MkDocs with the Material theme.

We're pretty happy with it and it's very flexible.

There are tons of alternatives out there.
-->

---

### Co-ownership

Who could help? Where’s the knowledge?
Who could share responsibilities?

<!--
_class: v-align
-->

<!--
Another problem: The documentation just existed for the sake of knowing documentation had to exist.

This is not enough - if - We want to improve.

The result: We only had the absolute minimum to keep documentation alive.
-->

---

#### Kept

- Creation
- Management
- Data analysis

#### Added

- Speed
- Visibility
- Openness
- User’s POV
- Horizontal communication
- New methodologies
- New tools

![bg right 90%](../img/docs_design-ownership.png)

<!--
_class: v-align content-flush-top padding-null-right
-->

<!--
Only: Technical Writers + Marketing

We kept: Read

We added:
- Speed + visibility + openness
  - More people seeing
  - Recognizing the importance
  - Wanting to contribute
  - We shared all outputs with the team
- Brought user representation
  - Technical Services
  - Account managers
  - Customer success
  - And more opinions and empirical knowledge
- PMs helped
  - Draw the attention
  - Move things
  - Get resources
  - Product POV
- UX team
  - New ways of doing
  - Explored new tools
    - Posthog
  - Proposed solutions
-->

---

### Providing clarity

Is the content accessible to people?
Does it provide intuitive access to their needs?
Are there untapped opportunities?

<!--
_class: v-align
-->

<!--
We audited the websites implementation and designs from our UX POV.

We immediately found opportunities to improve.

We wanted to ask...
-->

---

#### Tweaked

- Applied readable fonts
- Added spacing
- More chromatic contrast
- More reading contrast (headings Vs running text blocks)
- On-brand re-styling

![bg](../img/docs_design-accessibility.png)

<!--
_class: content-flush-top
-->

<!--
- Reading: Geometric -> Grotesque
- Kept Geometric for headings
- Boosted contrast on headings
- Added more spacing
- Made hyperlinks for accessible
  - Barely perceivable on the left
-->

---

#### Added

- Guidelines and resources to place icons, buttons, dividers and tabs
- Guidelines to flag key bits of content and decision-making points

![bg](../img/docs_design-cta.png)

<!--
_class: content-flush-top
-->

<!--
We were not using the full potential of MkDocs.

We made sure to provide guidance on how to apply more elements, because the maintainers (tech writers) were not as well versed on visual arrangement.

We were open to help decide.
-->

---

#### Extended

- Created and documented new custom components
  - Tiny Admonitions: when you want to be a little more subtle
  - Framed Content: when you wish to disrupt and announce
- Use out-of-the-box components 
  - Feedback Module
  - And more…

![bg right:60%](../img/docs_design-new_components2.png)

<!--
_class: v-align padding-null-right
-->

<!--
This MkDocs theme is great out of the box, but we wanted more.

Created extensions that made shaped the content to our liking and in a motivation to help users.

Also digged deep to find components that were not in use but would help immensely, like the feedback module.
-->

---

### Helping people

What can we do for them?
How might we anticipate their needs?
How can we make them succeed?

<!--
_class: v-align
-->

---

#### Invested in

- Researching the needs
- Experiments with navigation
- Guidelines for navigation streamlining
- Quickstart guide creation
- Visually prominent guiding steps

![bg right:60%](../img/docs_design-quickstart.png)

<!--
_class: v-align padding-null-right
-->

<!--
We talked with people and experts to understand their needs.

We did experiments a bunch of testing with navigation.

For example, this top navigation (horizontal) + side navigation (vertical) was disapproved.

We found that users felt confused navigating so many sections through 2 distinct patterns. They wouldn't know where is what.

So we decided to generate guidelines that would focus on making the sidebar navigation the best navigation possible.

We also helped create quickstart guides, guiving pointers on how to guide users into installing in a quick and clear way, so they could get to enjoy the product fast.

That is why we also created some visual cues in the quickstart guides (numbered bullet points).
-->

---

We crafted journeys and woven them together, so we could guide people by-their-hand, through key touchpoints, into discovering what they needed.

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

### Unifying the experience

Imagine using the documentation.
How does it look like? How might we improve it?
Does it feel whole and credible?

<!--
_class: v-align
-->

---

#### Changed

- Moved the Documentation Home Page
- Main website → Documentation websites
- Kept link from Main Website Home Page

#### Gained

- Documentation Home Page feels similar to the product documentation
- Navigation patterns are the similar
- Feels like the same space
- Feels whole and professional

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

### Overview of what we did

- Definition of a strategy
- Set up co-ownership
- Provide clarity
- Help people achieve their goals

<!--
_class: v-align content-flush-top
-->

<!--
- Definition of a strategy
  - Generate consensus
- Set up co-ownership
  - Share responsibility
  - Garner expertise
- Provide clarity
  - Readable
  - Accessible
- Help people achieve their goals
  - Understand their needs through research
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
    vertical-align: -4px;
    margin-left: 4px;
  }
</style>

---

### To do

- Final imagery from docs home
- Conclusion

Extras:
- Outdated documentation
- Inconsistent content across products
- Lack of practical examples

<!--
_class: v-align
-->