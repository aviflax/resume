---
pagetitle: "Avi Flax: Software { Engineer&nbsp;∪&nbsp;Architect&nbsp;∪&nbsp;Leader }"
---

<style>
  @font-face {
    font-family: charter;
    font-style: normal;
    font-weight: normal;
    font-stretch: normal;
    src: url('fonts/Charter/charter_regular.woff2') format('woff2');
  }
    
  @font-face {
    font-family: charter;
    font-style: italic;
    font-weight: normal;
    font-stretch: normal;
    src: url('fonts/Charter/charter_italic.woff2') format('woff2');
  }
    
  @font-face {
    font-family: charter;
    font-style: normal;
    font-weight: bold;
    font-stretch: normal;
    src: url('fonts/Charter/charter_bold.woff2') format('woff2');
  }
    
  @font-face {
    font-family: charter;
    font-style: italic;
    font-weight: bold;
    font-stretch: normal;
    src: url('fonts/Charter/charter_bold_italic.woff2') format('woff2');
  }

  html, body {
    max-width: 10in;
    font-size: 16pt;
    margin: 0 auto;
    padding: 0 0.5rem;
    font-family: Charter, Times, Serif;
  }

  h2 { margin: 1.5rem 0 0.75rem 0; }

  header {
    h1 { margin-bottom: 0.3em; }
    
    h2#tagline {
      margin-top: 0;
      padding-top: 0;
      font-size: 130%;
      font-weight: normal;
    }
  }

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

  no-br { white-space: nowrap; } /* According to the Mozilla MDN HTML reference, nobr is deprecated */
  h4 { margin: 1.5rem 0 0 0; }
  summary + section > h4 { margin-top: 0; }
  summary + ul { margin-top: 0; }
  section h4 + ul { margin-top: 0.4rem; }
  li:not(:last-child) { margin-bottom: 0.5rem; }
  li > ul, li > ol { margin-top: 1rem; }

  h4 > em {
    margin-left: 0.75rem;
    margin-right: 0.75rem;
    font-weight: normal;
  }

  footer {
    border-top: 1px solid silver;
    margin-top: 2rem;
    font-size: small;
  }

  @page {
    size: A4;
    margin: 0.3cm 0.25cm 0.5cm 0.25cm;

    /* This has little-to-no support in browsers but is supported by Weasyprint. */
    @bottom-center {
      content: counter(page) " / " counter(pages);
      font-family: Charter, Times, Serif;
      font-size: 8pt;
    }
  }

  @media screen {
    details + details { border-top: 1px solid silver; }
    #web-version-section { display: none; }
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
    #download-section { display: none; }
  }
</style>

<header>
  <h1>Avi Flax</h1>
  <h2 id="tagline">Software { Engineer&nbsp;∪&nbsp;Architect&nbsp;∪&nbsp;Leader }</h2>
</header>

<!-- NOTE: you (I) might be tempted to use &nbsp; in certain places. Just FYI, that renders oddly
     in our current PDF-rendering pipeline. (The non-breaking spaces are rendered as extra-wide for
     some annoying reason.) -->

<section>

## Summary

* I’ve **designed, built, maintained, &amp; operated** many successful, sophisticated
  **<no-br>software systems &amp; products,</no-br>** including:
  * An LLM prompt engineering tool
  * A system that manages secure, auditable access to many different AWS accounts
  * An open-source tool for data-driven architecture diagrams
  * A streaming IoT data pipeline
  * A streaming product metrics pipeline
  * Many sophisticated RESTful Web APIs
  * A Web/SOA insurance platform covering all key aspects of <no-br>policy origination &amp; management</no-br>
  * A Web-based search <no-br>engine &amp; reference</no-br> platform for engineers
  * A Web API at the heart of a new-from-the-ground-up API-centric (hybrid) publishing platform
    for a prominent news agency
* I’ve **built, <no-br>managed, &amp; supported</no-br>** many successful, sophisticated
  **<no-br>software engineering</no-br> <no-br>teams &amp; orgs;</no-br>** for example I’ve:
  * Helped <no-br>grow &amp; optimize</no-br> engineering orgs via hiring/firing, mentoring, professional
    development <no-br>programs, &amp; regular</no-br> refactoring
  * Leveled-up engineering culture &amp; practices, e.g. introduced automated testing, code review,
    continuous delivery, infrastructure-as-code, &amp; immutable infrastructure
  * Leveled-up documentation &amp; knowledge sharing at multiple orgs

</section>

## Experience

<details><summary><h3>2015–2025</h3></summary>

<section>

#### **2024–2025** *<nobr>Chief Software Architect</nobr>* Omne

* Built &amp; refined the team &amp; its strategy, processes, &amp; culture
* Designed &amp; built an ERP system for the manufacturing market
* Tech: PostgreSQL, C#, Playwright, GitHub Actions, Kafka, Azure Cloud, Terraform, Bicep, Docker

