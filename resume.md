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

    summary::marker { font-size: 120%; }

    & > *:not(summary) { margin-left: 1rem; }
  }

  h4 { margin: 2.5rem 0 0 0; }
  summary + section > h4 { margin-top: 0; }
  summary + ul { margin-top: 0; }
  section h4 + ul { margin-top: 0.5rem; }
  details + details { border-top: 1px solid silver; }
  li:not(:last-child) { margin-bottom: 1rem; }
  li > ul, li > ol { margin-top: 1rem; }

  h4 > em {
    margin-left: 0.5rem;
    font-weight: normal;
  }

  footer {
      border-top: 1px solid silver;
      margin-top: 2rem;
      font-size: small;
  }

  @page {
    size: A4;
    margin: 0.5cm 0.5cm 1cm 0.5cm;

    @bottom-center {
      content: counter(page) " / " counter(pages);
      font-family: Charter, Times, Serif;
      font-size: 8pt;
    }
  }

  @media print {
    body { font-size: 12pt; }
    summary, h2 { break-after: avoid; }
    section { break-inside: avoid; }
    section h4 + ul { margin-top: 0; }
    summary > h3 { font-size: large; }
    li:not(:last-child) { margin-bottom: 0.5rem; }
    li > ul, li > ol { margin-top: 0.5rem; }
    h4 { margin: 1.5rem 0 0.4rem 0; }
  }
</style>

<header><h1>Avi Flax</h1></header>

<!--

TODO:

* Add somewhere:
  * team building
  * mentoring
  * education
  * professional development
  * Experience with remote/distributed teams

-->

<section>

## Summary

* **Deep expertise** in the Web (especially the back end), APIs, architecture, documentation,
  stream processing, automated testing, and continuous delivery
* **Extensive experience** in the end-to-end software development process: requirements, planning,
  design, implementation, testing, deployment, operations, maintenance
* **Highly engaged:** collaborative, conscientious, curious, diligent, meticulous, mission-oriented
  <!-- add example? --> <!-- show don’t tell? -->
* **Dedicated** to diversity, efficiency, equity, inclusion, justice, kindness, & sustainability

</section>

## Experience

<details><summary><h3>2015–2025</h3></summary>

<section>

#### Omne *<nobr>Chief Software Architect</nobr>* *2024–2025*

* Built and refined the team and its strategy, processes, and culture
* Designed and built an ERP system for the manufacturing market
* Tech: PostgreSQL, C#, Playwright, GitHub Actions, Kafka, Azure Cloud, Terraform, Bicep, Docker

</section>

<section>

#### Trudy *<nobr>Principal Software Engineer</nobr>* *2023–2024*

* Designed, implemented, and maintained:
  * An internal prompt engineering tool for rapidly testing many variations of LLM invocations
  * A prototype SaaS product to enable non-experts to craft, test, and use LLM prompts with multiple
    LLM providers
* Tech: JavaScript, Google Apps Script, Google Workspace APIs, PostgreSQL, HTMX, Python, Django,
  Clojure

</section><section>

#### Latacora *<nobr>Staff Software Engineer</nobr>* *2022–2023*

* Designed, implemented, and maintained:
  * A system that manages access to many AWS accounts via AWS SSO and [Pulumi]
  * A system for deploying multiple tools to many AWS accounts via Pulumi
  * A custom database for crucial business data & CLI tools for integrating the DB with tools such
    as [Fibery] and JIRA
* Tech: Clojure, AWS, Pulumi, GitHub Actions, Docker

</section><section>

#### Modern Energy *<nobr>Senior Director of Technology</nobr>* *2020–2021*

* Helped bootstrap a new Retail Energy Provider (REP) in Texas' ERCOT market
* Automated wholesale energy trades for a few different markets via [APX MarketSuite]
* Helped bootstrap a new HVAC optimization startup by integrating with [InfiSense] and [MelRok]
* Tech: Clojure, Kafka, Airflow, Python, Docker, Pulumi, Google Workspace APIs

</section><section>

#### Funding Circle *<nobr>Principal Software Engineer</nobr>* *2017–2020*

* Leveled-up documentation & knowledge sharing at a 250-person software product org
* Conceived, built, released, and maintained [FC4], an open-source framework for authoring software
  architecture diagrams
* Tech: Clojure, Ruby, Kafka, GitHub Actions, Docker, [C4 Model], [Structurizr]

