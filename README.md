# Apache Sling (apache-sling)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache Sling is a RESTful web framework built on top of the Java Content Repository (JCR) standard. It maps HTTP requests to content resources using a resource-oriented URL decomposition model and uses scripts or servlets to render responses, supporting multiple scripting languages including HTL, JSP, Groovy, and server-side JavaScript. Apache Sling forms the foundation of Adobe Experience Manager (AEM) and is an Apache Software Foundation project with 300+ modular OSGi bundles.

**URL:** [https://sling.apache.org/](https://sling.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Content Management, Java, JCR, OSGi, REST, Web Framework, Open Source, Adobe Experience Manager

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Sling Resource API
The Sling Resource API provides RESTful access to JCR content repository nodes via HTTP. Every content node is addressable as a URL, supporting GET, POST, PUT, DELETE, and MOVE operations. Content is accessible in multiple formats via selector and extension: .json for structured data, .xml for XML export, .infinity.json for deep tree traversal.

**Human URL:** [https://sling.apache.org/documentation/the-sling-engine/resources.html](https://sling.apache.org/documentation/the-sling-engine/resources.html)

#### Tags:

 - REST, JCR, Content Management, Resources, Java

#### Properties

- [Documentation](https://sling.apache.org/documentation/the-sling-engine/resources.html)
- [Documentation](https://sling.apache.org/documentation/bundles/manipulating-content-the-slingpostservlet-servlets-post.html)

### Apache Sling Scripting API
The Sling Scripting API enables server-side rendering through multiple scripting engines. Scripts are resolved from the content repository based on resource type and selectors, supporting HTL, JSP, Groovy, FreeMarker, Thymeleaf, and server-side JavaScript via Rhino.

**Human URL:** [https://sling.apache.org/documentation/bundles/scripting.html](https://sling.apache.org/documentation/bundles/scripting.html)

#### Tags:

 - Scripting, HTL, JSP, Groovy, Templates, Java

#### Properties

- [Documentation](https://sling.apache.org/documentation/bundles/scripting.html)
- [Documentation](https://sling.apache.org/documentation/bundles/scripting/scripting-htl.html)

### Apache Sling Event API
The Sling Event API provides a job processing and eventing system built on OSGi EventAdmin. It supports distributed job queuing, scheduled job execution, event broadcasting across cluster nodes, and workflow triggering.

**Human URL:** [https://sling.apache.org/documentation/bundles/apache-sling-eventing-and-job-handling.html](https://sling.apache.org/documentation/bundles/apache-sling-eventing-and-job-handling.html)

#### Tags:

 - Events, Jobs, Async, OSGi, Workflow

#### Properties

- [Documentation](https://sling.apache.org/documentation/bundles/apache-sling-eventing-and-job-handling.html)

## Common Properties

- [GitHubOrganization](https://github.com/apache/sling-org-apache-sling-api)
- [GitHubRepository](https://github.com/apache/sling)
- [Documentation](https://sling.apache.org/documentation.html)
- [Portal](https://sling.apache.org/)
- [GettingStarted](https://sling.apache.org/documentation/getting-started.html)
- [Blog](https://sling.apache.org/news.html)
- [Support](https://sling.apache.org/project-information/mailing-lists.html)
- [TermsOfService](https://www.apache.org/licenses/)
- [FAQ](https://cwiki.apache.org/confluence/display/SLING/)
- [Maven Central Packages](https://search.maven.org/search?q=org.apache.sling)

## Features

| Name | Description |
|------|-------------|
| Resource-Oriented REST API | Every JCR node is a REST resource accessible via URL with GET, POST, PUT, DELETE operations. |
| URL Decomposition | Flexible URL decomposition into resource path, selectors, extension, and suffix for content negotiation. |
| SlingPostServlet | Powerful POST servlet for content CRUD operations, supporting create, modify, delete, move, copy, and import. |
| Multi-Language Scripting | Server-side rendering with HTL, JSP, Groovy, FreeMarker, Thymeleaf, and Rhino JavaScript. |
| OSGi Modular Architecture | 300+ modular OSGi bundles with hot-deploy capability and dynamic configuration. |
| Resource Type Hierarchy | Sling Resource Type system enables component inheritance and script resolution. |
| Event and Job Processing | Distributed job queue and event system for asynchronous content processing. |
| Health Check Framework | Extensible health check system for monitoring Sling instance components. |
| Replication and Distribution | Content distribution bundles for replicating content between Sling instances. |

## Use Cases

| Name | Description |
|------|-------------|
| Content Management Systems | Build REST-based CMS solutions with JCR-backed content repositories. |
| Adobe Experience Manager | Foundation framework for AEM digital experience platform implementations. |
| Headless CMS | Serve structured JSON content via Sling's resource API for headless front-end applications. |
| Web Application Framework | Build OSGi-based Java web applications with RESTful resource routing. |
| Digital Asset Management | Manage and serve digital assets stored in JCR with metadata and rendition support. |

## Integrations

| Name | Description |
|------|-------------|
| Adobe Experience Manager | Apache Sling is the foundational framework for Adobe Experience Manager (AEM). |
| Apache Jackrabbit Oak | JCR implementation providing the content repository backend for Sling. |
| Apache Felix | OSGi framework container that hosts Sling bundles and manages the service registry. |
| Apache Karaf | OSGi runtime alternative for deploying Sling-based applications. |
| Maven | Maven plugin (slingstart-maven-plugin) and Maven archetypes for Sling development. |
| Elasticsearch | Search integration for indexing JCR content via Sling's indexing framework. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
