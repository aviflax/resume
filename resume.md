<style>
  html, body {
      max-width: 8in;
      font-size: 17pt;
      margin-left: 1rem;
  }

  details {
    summary {
      margin-left: 1rem;
      font-size: 1.2rem;
      cursor: pointer;
    }

    summary::marker {
        font-size: 120%;
    }

    & > *:not(summary) {
        margin-left: 2.5rem;
    }
  }

  details + details {
      border-top: 1px solid black;
  }

  li:not(:last-child) {
    margin-bottom: 0.75rem;
  }

  li > ul,
  li > ol {
    margin-top: 0.75rem;
  }

  h4 > em {
      font-weight: normal;
  }
</style>

# Avi Flax

<span id="tagline">Software engineer/architect; experienced generalist</span>


## Summary

* **Deep expertise** in the Web, APIs, stream processing, automated testing, and continuous delivery
* **Deep experience** in all aspects of software development: requirements, planning, design,
  implementation, testing, deployment, operations, maintenance
* **Deeply engaged:** collaborative, conscientious, curious, diligent, driven, meticulous,
  mission-oriented, thoughtful, thorough


## Experience

<details open>
    <summary><h3>2015–2025</h3></summary>

#### Omne *Chief Software Architect, 2024–2025*

* Built and refined the team and its strategy, processes, and culture
* Designed and built a pre-alpha [ERP] system with a focus on manufacturing customers
* Tech: PostgreSQL, C#, Playwright, GitHub Actions, Kafka, Azure Cloud

#### Trudy *Principal Software Engineer, 2023–2024*

* Designed, implemented, and maintained:
  * An internal prompt engineering tool for rapidly testing many variations of LLM invocations
  * A pre-alpha <abbr title="Software as a Service">SaaS</abbr> product to enable non-experts to
    craft, test, and use LLM prompts with multiple LLM providers
* Tech: JavaScript, Google Apps Script, Google Workspace APIs, PostgreSQL, Python, Django, Clojure

#### Latacora *Staff Software Engineer, 2022–2023*

* Designed, implemented, and maintained:
  * A system that manages access to many AWS accounts via AWS SSO and [Pulumi]
  * A system for deploying multiple tools to many AWS accounts via Pulumi
  * A custom database for crucial business data &amp; CLI tools for integrating the DB with tools
    such as [Fibery] and JIRA
* Tech: Clojure, AWS, Pulumi, GitHub Actions

#### Modern Energy *Senior Director of Technology, 2020–2021*

* Helped bootstrap a new Retail Energy Provider (REP) in Texas' ERCOT market
* Automated wholesale energy trades for a few different markets via [APX MarketSuite]
* Helped bootstrap a new HVAC optimization startup by integrating with [InfiSense] and [MelRok]
* Tech: Clojure, Kafka, Airflow, Python, Google Workspace APIs, Pulumi

#### Funding Circle *Principal Software Engineer, 2017–2020*

* 🔜
* 🔜
* Tech: Clojure, Ruby, Kafka, GitHub Actions

#### Park Assist *Principal Software Architect, 2016–2017*

* 🔜
* 🔜
* Tech: Ruby, JRuby, Kafka, SQL Server

</details>

<details>
    <summary><h3>2005–2015</h3></summary>

#### Timehop *2015*

* Refactored a critical and complex system into a loosely-coupled stream-based system using Kinesis
  and Go ([slides])
* Designed and implemented:
  * A sophisticated integration with Twilio for SMS-based signup
  * A tool for quickly processing billions of records

#### Thinkful *2014*

* Designed and implemented an event-driven system to automate Stripe subscription management

#### SFX *2013–2014*

* 🔜
* 🔜
* 🔜

#### Arc90 *2005–2013*

* 🔜
* 🔜
* 🔜

</details>

<details>
    <summary><h3>1997–2005</h3></summary>

#### ADP *2001–2004*

* Refactored, enhanced, and maintained a sophisticated application for producing custom financial
  documents for on-demand printing

#### register.com *2001*

<!-- TODO: compress down to a single bullet -->
* Team lead position for large high-traffic auction site
* Responsibilities included designing, implementing, and maintaining features; reengineering site
  technology and architecture
* Created new internal tools and development procedures

#### RewardsPlus *2000*

* Maintained and enhanced a large-scale online employee benefits enrollment system for diverse
  clients with diverse needs

#### Words In Progress *1998–2000*

* Developed requirements and specifications for high traffic websites directly with clients; crafted
  application architecture and database design

#### Ideal Computer Strategies *1998*

* Worked with teams of designers, coders, and project managers to concurrently develop and deploy
  client websites with basic dynamic features

#### PCC Internet Design *1997–1998*

* Founded and managed a small Web design shop in Baltimore, MD providing full-service Web design
  and development to small businesses in the area

</details>

----

[avi@aviflax.com](mailto:avi@aviflax.com)



[APX MarketSuite]: https://apx.com/power-scheduling-energy-accounting-services/
[ERP]: https://en.wikipedia.org/wiki/Enterprise_resource_planning
[Fibery]: https://fibery.io
[InfiSense]: https://www.infisense.com
[MelRok]: https://melrok.com
[Pulumi]: https://www.pulumi.com/
[slides]: https://speakerdeck.com/aviflax/stream-data-processing-with-kinesis-and-go-at-timehop