</section><section>

#### Park Assist *<nobr>Principal Software Architect</nobr>* *2016–2017*

* Rewrote a critical data pipeline using stream processing to reduce latency and improve reliability
* Designed, built, maintained, and operated stream data topologies for high-throughput & low-latency
  data processing
* Leveled-up engineering culture & practices, e.g. introduced infrastructure-as-code, immutable
  infrastructure, and continuous delivery
* Tech: Ruby, JRuby, Kafka, Kafka Streams, SQL Server, Kubernetes, AWS, Terraform, CircleCI,
  Ansible, Datadog

</section>

</details>

<details><summary><h3>2005–2015</h3></summary>

<section>

#### Timehop *2015*

* Rewrote a critical data pipeline using stream processing to reduce latency and improve reliability
* Designed and implemented:
  * A sophisticated integration with Twilio for SMS-based signup
  * A tool for quickly processing billions of records
* Tech: Go (Golang), AWS, Redis, DynamoDB, Kinesis

</section><section>

#### Thinkful *2014*

* Designed and implemented an event-driven system to automate Stripe subscription management
* Tech: Python, Django

</section><section>

#### SFX Entertainment *CTO* *2013–2014*

* Led the design and implementation of an ambitious new-from-the-ground-up streaming music platform
  * With multiple teams: platform, Web, iOS, Android
* Recruited key team members
* Tech: Clojure, REST APIs, AWS

</section><section>

#### Arc90 *2005–2013*

* Wore many hats: developer, architect, tech lead, director, partner
* Worked with teams to design, build, and maintain sophisticated software platforms, including:
  * A Web/SOA insurance platform covering all key aspects of policy origination and management
  * A Web-based search engine and reference platform for engineers
  * A Web API at the heart of a new-from-the-ground-up news distribution platform for Reuters
* Conducted technical audits of clients’ acquisition targets
* Helped manage the business
* Managed client relationships
* Invested much time and effort in recruiting and retaining exceptional team members
* Started practice of regular company-wide code review
* Tech: [ColdFusion], Groovy, Java, Python, [XQuery], [XSLT], [XSD], [Relax NG], [eXist],
  [MarkLogic], MongoDB, SQL Server, AWS

</section>

</details>

<details><summary><h3>1997–2005</h3></summary>

<section>

#### ADP *2001–2004*

* Refactored, enhanced, and maintained a sophisticated application for producing custom financial
  documents for <nobr>on-demand</nobr> printing
* Tech: Microsoft SQL Server, ColdFusion, XSLT, <nobr>XSL-FO</nobr>

</section><section>

#### register.com *2001*

<!-- TODO: compress down to a single bullet -->
* Team lead position for large high-traffic auction site
* Responsibilities included designing, implementing, and maintaining features; reengineering site
  technology and architecture
* Created new internal tools and development procedures
* Tech: ColdFusion

</section><section>

#### RewardsPlus *2000*

* Maintained and enhanced a large-scale online employee benefits enrollment system for diverse
  clients with diverse needs
* Tech: ColdFusion

</section><section>

#### Words In Progress *1998–2000*

* Developed requirements and specifications for high traffic websites directly with clients; crafted
  application architecture and database design
* Maintained one of the earliest major e-commerce Websites for <nobr>T-Mobile</nobr>
* Tech: Microsoft Access, ColdFusion, HomeSite

</section><section>

#### Ideal Computer Strategies *1998*

* Worked with teams of designers, coders, and project managers to concurrently develop and deploy
  client websites with basic dynamic features
* Tech: Microsoft Access, ColdFusion, HomeSite

</section><section>

#### PCC Internet Design *1997–1998*

* Founded and managed a small Web design shop in Baltimore, MD providing full-service Web design
  and development to small businesses in the area
* Tech: Windows Notepad, HTML

</section>

</details>


## Output

<section><details><summary><h3>Speaking</h3></summary>

