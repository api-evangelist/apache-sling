# Apache Sling (apache-sling)
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