</section>

<section>

#### **2023–2024** *<nobr>Principal Software Engineer</nobr>* Trudy

* Designed, implemented, &amp; maintained:
  * An internal prompt engineering tool for rapidly testing many variations of LLM invocations
  * A prototype SaaS product to enable non-experts to craft, test, &amp; use LLM prompts with multiple
    LLM providers
* Tech: JavaScript, Google Apps Script, Google Workspace APIs, PostgreSQL, HTMX, Python, Django,
  Clojure

</section><section>

#### **2022–2023** *<nobr>Staff Software Engineer</nobr>* Latacora

* Designed, implemented, &amp; maintained:
  * A system that manages access to many AWS accounts via AWS SSO &amp; [Pulumi]
  * A system for deploying multiple tools to many AWS accounts via Pulumi
  * A custom database for crucial business data &amp; CLI tools for integrating the DB with tools such
    as [Fibery] &amp; JIRA
* Tech: Clojure, AWS, Pulumi, GitHub Actions, Docker

</section><section>

#### **2020–2021** *<nobr>Senior Director of Technology</nobr>* Modern Energy

* Helped bootstrap a new Retail Energy Provider (REP) in Texas' ERCOT market
* Automated wholesale energy trades for a few different markets via [APX MarketSuite]
* Helped bootstrap a new HVAC optimization startup by integrating with [InfiSense] &amp; [MelRok]
* Tech: Clojure, Kafka, Airflow, Python, Docker, Pulumi, Google Workspace APIs

</section><section>

#### **2017–2020** *<nobr>Principal Software Engineer</nobr>* Funding Circle

* Leveled-up documentation &amp; knowledge sharing at a 250-person software product org
* Conceived, built, released, &amp; maintained [FC4], an open-source framework for authoring software
  architecture diagrams
* Tech: Clojure, Ruby, Kafka, GitHub Actions, Docker, [C4 Model], [Structurizr]

</section><section>

#### **2015–2017** *<nobr>Principal Software Architect</nobr>* Park Assist

* Rewrote a critical data pipeline using stream processing to reduce latency &amp; improve reliability
* Designed, built, maintained, &amp; operated stream data topologies for high-throughput & low-latency
  data processing
* Leveled-up engineering culture &amp; practices, e.g. introduced infrastructure-as-code, immutable
  infrastructure, &amp; continuous delivery
* Tech: Ruby, JRuby, Kafka, Kafka Streams, SQL Server, Kubernetes, AWS, Terraform, CircleCI,
  Ansible, Datadog

</section>

</details>

<details><summary><h3>2005–2015</h3></summary>

<section>

#### **2015** *&nbsp;* Timehop

* Rewrote a critical data pipeline using stream processing to reduce latency &amp; improve reliability
* Designed &amp; implemented:
  * A sophisticated integration with Twilio for SMS-based signup
  * A tool for quickly processing billions of records
* Tech: Go (Golang), AWS, Redis, DynamoDB, Kinesis

</section><section>

#### **2014** *&nbsp;* Thinkful

* Designed &amp; implemented an event-driven system to automate Stripe subscription management
* Tech: Python, Django

</section><section>

#### **2013–2014** *CTO* SFX Entertainment

* Led the design &amp; implementation of an ambitious new-from-the-ground-up streaming music platform
  * With multiple teams: platform, Web, iOS, Android
* Recruited key team members
* Tech: Clojure, REST APIs, AWS

</section><section>

#### **2005–2013** *&nbsp;* Arc90

* Wore many hats: developer, architect, tech lead, director, partner
* Worked with teams to design, build, &amp; maintain sophisticated software platforms, including:
  * A Web/SOA insurance platform covering all key aspects of policy origination &amp; management
  * A Web-based search engine &amp; reference platform for engineers
  * A Web API at the heart of a new-from-the-ground-up news distribution platform for Reuters
* Conducted technical audits of clients’ acquisition targets
* Helped manage the business
* Managed client relationships
* Invested much time &amp; effort in recruiting &amp; retaining exceptional team members
* Started practice of regular company-wide code review
* Tech: [ColdFusion], Groovy, Java, Python, [XQuery], [XSLT], [XSD], [Relax NG], [eXist],
  [MarkLogic], MongoDB, SQL Server, AWS

</section>

</details>

<details><summary><h3>1997–2005</h3></summary>

<section>

#### **2001–2004** *&nbsp;* ADP

* Refactored, enhanced, &amp; maintained a sophisticated application for producing custom financial
  documents for <nobr>on-demand</nobr> printing
* Tech: Microsoft SQL Server, ColdFusion, XSLT, <nobr>XSL-FO</nobr>

</section><section>

#### **2001** *&nbsp;* register.com