* [(Architecture) Diagrams as Data] <br> &nbsp;&nbsp; Clojure/conj (2019)
* [Set your data free with model-based architecture diagramming] <br> &nbsp;&nbsp; Write the Docs Portland (2020)
* [Concurrency via Communication — Large and Small] <br> &nbsp;&nbsp; Bay Area Clojure Meetup (2018)
* [Large Nested JSON with Spec: A Comedy of Errors] <br> &nbsp;&nbsp; Bay Area Clojure Meetup (2018)
* [Specifying Other People's Data Structures with Spec] <br> &nbsp;&nbsp; Clojure/nyc (2018)
* [Stream Data Processing with Kinesis and Go at Timehop][timehop-slides] <br> &nbsp;&nbsp; GolangNYC (2015)
* [The impedance mismatch of Web Microframeworks] <br> &nbsp;&nbsp; PyGrunn (2014)

</details></section>


<section><details><summary><h3>Writing</h3></summary>

* [A discussion with my CEO] on the value of code in the LLM era <nobr>(June 2025)</nobr>
* [Some of my favorite resources on software design and development] (2021)
* [Conference Highlights: Write the Docs Portland 2019] (2019)
* A collection of [resources for learning stream processing] (2014–2017)
* [Stack Overflow] (2008–)

</section></details>


<section><details><summary><h3>Code</h3></summary>

* I’m currently working on [a side project]: an app to help community organizers create digital
  calendars for their community programs
* In 2021 I built and launched the Web app <code>ny.vax.help</code> to help people get appointments
  for COVID-19 vaccines in New York State ([repo][vax-help-repo])
* In 2018 I released [FC4], an open-source framework for authoring software architecture diagrams

</section></details>


<section>

## Contact

* 📧 [Email]
* 💬 [Signal]
* 🔗 [LinkedIn]
* 🌎 White Plains, New York, USA

</section>


<footer>

Last modified $updated$ via [$shortsha$](https://github.com/aviflax/resume/commit/$fullsha$)

</footer>



[A discussion with my CEO]: https://gist.github.com/aviflax/80129718328ef064bb299ccd3b5f3a56
[a side project]: https://github.com/aviflax/communitycal
[APX MarketSuite]: https://apx.com/power-scheduling-energy-accounting-services/
[C4 Model]: https://c4model.com
[ColdFusion]: https://en.wikipedia.org/wiki/Adobe_ColdFusion
[Concurrency via Communication — Large and Small]: https://www.youtube.com/watch?v=Vl4KFEJwPPQ
[Conference Highlights: Write the Docs Portland 2019]: https://web.archive.org/web/20220605064728/https://engineering.fundingcircle.com/blog/2019/06/06/write-the-docs-portland-2019/
[Email]: mailto:avi@aviflax.com
[eXist]: https://en.wikipedia.org/wiki/EXist
[FC4]: https://github.com/aviflax/fc4
[Fibery]: https://fibery.io
[InfiSense]: https://www.infisense.com
[Large Nested JSON with Spec: A Comedy of Errors]: https://www.youtube.com/watch?v=5JpcDKooaIQ
[LinkedIn]: https://www.linkedin.com/in/aviflax
[MarkLogic]: https://en.wikipedia.org/wiki/MarkLogic
[MelRok]: https://melrok.com
[Pulumi]: https://www.pulumi.com/
[Set your data free with model-based architecture diagramming]: https://www.youtube.com/watch?v=3i-C7qbRGGQ
[Specifying Other People's Data Structures with Spec]: https://youtu.be/eqfSifXaXnw
[The impedance mismatch of Web Microframeworks]: https://www.youtube.com/watch?v=HGpDHBzErkg
[(Architecture) Diagrams as Data]: https://youtu.be/HmHOYkTVxIg
[Relax NG]: https://en.wikipedia.org/wiki/RELAX_NG
[resources for learning stream processing]: https://gist.github.com/aviflax/7f453a41a06a200a2f5d
[Signal]: https://signal.me/#eu/mm1ogKZ9za21IbeckQ-45ax_5rif1WVN2z5q0Z3Mieh-JmSMtotIbKuir5jc36UY
[Some of my favorite resources on software design and development]: https://gist.github.com/aviflax/7ce52beecd986bb02f8a055c488c88af
[Stack Overflow]: https://stackoverflow.com/users/7012/avi-flax
[Structurizr]: https://structurizr.com
[timehop-slides]: https://speakerdeck.com/aviflax/stream-data-processing-with-kinesis-and-go-at-timehop
[vax-help-repo]: https://github.com/aviflax/vax.help
[XQuery]: https://en.wikipedia.org/wiki/XQuery
[XSD]: https://en.wikipedia.org/wiki/XML_Schema_(W3C)
[XSLT]: https://en.wikipedia.org/wiki/XSLT
