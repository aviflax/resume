---
pagetitle: "Avi Flax: Software engineer/architect; experienced generalist"
---

<style>
  html, body {
      max-width: 8in;
      font-size: 16pt;
      margin: 0 auto;
      padding: 0 0.5rem;
      font-family: Charter, Times, Serif;
  }

  h2 { margin: 2rem 0 0 0; }

  details {
    margin-left: 0.75rem;

    summary {
      margin: 0;
      font-size: 1.2rem;
      cursor: pointer;

      h1, h2, h3, h4, h5, h6 { display: inline-block; }
    }

    summary::marker {
        font-size: 120%;
    }

    & > *:not(summary) {
        margin-left: 1rem;
    }
  }

  details + details {
      border-top: 1px solid silver;
  }
  h4 { margin: 2.5rem 0 0 0; }
  summary + h4 { margin-top: 0; }

  li:not(:last-child) {
    margin-bottom: 1rem;
  }

  li > ul,
  li > ol {
    margin-top: 1rem;
  }

  h4 > em {
      margin-left: 0.5rem;
      font-weight: normal;
  }

  abbr {
      cursor: help;
  }
</style>

<header>

# Avi Flax

<span id="tagline">Software engineer/architect; experienced generalist</span>

</header>

<!--

TODO:

* Add somewhere:
  * team building
  * mentoring
  * education
  * professional development
  * Experience with remote/distributed teams

-->


## Summary

* **Deep expertise** in <abbr title="The World Wide Web!">the Web</abbr> (especially the back end),
  <abbr title="Application Programming Interfaces">APIs</abbr>, architecture, documentation, stream
  processing, automated testing, and continuous delivery
* **Deep experience** in all aspects of software development: requirements, planning, design,
  implementation, testing, deployment, operations, maintenance
* **Deeply engaged:** collaborative, conscientious, curious, diligent, driven, meticulous,
  mission-oriented, rigorous, thoughtful, thorough
* **Dedicated** to <!-- alliteration --> community, compassion, diversity, <!-- egalitarianism, -->
  empathy, equity, impact, inclusion, justice, kindness, solidarity, sustainability, understanding


## Experience

<details><summary><h3>2015–2025</h3></summary>

#### Omne *<nobr>Chief Software Architect</nobr>* *2024–2025*

* Built and refined the team and its strategy, processes, and culture
* Designed and built a pre-alpha <abbr title="Enterprise Resource Planning">ERP</abbr> system with a
  focus on manufacturing customers
* Tech: PostgreSQL, C#, Playwright, GitHub Actions, Kafka, Azure Cloud, Terraform, Bicep

#### Trudy *<nobr>Principal Software Engineer</nobr>* *2023–2024*

* Designed, implemented, and maintained:
  * An internal prompt engineering tool for rapidly testing many variations of LLM invocations
  * A pre-alpha <abbr title="Software as a Service">SaaS</abbr> product to enable non-experts to
    craft, test, and use <abbr title="Large Language Model">LLM</abbr> prompts with multiple LLM
    providers
* Tech: JavaScript, Google Apps Script, Google Workspace APIs, PostgreSQL, HTMX, Python, Django,
  Clojure

#### Latacora *<nobr>Staff Software Engineer</nobr>* *2022–2023*

* Designed, implemented, and maintained:
  * A system that manages access to many AWS accounts via AWS SSO and [Pulumi]
  * A system for deploying multiple tools to many AWS accounts via Pulumi
  * A custom database for crucial business data &amp;
    <abbr title="Command-Line Interface">CLI</abbr> tools for integrating the DB with tools such as
    [Fibery] and JIRA
* Tech: Clojure, AWS, Pulumi, GitHub Actions

#### Modern Energy *<nobr>Senior Director of Technology</nobr>* *2020–2021*

* Helped bootstrap a new Retail Energy Provider (REP) in Texas' ERCOT market
* Automated wholesale energy trades for a few different markets via [APX MarketSuite]
* Helped bootstrap a new HVAC optimization startup by integrating with [InfiSense] and [MelRok]
* Tech: Clojure, Kafka, Airflow, Python, Google Workspace APIs, Pulumi

#### Funding Circle *<nobr>Principal Software Engineer</nobr>* *2017–2020*

* 🔜
* 🔜
* Tech: Clojure, Ruby, Kafka, GitHub Actions

#### Park Assist *<nobr>Principal Software Architect</nobr>* *2016–2017*

* 🔜
* 🔜
* Tech: Ruby, JRuby, Kafka, SQL Server

</details>

<details><summary><h3>2005–2015</h3></summary>

#### Timehop *2015*