<!-- TODO: compress down to a single bullet -->
* Team lead position for large high-traffic auction site
* Responsibilities included designing, implementing, &amp; maintaining features; reengineering site
  technology &amp; architecture
* Created new internal tools &amp; development procedures
* Tech: ColdFusion

</section><section>

#### **2000** *&nbsp;* RewardsPlus

* Maintained &amp; enhanced a large-scale online employee benefits enrollment system for diverse
  clients with diverse needs
* Tech: ColdFusion

</section><section>

#### **1998–2000** *&nbsp;* Words In Progress

* Developed requirements &amp; specifications for high traffic websites directly with clients; crafted
  application architecture &amp; database design
* Maintained one of the earliest major e-commerce Websites for <nobr>T-Mobile</nobr>
* Tech: Microsoft Access, ColdFusion, HomeSite

</section><section>

#### **1998** *&nbsp;* Ideal Computer Strategies

* Worked with teams of designers, coders, &amp; project managers to concurrently develop &amp; deploy
  client websites with basic dynamic features
* Tech: Microsoft Access, ColdFusion, HomeSite

</section><section>

#### **1997–1998** *&nbsp;* PCC Internet Design

* Founded &amp; managed a small Web design shop in Baltimore, MD providing full-service Web design
  &amp; development to small businesses in the area
* Tech: Windows Notepad, HTML

</section>

</details>


## Output

<section><details><summary><h3>Speaking</h3></summary>

* [Set your data free with model-based architecture diagramming]
  (Write the Docs, 2020)
* [(Architecture) Diagrams as Data]
  (Clojure/conj, 2019)
* [Concurrency via Communication — Large &amp; Small]
  (Bay Area Clojure, 2018)
* [Large Nested JSON with Spec: A Comedy of Errors]
  (Bay Area Clojure, 2018)
* [Specifying Other People's Data Structures with Spec]
  (Clojure/nyc, 2018)
* [Stream Data Processing with Kinesis &amp; Go at Timehop][timehop-slides]
  (GolangNYC, 2015)
* [The impedance mismatch of Web Microframeworks]
  (PyGrunn, 2014)

</details></section>


<section><details><summary><h3>Writing</h3></summary>

* [A discussion with my CEO] on the value of code in the LLM era <nobr>(June 2025)</nobr>
* [Some of my favorite resources on software design &amp; development] (2021)
* [Conference Highlights: Write the Docs Portland 2019] (2019)
* A collection of [resources for learning stream processing] (2014–2017)
* [Stack Overflow] (2008–)

</section></details>


<section><details><summary><h3>Code</h3></summary>

* I’m currently working on a side project: [a Web app][communitycal-repo] to help community
  organizers create digital calendars for their community programs
* In 2021 I built &amp; launched the Web app <code>ny.vax.help</code> to help people get appointments
  for COVID-19 vaccines in New York State ([repo][vax-help-repo])
* In 2018 I released [FC4], an open-source framework for authoring software architecture diagrams

</section></details>


<section id="download-section">
    
## Download

Please feel free to download [the PDF version] of this document.

</section>


<section id="web-version-section">

## Canonical Version

The canonical version of this document is available at [https://aviflax.dev/resume](https://aviflax.dev/resume)

</section>


<section>

## Contact

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 20px;">
  <div>📧 [Email]</div>
  <div>💬 [Signal]</div>
  <div>🔗 [LinkedIn]</div>
  <div><no-br>🌎 White Plains, NY</no-br></div>
</div>

</section>


<footer>

Last modified $updated$ via [$shortsha$](https://github.com/aviflax/resume/commit/$fullsha$)

</footer>



[A discussion with my CEO]: https://gist.github.com/aviflax/80129718328ef064bb299ccd3b5f3a56
[APX MarketSuite]: https://apx.com/power-scheduling-energy-accounting-services/
[C4 Model]: https://c4model.com
[ColdFusion]: https://en.wikipedia.org/wiki/Adobe_ColdFusion
[communitycal-repo]: https://github.com/aviflax/communitycal
[Concurrency via Communication — Large &amp; Small]: https://www.youtube.com/watch?v=Vl4KFEJwPPQ
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
[Some of my favorite resources on software design &amp; development]: https://gist.github.com/aviflax/7ce52beecd986bb02f8a055c488c88af
[Stack Overflow]: https://stackoverflow.com/users/7012/avi-flax
[Structurizr]: https://structurizr.com
[the PDF version]: ./pdf/Avi Flax’s Resume.pdf
[timehop-slides]: https://speakerdeck.com/aviflax/stream-data-processing-with-kinesis-and-go-at-timehop
[vax-help-repo]: https://github.com/aviflax/vax.help
[XQuery]: https://en.wikipedia.org/wiki/XQuery
[XSD]: https://en.wikipedia.org/wiki/XML_Schema_(W3C)
[XSLT]: https://en.wikipedia.org/wiki/XSLT