* Refactored a critical and complex system into a <nobr>loosely-coupled</nobr> stream-based system
  using Kinesis and Go (Golang) ([slides])
* Designed and implemented:
  * A sophisticated integration with Twilio for SMS-based signup
  * A tool for quickly processing billions of records
* Tech: 🔜

#### Thinkful *2014*

* Designed and implemented an event-driven system to automate Stripe subscription management

#### SFX *2013–2014*

* 🔜
* 🔜
* 🔜
* Tech: 🔜

#### Arc90 *2005–2013*

* 🔜
* 🔜
* 🔜
* Tech: 🔜

</details>

<details><summary><h3>1997–2005</h3></summary>

#### ADP *2001–2004*

* Refactored, enhanced, and maintained a sophisticated application for producing custom financial
  documents for <nobr>on-demand</nobr> printing
* Tech: Microsoft SQL Server, ColdFusion, XSLT, <nobr>XSL-FO</nobr>

#### register.com *2001*

<!-- TODO: compress down to a single bullet -->
* Team lead position for large high-traffic auction site
* Responsibilities included designing, implementing, and maintaining features; reengineering site
  technology and architecture
* Created new internal tools and development procedures
* Tech: ColdFusion

#### RewardsPlus *2000*

* Maintained and enhanced a large-scale online employee benefits enrollment system for diverse
  clients with diverse needs
* Tech: ColdFusion

#### Words In Progress *1998–2000*

* Developed requirements and specifications for high traffic websites directly with clients; crafted
  application architecture and database design
* Maintained one of the earliest major e-commerce Websites for <nobr>T-Mobile</nobr>
* Tech: Microsoft Access, ColdFusion, HomeSite

#### Ideal Computer Strategies *1998*

* Worked with teams of designers, coders, and project managers to concurrently develop and deploy
  client websites with basic dynamic features
* Tech: Microsoft Access, ColdFusion, HomeSite

#### PCC Internet Design *1997–1998*

* Founded and managed a small Web design shop in Baltimore, MD providing full-service Web design
  and development to small businesses in the area
* Tech: Windows Notepad, HTML

</details>

## Output

<details><summary><h3>Speaking</h3></summary>

* [Set your data free with model-based architecture diagramming] ([Write the Docs] 2020)
* [(Architecture) Diagrams as Data] (Clojure/conj 2019)
* [Concurrency via Communication — Large and Small] (Bay Area Clojure Meetup 2018)
* [Large Nested JSON with Spec: A Comedy of Errors] (Bay Area Clojure Meetup 2018)
* [Specifying Other People's Data Structures with Spec: an Experience Report] (Clojure/nyc 2018)
* [The impedance mismatch of Web Microframeworks] (PyGrunn 2014)

</details>


<details><summary><h3>Writing</h3></summary>

* 🔜
* [Stack Overflow]
* 🔜

</details>


<details><summary><h3>Code</h3></summary>

🔜

</details>


## Contact

* [📧 Email]
* [Signal]
* [LinkedIn]
* <abbr title="In Real Life">IRL</abbr>: White Plains, New York, USA



[APX MarketSuite]: https://apx.com/power-scheduling-energy-accounting-services/
[Concurrency via Communication — Large and Small]: https://www.youtube.com/watch?v=Vl4KFEJwPPQ
[📧 Email]: mailto:avi@aviflax.com
[Fibery]: https://fibery.io
[InfiSense]: https://www.infisense.com
[Large Nested JSON with Spec: A Comedy of Errors]: https://www.youtube.com/watch?v=5JpcDKooaIQ
[LinkedIn]: https://www.linkedin.com/in/aviflax
[MelRok]: https://melrok.com
[Pulumi]: https://www.pulumi.com/
[Set your data free with model-based architecture diagramming]: https://www.youtube.com/watch?v=3i-C7qbRGGQ
[Specifying Other People's Data Structures with Spec: an Experience Report]: https://youtu.be/eqfSifXaXnw
[The impedance mismatch of Web Microframeworks]: https://www.youtube.com/watch?v=HGpDHBzErkg
[Write the Docs]: https://www.writethedocs.org/conf/
[(Architecture) Diagrams as Data]: https://youtu.be/HmHOYkTVxIg
[Signal]: https://signal.me/#eu/mm1ogKZ9za21IbeckQ-45ax_5rif1WVN2z5q0Z3Mieh-JmSMtotIbKuir5jc36UY
[slides]: https://speakerdeck.com/aviflax/stream-data-processing-with-kinesis-and-go-at-timehop
[Stack Overflow]: https://stackoverflow.com/users/7012/avi-flax
