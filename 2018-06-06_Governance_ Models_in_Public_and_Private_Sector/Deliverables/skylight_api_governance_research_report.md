# API GOVERNANCE IN THE PUBLIC AND PRIVATE SECTORS

This is [Skylight’s](https://skylight.digital/) report for the U.S. Department of Veterans Affairs (VA) microconsulting project, "[Governance Models in Public and Private Sector](https://github.com/department-of-veterans-affairs/VA-Micropurchase-Repo/issues/18)." The VA undertook this project in order to better understand how private- and public-sector organizations approach API governance.

In preparing this report, we drew on nearly a decade’s worth of our own API governance expertise, as well as information obtained through interviews with seven different organizations. For each interview, we followed an interview script (see Appendix A) and took notes. The Government Digital Service (see Appendix B), HMRC (see Appendices C and D), Capital One (see Appendix E), BYU (see Appendix F), and MuleSoft (see Appendix E) all agreed to releasing our notes publicly. The other two organizations (a big bank and a large social networking site) preferred to keep them private.

We structured this report to largely reflect the interview conversations that we held with leaders from around the API governance space. These conversations focused on the following areas:

* Types of organizational roles and models being used to govern APIs

* Approach to software architecture being employed

* Identification and prioritization of APIs

* Development of standards around the delivery of APIs

* Moving APIs into a production environment

* Making APIs available to consumers

Finally, our report outlines considerations for ultimately realizing API governance and the path to get there.

# Types of organizational roles and models being used to govern APIs

Organizations use a number of different roles when it comes to achieving the consistent delivery of APIs at scale. While there are many names for these roles, we’ve distilled them down into the following areas:

* **Leadership &ndash;** Providing leadership to teams.

* **Innovation &ndash;** Innovative uses of APIs.

* **Communication &ndash;** Facilitating communication across all teams and projects.

* **Advisory &ndash;** Acting as an advisor to existing leadership and management.

* **Strategy &ndash;** Helping teams develop, evolve, and realize their strategies.

* **Enablement &ndash;** Helping teams deliver APIs successfully.

* **Architecture &ndash;** Providing a vary of software architecture design expertise.

* **Coaching &ndash;** Coaching existing teams and decision makers across the organization.

Roles in these areas are critical to driving API governance successfully across the organization.

In addition to these roles, organizations are using a number of different structural models to advance their enterprise-wide governance efforts. These include:

* **Labs &ndash;** Creating lab environments in which APIs can be experimented with.

* **Canonical &ndash;** Curating and communicating canonical sources of information.

* **Centralized &ndash;** Packaging all efforts within a single group.

* **Distributed &ndash;** Taking a decentralized approach to who delivers APIs, and sometimes how.

* **Global &ndash;** Treating APIs as a global initiative across the enterprise.

* **Excellence &ndash;** A group or team focused on helping others throughout the organization deliver excellent APIs.

* **Embedded &ndash;** Making sure API expertise is embedded throughout the organization.

We recommend thinking of these models more as principles for approaching governance, as opposed to rigid structures or one best way over another. There’s no clear single role or model that brings success to API efforts at scale across an enterprise. However, there are clear patterns being applied in the early stages of the industry-wide API movement that can be emulated by new players. One such pattern that seems to be emerging is the emphasis on canonical and centralized approaches, coupled with embedded and distributed approaches. The main reason for this is to ensure that the entire enterprise is moving forward in unison, and to leverage existing capacity throughout the organization to deliver on the API governance strategy.

# Approach to software architecture being employed

Governance is all about shaping the way software is architected and designed. There are a number of healthy, and not-so-healthy, patterns across the landscape to consider. In doing so, it’s important to recognize the forces that are operating to influence the direction of software architectures, including in your own enterprise.

## Domain awareness

Software architecture is always a product of its existing environment or domain. These are some of the areas to take into consideration in terms of how your enterprise domain influences your architecture:

* **Resources &ndash;** The types of digital resources that exist today shape how your software architecture is defined and evolves.

* **Schemas &ndash;** Existing schemas define how data are stored, gathered, and syndicated. Even if schemas are abstracted away through other means, it still influences architectural decisions at all levels.

* **Process &ndash;** Existing business processes influence architecture, and can’t always be immediately changed without impacting future architectural decisions.

* **Industry &ndash;** External industry factors are always emerging, thereby shifting how software is crafted. Design, development, and operational factors need to be considered as architecture is refactored to keep up with industry trends.

* **Regulatory &ndash;** In addition to more organic industry influences, there are regulatory-related considerations that factor in.

* **Definitions &ndash;** Access to and availability of machine-readable definitions, schemas, processes, and other guiding structural elements shape software architecture as well.

Domain expertise, awareness, and structure will always fundamentally shape an organization’s software architecture. This makes it imperative not to outsource all of your domain expertise, as many organizations we talk to expressed. Otherwise, you run the risk of not having access to the critical domain knowledge that you need to design and evolve your software architecture on your terms.

## Legacy considerations

You can never escape the past when it comes to making decisions about the future of your software architecture. At the same time, it’s important not to view your legacy decisions and environments in a negative light. Instead, look at them as historical artifacts (for example, embedded domain knowledge and lessons learned) that can inform how you move forward. Here are a handful of legacy considerations we identified through our discussions:

* **Systems &ndash;** Existing systems in operation have significant influence over all current and future architectural decisions, making legacy system considerations a critical factor in making decisions.

* **People &ndash;** Senior staff who operate legacy systems, or who were around when they were developed, possess a significant amount of power when it comes to influencing any new system architecture. You can’t ignore them.

* **Partners &ndash;** External partners who have significant history with the enterprise possess a great deal of voting power when it comes to what software architectures get adopted.

* **Trauma &ndash;** Institutional memories of past outages, breaches, and bad architectural decisions will continue to influence the future, especially when legacy teams possess influence.

Systems, people, partners, and bad decisions made in the past will continue to drive, and often times haunt, each wave of software architectural shifts. These influences can’t be ignored nor abandoned, and must be transformed into positive effects on the next generation of investments in software architecture. Change will be inevitable, and legacy technical and cultural debt needs to be addressed, but not at the cost of repeating the mistakes of the past.

## Contemporary considerations

Regardless of legacy concerns, we all live in the present. During our discussions with organizations regarding the challenges they face, and the current forces shaping their software architecture decisions, we found several recurring themes:

* **Talent available &ndash;** The talent available for designing, developing, and deploying API infrastructure dictates what’s possible at all stages.

* **Contractors &ndash;** Contracted work changes the dynamics of governance &mdash it requires strong processes and a different focus when it comes to execution.

* **Mainstream awareness &ndash;** Continually aligning software architecture practices with mainstream practices helps to evolve the architecture incrementally.  

* **Internal capacity &ndash;** It’s been stated several times that doing APIs at scale across the enterprise wouldn’t be possible without investing in the organization’s own internal capacity over outsourcing to another vendor.

Modern practices shape how you deliver software architecture, govern the evolution of your infrastructure, and find the talent and resources to make it happen. It’s important to understand how the emergence of mainstream practices will affect your software architecture roadmap, how your teams will work with external partners, and how you’ll build-up the capacity necessary to adopt and support effectively.

## Technically defined

The technology you adopt helps define and govern how software architecture is delivered and evolved. There are many evolutionary trends in software architecture that have moved the conversation forward, allowing teams to be more agile, consistent, and efficient in doing what they do. As we studied the architectural approaches of leading API providers across the landscape, we found several instances in which software architecture is influencing future generations and iterations:

* **Vendors &ndash;** Specific vendors have their own guiding principles as to how software architecture gets defined, delivered, and governed. Often, this gives them an outsized role in dictating what happens next.

* **Frameworks &ndash;** Software and programming language frameworks dictate specific patterns, govern how software is delivered, and drive the conversation on how it evolves. They can voice a significant amount of dogma that’ll have a gravity all to its own when it comes to future decisions.

* **Cloud platforms &ndash;** Amazon, Google, and Microsoft have a strong voice in how software architecture is defined in the current climate by providing you with the services and tooling to govern the software lifecycle. Their control over how you define our infrastructure is only going to increase as their market dominance grows.

* **Continuous integration/deployment &ndash;** Continuous integration/deployment services and tooling have established new methods for delivering software, reducing the length of the delivery cycle from yearly to hourly.

* **Source control &ndash;** Services like GitHub, GitLab, and Bitbucket are defining how software is delivered by providing the vehicle for moving code forward, the hooks for governing each commit, and tracking the steps as code is versioned and evolved.

These areas of software architecture increasingly govern how you design, develop, deploy, and manage your infrastructure. They provide the platform needed to manage and orchestrate increasingly complex technology infrastructures. The decisions you make about technology now will continue to influence your decisions for years to come.

## Business defined

When it comes to delivering software architecture, not everything is governed by the technical components, and much of what gets delivered is defined by the business side of the equation. The amount of investment by a business into IT, as well as several other groups, determine what gets done. In general, the following business elements govern software architecture:

* **Budgets &ndash;** The amount of money allocated for a team affects work on defining, deploying, managing, and iterating on software architecture.

* **Investors &ndash;** Many groups are influenced and even restricted by outside investors. This influence can determine what software architectures are prioritized, and dictate decisions around what’s worked on.

* **Partners &ndash;** External partners with a strong influence can shape decisions and play a big role in governance.

* **Public image &ndash;** Often times decisions that go into software architecture will be driven by public-image concerns.

* **Culture &ndash;** Organizational culture can drive decisions in significant ways, and can be more challenging to change than the underlying technology in many cases.

The governance of software architecture has to be in alignment with the business objectives of an enterprise. Many groups choose to begin their API journeys based upon trends, or the desire of a small group, and encounter significant friction when trying to align with wider enterprise business objectives. Groups that address business considerations early and often do a much better job of reducing friction when it comes to software architecture governance decisions.

## Observability

Almost all of our discussions around software infrastructure governance have included several mentions of the importance of observability. Software designed, delivered, and supported in isolation either fails or is destined to become the next generation of technical debt. There were several areas of emphasis when it came to ensuring that an API-driven infrastructure considers observability from day one and continues to operate in a way that everyone involved can see what’s happening.

* **Openness &ndash;** Groups who operate out in the open, share their progress actively with other teams, and encourage a transparent process find higher levels of success, adoption, and consistency across their architectural efforts.

* **Collaborative &ndash;** While identified as sometimes being slower than traditional, more isolated efforts, teams who encouraged cross-team collaboration saw that their architectural decisions were sounder, more stable, and received greater acceptance.

* **Open source &ndash;** Following open-source-software-development practices and working with existing open-source solutions helps ensure that enterprise software architecture lasts longer, has more support, and follows more common standards compared to proprietary approaches.

* **Public &ndash;** When it makes sense from a privacy and security standpoint, being public by default helps to ensure that project teams behave differently and hold themselves more accountable. Being public also helps to attract external talent, encourage contributions from domain experts, and garner positive public opinion along the way.

Enterprise organizations that push for observability by default find that teams tend to work better together and have a more open attitude. To focus on observability means attracting the right personalities, encouraging regular communication, and thinking externally by default, not as something that happens down the road. These actions bring much-needed transparency into processes that can often be very complex and abstract, and push things to speak to a wider audience beyond developer and IT groups.

## Shared process

Having a shared process that can be communicated across internal and external stakeholders (for example, technical teams, business groups, and third-party developers) who can follow and participate in is now a regular part of newer API-centric, software-delivery lifecycles. Sharing core elements helps ensure that the process for defining, designing, delivering, and evolving software architecture is shared by all.

* **Contract &ndash;** Crafting, maintaining, and consistently applying a machine-readable contract, using common formats such as YAML, is a common approach to ensuring commonality across all architectural projects, as it allows defining individual solutions as independent business services.

* **Pipeline &ndash;** Extending the above machine-readable service contracts with YAML-defined pipeline definitions ensures that all software is delivered in a consistent, reproducible manner across many disparate teams.

* **Versioning &ndash;** Establishing a common approach to versioning code, definitions, and other artifacts provides a common semantic approach to governing how architecture is evolved in a shared manner that everyone can follow.

Historically the software development and operation lifecycle is owned by IT and specifically development groups. Modern approaches to delivering software at scale is a shared process, requiring collaboration among multiple internal and external stakeholders. This collaboration requires bringing software architecture out of the shadows and conducting it on the open web, making it more inclusive amongst all stakeholders. That open collaborative process must, of course, respect privacy and security along the way.

# Identification and prioritization APIs

Once the architectural foundations have been laid, there are many ways in which large enterprises begin identifying potential APIs that should be designed, deployed, and evolved to support the many applications that’ll be depending on the underlying platform architecture. Depending on the organization and its priorities, the reasons for how new APIs arise vary, leading to different lifecycles and resulting services being delivered across internal and external consumers.

During our research, we identified that there’s no single approach to identifying which APIs should be delivered. However, we did uncover a variety of approaches in use across the landscape that helps us to understand why you create APIs.

## Existing realities

Our existing realities drive the need for APIs, and reflect where you should be looking to provide new services to users. While some APIs may be entirely new solutions, it’s most likely that these APIs will be born out of the existing digital solutions that are in place today, such as:

* **Database &ndash;** Existing databases are the number one place groups are identifying potential resources for API deployment. By exposing historically accumulated digital assets using the web, and making them available for use in new applications, databases are a major source of new data products.

* **Website &ndash;** Existing websites reflect the last 20 years of digital evolution; they represent the digital resources accumulated and identified as being important to share with users. HTML representations of your digital assets are always the first step in the API deployment process, followed by understanding what to make available as JSON or other more sophisticated representations.

* **Integrations &ndash;** Existing software integrations, such as system-to-system integrations, represent a rich area for understanding how digital resources are delivered, accessed, and made available throughout existing the ecosystem. These integrations are important part of the overall landscape in terms of identifying what should be turned into APIs.

* **Applications &ndash;** Existing web, mobile, desktop, and other applications will have a variety of backend system connectivity solutions. And they may represent more bespoke approaches to doing APIs, which are off-the-radar when it comes to governance. Such approaches provide another rich area for mapping out the connections between common applications and understanding how they’re consumed by internal and external parties.

* **Services &ndash;** APIs aren’t a new idea, which means they already exist in a variety of formats. Legacy web services, RPC, FTP, and other API and messaging formats should be mapped out and included as part of the potential API evolutionary landscape. Taking existing services, and evolving them in a consistent manner with all other API-driven services, allows you to leverage web technologies to consistently deliver and manage digital resources.

* **Spreadsheets &ndash;** Most business still takes place in spreadsheets. These portable data stores are emailed, shared, and spread around the enterprise, and represent a rich source of information when it comes to understanding which resources should be published as APIs.

You can’t govern what isn’t mapped out and known. It becomes increasingly difficult to govern software infrastructure that exists across many open and proprietary formats, and delivered as custom one-off solutions. Governance begins with knowing the landscape, and the greatest impediment to functional governance across organizations are the unknowns. Therefore, it’s critical to understand what solutions are already in place and how existing architectural approaches fit into the big picture. Otherwise, it’s impossible to make the enterprise architecture operate in concert.

## Public presence

Another reason for having an open, public approach to selecting, delivering, and operating software infrastructure is that it establishes a public presence across web properties, social networks, and other platforms where enterprise organizations can build a community around. There are a number of ways to identify potential new API resources by simply being public, engaging with the community, and establishing API delivery lifecycles that involve having a public presence.

* **User requests &ndash;** Actively soliciting web, mobile, and developer feedback, both internally and externally, is a great way to learn about potentially new API resource opportunities. Organizations can leverage existing users as a source of insight when it comes to what services would make applications better, demonstrating the importance of investing in an API-literate user base.

* **Partner requests &ndash;** Actively working with partners to conduct regular meetings regarding digital assets and transformation, as well as seeking feedback on what types of services would improve upon existing solutions, strengthens partner relations. Investing in these relationships allows you to use them as a way to evolve the API roadmap and increase their dependency (in a positive way) on your enterprise resources.

* **Public feedback &ndash;** Engaging with the public via websites, social networks, forums, and events can reveal new opportunities to deliver new API resources. This engagement enables tapping into public awareness around specific topics and within particular domains, as well as discovering ideas for new APIs.

* **Media coverage &ndash;** Keeping up with popular tech blogs, mainstream media, and other outlets helps you to understand what trends and opportunities are emerging around the delivery of API services.

* **Feedback loops &ndash;** Cultivating trusted feedback loops with existing users, social networks, and private-messaging platforms allows you to tap into the collective knowledge and domain expertise of others.

* **Negative consequences &ndash;** One significant issue with having a public presence is that it doesn’t always yield positive results, as not everyone has your best interests in mind. There are serious privacy, security, and safety concerns when operating public APIs that needed to be considered and addressed.

It isn’t easy soliciting feedback from the general public when it comes to determining the direction of your API platform roadmap. However, with some investment, curation, and cultivation, you can establish more reliable insights regarding the direction to take. The API community across the public and private sectors has grown significantly over the last decade. This community can serve as a wealth of talent and knowledge that can be tapped into

## Improvements

In terms of prioritizing APIs, investing in areas that drive enterprise-wide improvements emerged as a common theme during our research. Some of these improvement areas focused on:

* **Optimization &ndash;** Optimizing the consistency of how teams deliver APIs. This includes pushing for common design, delivery, and management patterns and standards.

* **Reusability &ndash;** Increasing the degree to which services can be reused across a variety of applications and delivery channels.

* **Acceleration &ndash;** Investing in governance in order to accelerate improvements in how services are delivered across the enterprise.

* **Flexibility &ndash;** Increasing the flexibility of how applications operate in order to improve the way teams work together and deliver across the enterprise.

It’s important to come up with your criteria for deciding which APIs to prioritize. However, you may want to consider prioritizing APIs which drive one or more improvements in the areas above..

## Challenges

The API journey is always full of challenges, and the risks these challenges represent should be identified and incorporated into your prioritization criteria. While some challenges can be minimized and overcome, others can cause unnecessary friction throughout the API journey.

* **Education &ndash;** Some API efforts require a significant degree of education. It’s important to understand how much investment in that area will be required.

* **Maturity &ndash;** Envisioning what maturity looks like for a particular service over time is an important consideration. It takes considerable effort to plan, deliver, and operate a "mature" service.

* **Isolation &ndash;** It’s important to identify resources that are being developed, maintained, and operated in isolation. And to figure out how to bring them into the fold. That reality affects the cost of future development efforts, and shouldn’t be ignored.

* **Management &ndash;** Management should be included in discussions around which resources should be developed into APIs. Management should take a leadership role in all conversations involving the targeting, evolution, and even deprecation of API services. This ensures that the prioritization of API development is always on the radar of management.

* **Consistency &ndash;** Although consistency is the goal, it may be an elusive, non-stop chase to actually realize consistency across teams. You want to strive for perfection while acknowledging that sometimes it’s okay for services to be just "good enough."

* **Reusability &ndash;** Similar to consistency, reusability is an obvious goal and should be worked towards, but it’ll also be elusive and not always reliably achieved over time. There might still be redundancy for some services, and overlapping aspects of delivering services, while in other areas reusability will be achievable.

* **Build it and they will come &ndash;** There’s been a significant amount of reflection regarding targeting, developing, and publishing APIs that weren’t needed based upon an "if you build it, they will come" mentality &mdash where often nobody came and the work was in vain.

Challenges are a fact of life in the delivery of software and evolving complex systems using APIs. Identifying challenges should be a natural part of the process for targeting resources for delivery as APIs. Challenges can increase friction when delivering services, and should be carefully evaluated before tackling the development of new services. It’s easy to identify the potential of new APIs, but it takes a more seasoned eye to factor in the potential challenges.

# Development of standards around the delivery of APIs

Realizing and delivering upon governance at scale will require investment in standardizing data models, as well as the incorporation of existing patterns and standards throughout the API delivery lifecycle. Many enterprise API development groups are streamlining and standardization the delivery of APIs through the adoption of particular standards. Such standardization makes it easier for application developers to adopt and integrate APIs.

While the adoption of common data models, interfaces, media types, and web standards help contribute to the delivery of consistent APIs at scale, it can also prove to be a challenge for some teams, and even by viewed as a threat by others. There are a number of ways in which teams are pushing for standardization across their operations in order to achieve greater consistent, reuse, and results. In fact, this is one of the strengths of web APIs, in that they employ web standards to achieve wider adoption and the delivery of valuable resources at web scale.

## Core definitions

A suite of approaches have emerged in the last decade for designing, developing, evolving, and applying common API patterns across the API lifecycle. These standardized approaches use common machine-readable specifications and widely-used patterns. They’re also fueling considerable growth in the API sector by serving mobile applications, as well as other emerging channels such as voice, bot automation, and the Internet of Things. They also help enterprises more effectively organize how services are delivered at scale.

* **Resource-defined &ndash;** RESTful design patterns provide a simple approach to turning digital assets into a reusable stack of resources, which can be discovered and consumed across many channels.

* **Schema-driven &ndash;** JSON Schema is being used to take a variety of schemas and standardize them for use in RESTful API resource delivery. JSON Schema provides a reusable blueprint that can be used across the request and response model for all APIs.

* **Domain-driven &ndash;** The business domain is being used to guide the identification, development, evolution, and standardization of a variety of API definitions. Focusing on the business domain helps to establish separate areas of concern. This separation enables the decoupling of enterprise resources used across systems, which makes it easier to make these resources work together in unison.

* **Legacy abstraction &ndash;** Continued movements to decouple, redefine, and evolve legacy systems are pushing forward the identification of common patterns and transformation into newer web-based APIs. Distilling the wisdom contained within legacy databases and system interfaces helps to drive the development of common standards.

* **Vocabularies &ndash;** API development teams are not only establishing common vocabularies based upon the standardized language already in use, but they’re also taking the local dialect that’s used in bespoke systems and translating it into a common lexicon. This provides a standard language that can be used across the enterprise to talk about resources and services.

* **Discovery &ndash;** Many groups expressed difficulty around the adoption of standards because other teams couldn’t find existing schemas, definitions, or other existing standards. This underscores the importance of actively maintaining and communicating a comprehensive, discoverable catalog of core definitions across the enterprise. Such a catalog serves as a single or distributed location to which everyone can find and publish their common definitions.

Achieving a common language requires mapping out the known landscape across the enterprise and turning it into common patterns that can be reused across the design, development, and operation of the next generation of APIs. You must distill the linguistic and schematic aspects of your enterprise so that they become the building blocks of your API program.

## Doing business on the web

APIs are built on, and benefit from, over 20 years of web history and evolution. There are a number of elements to consider when working to identify and define common standards for use across the governance of any API program. While the API strategy should be rooted in definitions derived from the core of the enterprise, it should also be embracing the web and employing common patterns that make the web work as the foundation for delivering APIs.

* **Web standards &ndash;** The web is the foundation for the delivery of APIs. Most APIs will use HTTP as a transport, and be employing URLs, HTTP verbs, headers, parameters, and other common web standards. Web standards should be part of any governance strategy to help establish common patterns and definitions for use across operations.

* **Media types &ndash;** Media types are a fundamental part of the web, and help establish message formats that’ll be widely recognized outside the enterprise, encouraging the reuse and adoption of APIs that employ common media types. Allowing consumers to negotiate the format that makes the most sense for their team, and the types of applications they’re looking to develop.

* **Industry schema &ndash;** Industry-level schemas are emerging and maturing for use across API operations. Specifications like FHIR, PSD2, and other schemas, along with API design patterns, are evolving to help support industry-focused API operations, while encouraging reuse and interoperability across disparate groups.

* **Open source &ndash;** The usage of open-source software, tooling, specifications, and processes are helping to deliver on the API vision across the enterprise. Web APIs reflect the open-source ethos, and plays well with the delivery of web APIs. Encouraging reuse, adoption, and observability is necessary to help APIs succeed.

APIs are all about doing business on the web. The web provides the platform in which any API program will operate. When it comes to defining schemas, standards, and common patterns for use across API operations, the web is always the beginning of the conversation. While enterprise-defined patterns will always be front and center, the standards used to operate the web should always trump localized definitions, and be given priority whenever possible. Don’t reinvent the wheel when it comes to the web &mdash always reuse and implement what’s already known.

## Under the influence

When learning about new standards and considering which standards to adopt, it can be easy to find yourself under the influence of specific vendors, competing standards, programming communities, and other factors. Careful evaluation of standards is important, and an awareness of what some of the common elements are that may shift your opinions one way or another, or even obfuscate what’s real and prevent you from achieving objectives.

* **Caught in trends &ndash;** Avoid getting caught up in the trend cycles that can often make it difficult to understand the hype around specific specifications. Do your research, understand best practices and adoption levels, and make the sensible decisions around the impact to your own efforts.

* **External entities &ndash;** While engaging with external entities, understand what their priorities are when it comes to standards and specifications. Understanding the alignment between your enterprise’s objectives and the external entity’s motivations will help to ensure your efforts are being pushed in the right direction.

* **Internal demands &ndash;** Similar to external entities, understand what the internal teams’ priorities are and don’t always assume internal requests will have the overall enterprise objectives in mind.

* **Feedback loops &ndash;** Ensure that feedback looks are diverse in order to provide a wealth of opinions around what types of standards and specifications should be supported.

* **Organic change &ndash;** Be wary of vendor-induced standards adoption over a more organic, internal approach to standards adoption, the latter of which may better suit your needs.

There are plenty of currents to get caught up in when it comes to identifying, defining, and evolving standards. Not all will bear fruit, or realize the type of adoption needed to be successful. Establishing a balanced view of the landscape across internal and external actors will help ensure that you understand which API specifications, standards, and definitions will help move your enterprise forward.

## Taking the lead

While there are a number of ready-to-use standards available for the web, and organically grown out of the API community, these standards won’t always find their way into the enterprise. Leading organizations demonstrate that it takes a structured effort to define, disseminate, educate, and evolve standards across large organizations, with a number of proven tactics:

* **Workshops &ndash;** Organize, conduct, and grow the number of workshops held to introduce individuals across many teams to a variety of common standards and specifications.

* **Discussions &ndash;** Formalize discussions around emerging standards, and those that are in use, to help push forward awareness and adoption of standardized approaches across groups.

* **Collaboration &ndash;** Push teams to work together when it comes to sharing the standards in use, showcasing the investment they’ve made, and working together to understand the tooling, services, and standards being used.

* **Event storming &ndash;** Use event storming, which is a rapid, lightweight group modeling technique to help accelerate the identification, evolution, and adoption of standards that meet specific team needs.

* **Influencers &ndash;** Identify, invest in, and cultivate influencers who exist within current groups, and encourage them to evangelize and help spread the good word about standards across the enterprise.

* **Ask questions &ndash;** Always be asking questions about the standards, or lack of standards in use across the enterprise, pushing the conversation forward at all times when it comes to standards.

* **Challenge assumptions &ndash;** Make sure teams don’t get complacent, that the status quo is always being challenged, and that the internal domain rises to a higher level of standardization whenever possible.

It takes standards bodies to move forward common standards at the web and industry levels, and it takes the same approach to push forward the adoption and usage of standards within the enterprise. Leading enterprise organizations are able to quantify, measure, and evolve the infrastructure in a more organized way through the adoption of common schemas, specifications, and standards. This provides a common vocabulary for all teams to use when designing, deploying, and managing services that can be used consistently within, across, and outside of the enterprise.

# Moving APIs into a production environment

We researched how teams moving APIs from idea to production. The processes that were described involve documenting the lifecycle of a service, and executing on that lifecycle and monitoring progress throughout.

## Well-defined

To be able to deliver APIs at scale in a consistent way, teams are relying on a well-honed, well-defined lifecycle that’s been defined and continually refined. This lifecycle forces structure and rigor throughout the evolution of all services, puts governance in front of teams, and encourages them to execute in a consistent way in order to make an API a production reality. It’s important to focus on a handful of structured formats for imposing governance at the deployment levels:

* **Contract &ndash;** Require that all services begin with a machine-readable OpenAPI contract that defines the entire surface area of the API and its schema. Leverage the contract as the central truth for what the service will deliver, and how governance will be measured throughout the lifecycle of the service.

* **Process &ndash;** Provide a well-defined process for all developers laying out how any service moves from idea to production, with as much detail regarding each step along the way. Help all developers understand what they will face as they work to move their services forward in the enterprise.

* **Scorecard &ndash;** Have a machine-readable checklist and scorecard, with tooling to help each developer fork or establish an instance for their service. Provide a checklist of everything they need to consider, allowing them to check-off what has been done and what’s left, and provide a definition that can be used to define and report upon governance along the way.

* **Cycles &ndash;** Provide a variety of cycles that every service will need to go to before they will be production worthy, forcing developers to iterate upon their services, harden and mature them before they’ll be considered ready for production.

* **Reviews &ndash;** Require all services go through a series of lifecycle reviews by other teams, push service owners to present their work to each review team, work with them to satisfy any concerns, and make sure it meets all governance criteria.

* **Clinics &ndash;** Provide developers with a variety of clinics where they can receive feedback on their work, improve upon their service, and improve the health of their work before submitting it for inclusion in a production environment.

Enterprise organizations that provide structure for API development teams find it much easier to realize their governance aspirations. The scaffolding is already there to think about the consistency of services, and the face-to-face or virtual scrutiny of services helps provide the environment for governance practices to be executed, enforced, and evolved before any service reaches a production state. A well-defined API deployment lifecycle will help contribute to a well-defined API governance practice.

## Virtualization

One sign of enterprise groups who are further along in their governance journeys is the use of virtualized environments. Your should require all API developers to mock and iterate on their APIs in a virtualized environment, presenting them as if they’re real, before they ever are given a license to write any code, let alone reach a production state for their services.

* **Mocking &ndash;** Create mock APIs for all endpoints and virtualize every aspect of the surface area of an API, allowing a service to be iterated upon early on in its lifecycle.

* **Data &ndash;** Require virtualized and synthesized data be present for all mocked APIs, returning realistic data with responses and reflecting behavior encountered in a production environment.

* **Sandbox &ndash;** Provide a complete sandbox environment for developers to publish their mocked APIs into, simulating what they’ll encounter in a production environment but done in a much more safer and secure way.

Virtualized environments provide an important phase in the journey for APIs moving from concept to reality. They establish a safe environment for developers to iterate upon their work, and to encounter many of the challenges they’ll face in a public environment, without any of the potential for harm to users or the platform. This ensures that when a service is ready for development, most of the rough edges have been worked out of the service contract.

## Technology

One of the most significant ways in which we found enterprise groups governing the evolution of their APIs is through the technology they employ. This technology is providing much of the structure and discipline that organizations depend on to help ensure that APIs are being developed and ultimately deployed in a consistent manner.

* **Authentication &ndash;** Require standard-based approaches to authentication using Basic Auth, API keys, OAuth, and JWT. Ensure that teams understand when to use which protocol, and how to properly configure and use them as part of a larger API governance strategy.

* **Framework &ndash;** Rely on the programming frameworks in use to inject discipline into the process, dictating the governance of how APIs are delivered before they’re ready for a production environment.

* **Gateway &ndash;** Apply the policies and structure necessary to govern API services as they’re made available in a production environment. Many groups we spoke with had a sandbox or development edition of their gateway emulating many of the same elements that will be found in a production world.

* **Management &ndash;** Similar to the gateway, groups rely on their API management layers to help govern what APIs do, as well as provide transformations, policy templates, and a wide variety of other standardization prior to making services available in production.

* **Vendor &ndash;** Reliance on technology to deliver governance at the API deployment level gives a lot of control to vendors when it comes to governing the API lifecycle. If a vendor doesn’t provide a specific way of doing things, it may not exist within some groups, dictating the governance of many enterprise groups.

* **Tooling &ndash;** Most groups have an arsenal of open-source and custom tooling to help push code from development to production, as well as validate, scan, transform, shape, and harden code and interfaces prior to production usage.

* **Encryption &ndash;** Require encryption by default for storage and transport, using technology to ensure security is a default parameter for everything that is exposed publicly. This reduces the possibility of a breach and minimizes the damage when one does occur.

Our findings demonstrate how important both technological choices and architectural planning are to overall API governance conversations. The services, tooling, and applications we adopt will contribute to our governance practices, either positively or negatively. You should consider enforcing governance for all APIs as they move from development to production, in a way that teams can’t circumvent and often times don’t notice.

## Orchestration

Augmenting the previous discussion of core technology, there are a number of orchestration practices we found that help quantify and enforce governance on the road from development to production. They dictate how code, artifacts, and other elements included as part of the API lifecycle move forward, evolve, or possibly get held back until specific governance criteria are met.

* **Pipeline &ndash;** Continuous integration/continuous deployment services, tooling, and mindsets have introduced a pipeline workflow for many teams, standardizing the API delivery process as an executable, repeatable, measurable pipeline that can be realized across any team.

* **Stages &ndash;** Define clear stages that exist after development, but before production, that insist on more rigorous quality assurance, security reviews, compliance audits, and other governance checks.

* **Hooks &ndash;** Require well-defined pre- and post-commit hooks for all service repositories, and that these defaults are applied throughout a service’s pipeline, no matter which organization they emerge from.

* **DevOps &ndash;** Push that all teams are competent and skilled enough to execute on behalf of their services from beginning to end, and are owning and executing at every stage of the lifecycle. Reduce the need for reliance on special teams, thus eliminating bottlenecks.

* **Logging &ndash;** Identify the logging capabilities of the entire stack for each service being delivered. Make sure logging is turned on for everything, and all logs are shipped to a central location for auditing, and, when possible, real-time analysis and response.

Orchestration provides some clarity on the automation side of moving services from development to production, while also enforcing governance along the way. It allows for an assembly-line delivery of consistent services, and the iteration of each version, in alignment with the overall governance strategy. This reduces the chance for human error and increases the chance for consistent execution of the enterprise API strategy at scale across many different teams.

## The legal department

In addition to technical staff, the legal department should have a significant influence over APIs going from development to production. They can provide a structured framework that can generally apply across all services, but also more granular control over legal documents for specific services and use cases. We saw a handful of clear building blocks in use to help govern the delivery of APIs from the legal side of the equation:

* **Terms of service &ndash;** Have universally-applicable, modular, human-readable, and (possibly) machine-readable terms of service governing all services from a central location.

* **Privacy policy &ndash;** Have universally-applicable, modular, human-readable, and (possibly) machine-readable privacy policies governing all services from a central location.

* **Security policy &ndash;** Provide a comprehensive security policy that governs how services are secured, reflecting the technologies, checklists, tooling, and reviews that are in use by all team members.

* **Licensing &ndash;** Establish clear code, data, and interface licensing to be used across the entire API stack, allowing developers to properly license their services, as well as understand the provenance for the systems and services they depend on.

* **Service-level agreements &ndash;** Have a universally-applicable, modular, human-readable, and (possibly) machine-readable service-level agreement that can be applied across all services, measured, and reported upon as part of wider governance strategy.

* **Scopes &ndash;** Define and publish OAuth access scopes as part of a formal set of legal guidance regarding what data are accessible via services, and what role users and developers play in managing scope.

The legal department will play an important role in governing APIs as they move from development to production, and there needs to be clear guidance for all developers regarding what’s required. Similar to the technical and business elements of delivering services, the legal components need to be easy to access, understand, and apply, while also protecting the interests of everyone involved with the delivery and operation of enterprise services.

# Making APIs available to consumers

A key step in the lifecycle of properly-governed APIs is making them available to consumers, after they’ve been published to a production environment. This portion of our governance research is intended to provide a basic list of the building blocks involved in governing APIs at this stage in the lifecycle.

## Known consumers

Making your APIs available to consumers requires doing a lot of research on your target audience and positioning yourself to deliver a tailored experience. That might involve not only tailoring the design of your API for a particular audience, but the overall presentation, messaging, documentation, and even portal as well.

* **Studies &ndash;** Conduct regular studies on how consumers are using your APIs to develop applications and integrate systems.

* **Landscape &ndash;** Invest the time to understand how consumers are using API services across the industry landscape in which you’re targeting.

* **B2B &ndash;** Position the API to speak to a B2B audience by providing separate portals, documentation, and other resources.

* **B2C &ndash;** Position the API to speak to a B2B audience by providing separate portals, documentation, and other resources.

* **Partners &ndash;** Provide a unique set of resources that speak to partner groups, providing separate portals, documentation, and other resources.

* **Internal &ndash;** Position the API to speak to internal groups, providing separate portals, documentation, and other resources.

* **Context &ndash;** Ensure services are contextually aware. Different patterns, processes, and practices work well within some contexts and fail in others.

* **Office hours &ndash;** Hold conference calls or virtual office hours for different consumer groups to discuss what APIs and support resources are available. Use these session to solicit input on the product/platform roadmap.

Knowing your existing and potential API consumers is essential to delivering a tailored consumer experience. It’s difficult to design and present the right set of resources for an audience that you don’t understand. Understanding your consumers should be an ongoing process, happening well before you even begin development.

## Common patterns

We found a number of common patterns on how best to reach your audience, minimize barriers to adoption and usage, and maximize the impact of your APIs.

* **API design &ndash;** Aligning the design of your APIs with common RESTful resource design patterns helps to present them in ways that are both intuitive and familiar to consumers.

* **Developer portals &ndash;** Consistently-designed, easy-to-navigate, and well-branded portals provide an experience in which consumers can discover, onboard, and engage with your API platform.

* **Documentation &ndash;** Using common, open-source documentation across your APIs enables developers to learn about how to use them.

* **Definitions &ndash;** Providing machine-readable OpenAPI and Postman Collections for consumers gives them a portable definition of what an API does. Consumers can use these in their client tooling to generate code libraries, setup monitors, run tests, and understand what’s possible.

Common design and presentation patterns is one of the reasons why leading API providers have established a strong foothold with their consumers. When you study the approach of organizations such as Amazon, Google, Twitter, Twilio, and Stripe you’ll see that they all make similar use of design patterns, portals, documentation, and other support resources. These commonalities govern the presentation layer of their API-driven services, and represent the consistency that consumers have come to expect and enjoy when working across multiple API providers.

## Communication

The next aspect of presenting production APIs to consumers involves communication. That entails maintaining a steady stream of information around the platform, and leveraging any feedback gather from consumers to inform the API platform roadmap.

* **Updates &ndash;** Provide updates via mediums such as a blog. This helps to keep consumers up-to-date on what’s going on with the platform. And also gives them confidence that the platform is alive and well.

* **Roadmaps &ndash;** Publish a public roadmap for API consumers to help them understand what’s being planned. For internal groups, consider maintaining a private version of the roadmap.

* **Issues &ndash;** Be transparent and communicate any known issues with the platform, as well as their resolution status.

* **Change logs &ndash;** Translate the issues and roadmap into a change log for the platform, showcasing what’s historically occurred with the platform.

* **Showcase &ndash;** Publish a listing of applications and developers; showcase the work being done by API consumers; and highlight the value the platform brings to the table.

The best API providers excel at managing communications. As a result, you always have a sense of what’s happening and being worked on. You also see teams collaborating with one another, sharing practices, lessons learned, and showcasing their work.

# Realizing API governance

Everything covered so far in this document feeds into what should be considered part of the overall governance of an API platform, but with strong focus on the actual delivery of APIs. In this section, we examine what’s needed specifically for governance. We also look at what various organizations are doing to invest in the governance of APIs across their teams, projects, and the operational lifecycle. What follows are some key areas to consider.

## Structure

One key component of API governance that you’ll find in organizations who have been investing it for a while is the presence formal governance structures and teams. While the names of these structures may vary, they all have some common elements worth nothing:

* **Organization &ndash;** A formal organization that’s dedicated to governing APIs across the enterprise, including responsibility for developing and executing a formal governance strategy.

* **Core team &ndash;** Begin with a small, focused, core team, then expand and grow the team as needed.

* **Enablement team &ndash;** Provide an enablement team that works hand-in-hand with individual teams, helping them adopt healthy practices across the API lifecycle and ultimately achieve the organization’s governance objectives.

* **Advisory board &ndash;** Develop an advisory board of internal, and possibly external, individuals who can provide regular feedback on the organization’s API governance.

* **Legacy teams &ndash;** Involve legacy teams as part of your governance efforts to ensure the enterprise’s legacy aspects are taken into account.

There’s a lot variation in how organizations structure their governance teams. Some took a more centralized approach, while others took a more decentralized/organic approach. There’s no cookie-cutter approach to doing this, and finding the right organizational-context fit will ultimately need to be a process of self-discovery.

## The approach

Despite the varying degree of approaches used to organize and execute API governance across the enterprise, there are some common themes in terms of how to approach governance in a pragmatic way. These include:

* **Start simple &ndash;** Keep things as simple as possible when starting out. Don’t bite off more than you can chew and promise too much to the organization. Start with the basics, get involvement and buy-in, and move forward in a logical fashion.

* **Not heavy handed &ndash;** Refrain from being heavy handed with governance policing and enforcement. It’s repeatedly stated that heavy-handed efforts get an overwhelming amount of pushback and can set back efforts significantly.

* **Inline defined &ndash;** Provide guidance, education, and artifacts inline. Don’t expect people to read governance guides and understand how to comply. Feed them information on a regular basis through the channels they’re already tuned into such as corporate communications and their integrated development environments.

* **Having a mandate &ndash;** Think deeply about having a mandate regarding governance. Some people think it’s better stated as a mission, rather than a mandate. Consider the negative impact a mandate might have when it comes to adoption and participation.

* **Select enforcement &ndash;** Be creative in how you enforce governance across operations. Be very selective about where you enforce and push back on users. Find inspiring and motivational ways to enforce governance, being more carrot than stick.

* **Build community &ndash;** Work to build a community around the governance organization. This involves building relationships across teams, recruiting advocates, and regular training and education.

* **Evangelism &ndash;** Spend a significant amount of time reaching out to internal and external stakeholders. And most importantly always be evangelizing to management.

The general idea is to move beyond just a group of people in name only, and to have a structured and planned approach to executing API governance across the organization on a daily, weekly, monthly, quarterly, and annual basis. Organizations can accomplish this by establishing a deliberate API governance cadence, including regularly measuring value and iterating on the overall approach.

## Technology

Technology can play a critical role in helping to define, measure, and report on governance efforts. To that end, we found that those in charge of governance are making smart uses technology, even to the point of being able to govern in real time.

* **Definitions &ndash;** Using OpenAPI, Postman Collections, JSON Schema, and other machine-readable artifacts during all stages of the API lifecycle in order to quantify, measure, and report on how well governance efforts are being realized.

* **Management &ndash;** Leveraging API management solutions to apply policies, rate limiting, logging, and tracking. Such a management layer is primarily being used to understand consumer behavior. However, it’s also being used to understand provider, publisher, and developer behavior as well.

* **Gateway &ndash;** Leveraging an API gateway to serve as the single point of entry into all services. A gateway performs such functions as request routing, composition, and protocol translation. Gateways offer the perfect opportunity to enforce and measure how well governance is being applied across the organization.

* **Logging &ndash;** Using a centralized approach to logging across all services. Centralized access to logs is one of the most important ways in which governance teams can measure and report on what’s happening across the enterprise.

* **Monitoring &ndash;** Monitoring services by default, which allows governance teams to track how well services are meeting their internal and/external service-level agreements across multiple regions. This, in turns, sheds light on how effective governance is being applied across all services.

* **Testing &ndash;** Making sure that APIs are behaving as expected. This can be done by taking plain business assertions and testing them against APIs using machine-defined tests, which can be automated and executed in real time.

* **Security &ndash;** Gathering as much data as possible on how security is being handled. This can be accomplish by leveraging sources of information such as security scanning results, monitoring, and logging.

* **Reporting &ndash;** Leveraging technology behind many of the bullets above to automatically produce and aggregate reports on how well governance measures are being met.

Technology should be a key consideration in deciding how to approach API governance. Having services and tooling inline can help execute and report on how well governance is performing.

Embedded governance is much more likely to be leveraged than externally-mandated tracking and reporting.

## Challenges

Every organization that we talked with shared stories about the governance challenges they’ve faced. Many of these have been covered in the sections above, but we’d like to call them out here so that you can be prepared for what’s ahead in your own governance journey.

* **Getting buy-in &ndash;** Getting stakeholders to buy into governance strategies and solutions is a constant challenge for organizations. With it, however, people will resist governance. Many organizations use co-creation with stakeholders as a way to not only create the necessary buy-in, but to also create the conditions for innovative collaboration.

* **Adopting standards &ndash;** Most organizations agreed that standards are good. Getting people on the ground to actually adopt and realize the benefits of those standards has proven elusive.

* **Developing useful artifacts &ndash;** There wasn’t agreement that definitive artifacts such as guides, prototypes, and other common solutions were necessary. Some teams disregard these artifacts as not being worthwhile investments. Others, however, felt strongly that they were necessary in order to guide people toward working in certain ways.

* **Driving consistency &ndash;** Over and over, API governance teams expressed that driving consistency across the API lifecycle is a difficult process. It sounds easy when you plan a strategy, but actually executing it never quite plays out as envisioned.

* **Constantly improving &ndash;** API governance will never be perfect, and accepting that reality can be a challenge. It’s important that teams assume the attitude that governance is not a destination, but rather a journey. Teams must invest the time and effort to continually improve their approach to governance, trying to be a bit better everyday.

* **Being patient &ndash;** All of this will take time. Be patient. Play the long game. Understand it will take much longer than you expected to see the change you envision.

In the world of enterprise API governance, there’ll be seemingly more challenges than successes. And those challenges will be encountered at every stage of the API lifecycle. Awareness of the types of challenges that other organizations have encountered will you prepare for what’s ahead.

# The road to API governance

Since 2010, there’s been a huge uptick in the number of organizations doing APIs. Only a very small percentage of these organization have started to take a formal approach to API governance. Most organizations recognize the need for API governance, but a struggling to overcome a handful of common roadblocks:

* **People &ndash;** A lack of awareness, training, and communication among stakeholders is the biggest challenge that API governance efforts face. Don’t underestimate people when crafting a technology-focused effort. Technology is easy, people are hard.

* **Culture &ndash;** Be prepared for everything to take "10x" longer than you anticipated because of the challenges in re-shaping culture. Make a plan for how governance will address the existing culture within the organization.

* **Problems &ndash;** Count on problems coming up everywhere. Dedicate a significant amount of time and resources to identifying and addressing problems that come up. Don’t let problems fester, go ignored, or unaddressed. One way to think of this is don’t let too much bad "API governance debt" accumulate.

* **Existing realities &ndash;** API governance can’t proceed without taking your existing realities &mdash such as legacy system environments &mdash into account. While your objective should be to move the delivery of APIs to a specific destination, the strategy needs to be rooted in what exists today in order to build a bridge to where you want to be.

Not all organizations are ready for capital "G" governance. Some have to accept lower “g” governance, doing what they can with what they have to drive some aspect of governance forward. While an organized, centralized, and well-funded governance program is ideal and can achieve significant progress, a significant amount can still be achieved using a scrappier approach, at least until those efforts gain more traction and the resource attention deserved.

# Conclusion

This report pulls together several years of governance-related research, combined with information obtained from several interviews with API governance professionals. At this point in time, it’s important to recognize that API governance is more of a discussion than a formal discipline. There are a few, but not many, organizations blazing the API governance trail, with formal strategies and programs in place. Unfortunately, there isn’t much information publicly available on these efforts.

Therefore, the objective of our research effort was to bring some of this information to light, and assemble our findings in a logical order, reflecting how an organization might approach governance:

* **Organizational roles and models &ndash;** Defining what roles are needed to make governance happen and designing how to organize those roles.

* **Software architecture &ndash;** Laying out the overall approach to software architecture across the enterprise.

* **Identification and prioritization of APIs &ndash;** Defining the right resources to expose.

* **Development of standards around the delivery of APIs &ndash;** Working to standardize how things are done.

* **Moving APIs into a production environment &ndash;** Moving from idea to reality in a standard way.

* **Making APIs available to consumers &ndash;** Exposing resources properly to consumers.

Not every detail in this report will apply to the VA, nor every other organization looking to establish a wider API governance strategy. Our report is meant to shed light on the scope of how enterprise groups are addressing governance. And to serve as a source of information for organizations &mdash no matter how big or small &mdash to starting learning from one another.

Furthermore, this report reflects a patchwork of things that should be considered, rather than a prescriptive list of actions to take. There’s no such thing as a one-size-fits-all model to follow. With the right team and the right approach, you can make governance work for your organization and your specific circumstances.

You can’t ignore the negative perceptions of governance. Many people view governance as the antithesis of agility, innovation, and empowerment. It’s important to manage these perceptions, and give people the confidence that you’re approaching API governance in a way that will work for them and the enterprise.

One definition of governance comes from the Cambridge Dictionary: "the way in which an organization is managed at the highest level, and the systems for doing this[.]" Don’t conflate the highest level with the highest levels of management, and instead let it be more about the highest levels of strategy across the organization. It’s the system for governing a complex machine of API-driven gears that make applications work together across the enterprise. It’s the governance of the machine that has the potential to allow every individual within the enterprise to play a central and meaningful role.

# Appendix A: interview questions

For each interview, we asked the following questions:

1. What role do you play within the organization?

2. What’s your general approach to designing software architectures?

3. How does your organization decide which APIs to build in the first place?

4. How does your organization define the data models and standards upon which to deliver and operate APIs?

5. After your organization has decided what API(s) to build, how does your organization ultimately get them into a production environment?

6. How does your organization make APIs valuable to third-party consumers?

7. Do you have a formal API governance program in place? If so, please describe its mission and scope, how it was stood-up and rolled-out, how its structured, how its staffed, how it operates, how it has evolved, and how you plan to evolve it further.

8. If you don’t have a formal API governance program in place, are there any aspects of the API lifecycle that you’re currently governing? If so, please describe how you do that.

Over the course of the interview, we also asked the following questions:

1. What’s working well and what isn’t?

2. What improvements would you like to make?

3. What critical lessons have you learned?

# Appendix B: UK’s Government Digital Service interview notes

## 1. What role do you play within the organization?

Serve as Lead Tech Advisor and Head of Technical Writing. My group looks at what standards and guidance that the government needs.

Our former CTO found 18F’s API Standards to be an incredibly useful resource, and wanted to do something similar, addressing questions such as: What areas around API’s should be standardized? And what areas shouldn’t?

So we did a series of workshops around security, API documentation, and service levels. And decided what we should be saying in those areas.

Local government isn’t really building APIs yet. Local government is consuming government APIs. They tend to have a consistency problem in consuming APIs from the national government. So GDS creates an MOU template (how data is used) with local governments. MOU is the legal side of APIs such as how data is being handled, etc.

## 2. What’s your general approach to designing software architectures?

Agile approach to development. Moving to microservices architecture. Moving away from legacy is important. Do Wardley Mapping to identify service dependencies. Make everything open.

## 3. How does your organization decide which APIs to build in the first place?

We use Wardley Mapping. Try to create reuse as much as possible. Working in the open helps facilitate, because it encourages the behavior  to find something that’s already out there. GDS looks across government to identify common services or common data needs that should be built as APIs such as payment and notification. Right now there’s a lot of pressure on spending efficiently, so reuse is important.

## 4. How does your organization define the data models and standards upon which to deliver and operate APIs?

GDS has API standards in place. Was the result of cross-government collaboration with local and central government. HMRC and DWP are building APIs on a much larger scale.

First set of API standards events was mix of talks and feedback.

Second was all workshops. Three different sessions happening on different areas. About 80 people total across three streams. These workshops led to the API standards.

Collaboration creates buy-in and trust.

Originally, HMRC was going to create their own API standards. But now they’re going to refer to GDS’ because they were shaped by HMRC.

HMRC produced API standards for product managers that are less technical, and GDS is going to leverage those.

GDS tech writers are more than what we typically think about that role. They are content designers and they understand tech.

## 5. After your organization has decided what API(s) to build, how do you ultimately get them into a production environment?

Follow the GDS delivery model (discovery, alpha, beta, live).

## 6. How does your organization make APIs valuable and usable to third-party consumers?

Make sure technical documentation is designed and maintained well. Took a developer-centric approach to understanding what developers need. Have done diary studies, cort sorting, etc. to understand how they wanted their documentation structured. They discovered false assumptions about who used the documentation and how they used it.

From this research, created a documentation formatting tool, used across all products to help create consistency developer documentation.

Making APIs RESTful is default standard. Trying to encourage adoption of this.

Use Swagger for documentation and version control.

Be consistent and clear with versions, and making those as part of the URLs.

Primary users of GDS’ documentation are other government organizations.

Have internal government APIs, B2B APIs, and B2C APIs. Investment in documentation for B2B and B2C is higher; have ideal staffing models for these. GDS API documentation goes through the central GDS group for review. GDS tries to play support role for other cabinets. GDS guides them through how to structure and staff to manage documentation effectively.

Use GitHub and pull requests to document. Use a tool that spits out formatted documentation that publishes to GitHub.

## 7. Do you have a formal API governance program in place? If so, please describe its mission and scope, how it was stood-up and rolled-out, how its structured, how its staffed, how it operates, how it has evolved, and how you plan to evolve it further.

GDS standards are defined, but not mandated. Trying to make so useful that they are adopted.

Can "enforce" that these are used through governance around domain management. Can only use API domain if GDS’ API standards are used.

Currently creating architecture assessment authority to help guide APIs in the right direction.

Have few people on staff to drive the API strategy. Would love to be going a lot faster. There’s so much developing in the API space such as API management tools that it can be a challenge to keep up with.

## 8. If you don’t have a formal API governance program in place, are there any aspects of the API lifecycle that you’re currently governing? If so, please describe how you do that.

n/a

# Appendix C: HMRC #1 interview notes

## 1. What role do you play within the organization?

Role has always been tied to APIs. Was lead architect for APIPD (API Program Design), the platform for which was built by another team. Now head-up our solutions team. Run internal API design consultation sessions with teams when they are just getting started. Anything that’s going outside to third parties such as tax service providers runs through our API platform.

## 2. What’s your general approach to designing software architectures?

Start with why. Have to isolate a strategy. Even if organization has one, have to look at it in order to define objectives that support the strategy. Can you identify KPIs at a tactical level to help define and monitor APIs? For example, are you increasing the reach of the data? Are you saving people money?

Once strategy is defined, provide advice on defining a set of principles to guide the overall delivery approach; converging on smallest number of possible things to support a range of things; keeping complexity inside of the organization and shielding consumers from that; and not breaking consumers.

External advice provided consists of APIs specs (e.g., Roy Fielding REST). Internal advice provided is to close gaps not explained in external API specs.

## 3. How does your organization decide which APIs to build in the first place?

Originally, didn’t do it right. Started about 6 years ago. Started to mature about 2 years.

Started to design APIs for a specific project or consumer. Doing in isolation leads to duplication. For example, another teaming doing something similar. Didn’t have people at higher level looking across the landscape.

Started doing domain-driven design to take advantage of Pareto principle. Can design one or few APIs to support 80% of consumer needs.

The core domain, in this case the tax domain, should be modeled very well. Think about resources and different views based on this model (e.g., summary, detailed, time). Design APIs to be multi-channel based on this core domain. Been doing this over last 18 months. For example, a company may have to pay VAT, corporation, and personal assessment. Don’t want to have multiple credentials to access. Looking to build on this going into the future.

## 4. How does your organization define the data models and standards upon which to deliver and operate APIs?

There are a huge number of organizations and groups focused on this. Core architect group uses more modern delivery. Model things using domain-driven design. About 30 architects in the group like this approach. Use event storming to help define domains. Multi-stakeholder, not just architects. Built-up a language to help domain. If you do domain-driven design right, it should reflect in the code in terms of recognizable terms.

External standards, advice stack: HTTP, OAuth, OpenID, REST, HATEOAS (evolve API by providing links). Best to use existing standards when dealing with external consumers.

Working on internal standards as well.

Lesson learned: the organization’s domain is the most important thing. Don’t get fixated by external standards or tools such as Swagger or RAML. Great for non-HATEOAS APIs. API should minimize out-of-bound and should be self-describing according to Fielding model. If not, will be hard coded and hard to evolve. For non-true REST, Swagger or RAML good. A lot of people are trying to push GraphQL. Great if you have super user who understands your domain. Then can federate power and share complexity with the user.

## 5. After your organization has decided what API(s) to build, how do you ultimately get them into a production environment?

Just focus on consumer-facing APIs such as tax software providers. Engage process above. Will go onto the API platform where implemented and hosted. That platform has few things available to minimize rework: OAuth, OpenID, scopes for reducing resources, etc. In parallel to this, engage the API service process.

Welcome session: producer team talks with Shipley team &mdash standards, platform architecture implementation, and API design.

Kickoff session: looks at business requirements, strategy, backend data sources. Artifact that comes out is a kickoff artifact that’s published and will evolve over time as the design evolves.

It’s a living document for communicating with the organization: what they are trying to do and how they are progressing.

Next stage API design clinic. Architect-to-architect discussion focused on the user journey, etc. Understand the users. Then start dig into domain modeling, do state diagram / finite state machine.

After this, the producer team can start implementing, but can continue to engage with the central team.

Recommend to teams that they build simulated APIs to do user research. For example, can do A/B testing. And make changes on-the-fly during sessions. Lesson learned: user research is not the only part of research. Just as backend shouldn’t drive all design decisions, should consider other types of research such as architectural research.

Have to go through different assessments such as data modeling, security assessments, fraud analysis before can push to external testing environment. How long consumer testing lasts varies.

Another team does checks before API can be pushed to production. Need just enough governance to make this work.

An aside on our API Service Process. As part of our API platform, you have API design and API standards, with several groups working together. The entire customer process and customer architecture is called MDPT. The API platform is part of the tax platform, which is restricted to third parties.

Lesson learned: the central governance run by internal civil servants is critical. Before just contractors without authority.

## 6. How does your organization make APIs valuable and usable to third-party consumers?

Driven by market demand, so have an idea of what everyone wants. We’re targeted about providing what they need in order to achieve their goals (that is, don’t bog them down with things they don’t need). Use REST + HATEOAS.

## 7. Do you have a formal API governance program in place? If so, please describe its mission and scope, how it was stood-up and rolled-out, how its structured, how its staffed, how it operates, how it has evolved, and how you plan to evolve it further.

Described above.

## 8. If you don’t have a formal API governance program in place, are there any aspects of the API lifecycle that you’re currently governing? If so, please describe how you do that.

n/a

# Appendix D: HMRC #2 interview notes

## 1. What role do you play within the organization?

Head of API Design and Delivery, focused on enabling the rest of the organization to delivery APIs. Run the API platform, including catalog of API services and API standards. Have six delivery centers, with various teams deliverying APIs.

In functioning as a Center for Enablement, things have been going well. There have been challenges with ensuring quality given some constraints such as timeline.

Platform is missing some capabilities. Have been striking the right balance between governance and autonomy.

## 2. What’s your general approach to designing software architectures?

Brought a large outsourced system in-house. Called multi-digital tax platform. Started to apply modern practices, and set groundwork for APIs. Use microservices, containerization, cloud, etc. This approach has allowed HMRC to bring the capability in-house.

## 3. How does your organization decide which APIs to build in the first place?

When started, created an API strategy around creating APIs for third-party software. Instead of building the frontend themselves, wanted to open the APIs so third parties could consume in their applications. Started with a few exemplar ones to get momentum going.

Now focus on APIs for three groups: (1) third parties; (2) other agencies; and (3) internal consumers.

Do have a digital frontdoor where others can request APIs. Because funding is a constraint, really need a strong business case that aligns to mission.

Building APIs are very project focused and centered around data. Central group doesn’t prioritize really. Driven by demand or legislative requirement. Want to start exploring a change in model to be more user-centric and help to shape API strategy. Have been challenged to create reusable APIs across the organization. Standards have helped, but been a challenged to maintain consistent APIs, domain model, etc. Mastering the data from all the sources and ensuring their quality has been a challenge. Foresee this as being a challenge at scale.

## 4. How does your organization define the data models and standards upon which to deliver and operate APIs?

Have developed a domain model for the organization. Sets out how they want to address problem. Eventually going to publish this to GitHub so developers will understand HMRC’s thinking.

Standards focus on API design principles. Been a lot of work to agree on these.

Have an organization that is responsible for enterprise data architecture. Work closely with them.

## 5. After your organization has decided what API(s) to build, how do you ultimately get them into a production environment?

Use an API service process. Starts with a welcome call. Then project teams do user research (treat APIs as products). Use REST Assured to help design API and watch how developers use use it. Project teams communicate research using a product canvas, where it fits within the domain. Then have a design clinic. Then project teams start building. Then do assessments using various checklists. For example, if doing transactions, have to do fraud-risk assessment. Also do platform and architecture assessment.

In-process of developing a standard similar to GDS’.

## 6. How does your organization make APIs valuable and usable to third-party consumers?

Viewing them as products, and looking at functional and non-functional aspects. Have a software development support group that interacts with industry and users to understand how they are experiencing HMRC’s APIs.

Have weekly calls with vendors and where they are going with their product roadmaps to understand consumer direction.

Having a cradle-to-grave service is important.

## 7. Do you have a formal API governance program in place? If so, please describe its mission and scope, how it was stood-up and rolled-out, how its structured, how its staffed, how it operates, how it has evolved, and how you plan to evolve it further.

See above.

Have struggled to keep up with API standards with the development of the teams. Hasn’t been a huge mandate. HMRC has been somewhat under-resourced to push standards forward. Will focus on how to scale to industrialize APIs.

Organization starting to learn about the value of following the standards based on first-hand experience.

Working with GDS to establish a government-wide standard for APIs.

## 8. If you don’t have a formal API governance program in place, are there any aspects of the API lifecycle that you’re currently governing? If so, please describe how you do that.

n/a

# Appendix E: Capital One interview notes

## 1. What role do you play within the organization?

Director for Capital One Platform CoE. Previously API CoE. Changed name because not only handle governance for API processes and design standards, but also have responsibility for data transformation and event streaming. Have about 8-9k developers. Many APIs are internal. Work on carefully grooming the ecosystem to make sure delivering the best value.

Focus on: (1) understanding the landscape, not only internally, but externally as well (e.g., disruptive technologies); (2) helping people navigate the landscape and how to apply new developments to certain use cases; (3) measuring success. It’s one thing to set up a CoE, but it’s quite another to measure success, which is critical to viability of the CoE. From CoE perspective, it’s not just about technical metrics, but business metrics as well.

## 2. What’s your general approach to designing software architectures?

Capital One is probably unique in that the CoE sits within the product management group. Draw a definitive line between the interface and the implementation. The CoE focuses on the interface. The architecture teams focus on the implementation.

CoE trying to create an ecosystems of APIs that are cohesive and coherent. Try to avoid isolated areas of practice.

Product management + API design go hand-in-hand in terms of creating a great experience.

Trying to experiment with teaching people about APIs the same way you learn to drive. You don’t read the car manual. People don’t tend to dive into the standards doc, nor desire to, nor retain the information. How to put the essential information in front of people as they’re working using smarter tools such as Swagger Editor to provide in-context help (business-specific rulesets). Experimenting with machine learning. Switching from model to you have to be expert in all the docs, to instead providing great tools to provide context-specific help.

## 3. How does your organization decide which APIs to build in the first place?

This comes from the lines of business. They know their business and strategies and delivery intent. CoE doesn’t decide this.

## 4. How does your organization define the data models and standards upon which to deliver and operate APIs?

Context is everything. Companies get in trouble when they think things stored at rest should be streamed out the same way to consumers. Subscribe to backend for frontend patterns. What they’re preparing for consumers matters.

There’s group that defines data standards, and there’s governance around that. But by the time it gets to API level, then that’s where focus on the context of how that data is being consumed comes into play.

## 5. After your organization has decided what API(s) to build, how do you ultimately get them into a production environment?

Practice API-first design before start coding. Teams start developing after contract is defined. Track lead time at each stage. Any deviations are flagged and the CoE can swoop in to help remove blockers or address issues.

Use a central management tool to manage environments. Endpoint registration process that automates environment set up and promotion.

Use centralized gateway, which helps to display status, metrics, etc. in API portal.

## 6. How does your organization make APIs valuable and usable to third-party consumers?

Spend a fair amount of time looking at competitive landscape. Have experimented with third-party APIs to gather feedback / test a hypothesis. In some cases, demo as well. But after running live for a bit, sometimes the business case doesn’t hold up to real-world test. There’s only so much capacity to do all the things, so if an API experiment isn’t showing promise, will spin down and refocus efforts elsewhere.

For those APIs that are ongoing programs, invest the appropriate resources  (e.g., tech writers) to run well and make a great developer experience.

## 7. Do you have a formal API governance program in place? If so, please describe its mission and scope, how it was stood-up and rolled-out, how its structured, how its staffed, how it operates, how it has evolved, and how you plan to evolve it further.

Original motivation for API governance was concern around fragmentation that would make delivering products difficult and concern for pushing complexity onto to consumers, which might lead to duplicative integration efforts to get the data they needed.

Realized the importance of consistent interfaces in order to deliver consistent and great experiences.

Advice for getting started: start simple. For example, avoid designing perfect API standards doc. Things change so quickly. Governance is not a static thing. Less concerned about the static / authoritative artifact. More concerned about creating the process + capability for safely changing in the organization. Starting simple could be making sure APIs have health routes. Once you got that, then move onto monitoring, for example. Hard for big organizations to drive large-scale change at once. Gain momentum around small wins. As you do this, you refine and harden your process. You learn who is engaged and who isn’t. Religious wars get started around huge standards push. That will sap energy and kill progress.

Take an internal developer evangelist approach. Critical to building communities and alignment.

## 8. If you don’t have a formal API governance program in place, are there any aspects of the API lifecycle that you’re currently governing? If so, please describe how you do that.

n/a

# Appendix F: BYU interview notes

## 1. What role do you play within the organization?

Enterprise architect in the CIO office, doing org-wide API discovery and implementation.

## 2. What’s your general approach to designing software architectures?

Bring people together to co-discover and come to a consensus on the right approach. Takes time, but critical to creating buy-in and bringing people along.

## 3. How does your organization decide which APIs to build in the first place?

Take a breadth-first approach. Get group of people together to talk about APIs, what are good principles, and how to approach it. Wanted to define an approach to APIs across the organization. For example, wanted APIs that embody workflow, not CRUD. For example, in client, if student drops ECON 120, have to drop ECON 121.

Decided wanted API to reflect business of BYU. Took a long time to define this.

Created a pot of money to support API development. Anyone who asked to build functionality that required interacting with one of the 950 web services, provided money from that pot to the development team to build and use an API instead. Requires a degree of visibility into all the IT projects that are happening. Have been building out at University API incrementally that defines resources (e.g., people API) that ultimately will satisfy the need for everything. Some of these resource APIs are at different stages. Want to be in a position when have to replace people system, for example, can just swap it out because the APIs are in place.

## 4. How does your organization define the data models and standards upon which to deliver and operate APIs?

Arrived at consensus among a small group of influencers. Started implementing by using an API manager. Now using WSO2. Put a developer portal in place.

Right now doing a weekly 2-hour meeting with developers from across the university to ask questions, challenge assumptions, specify what level of detail is really necessary in JSON packages, etc. Have to have processes and money to solve the issues raised during these meetings, but at the same time stay true to principles. If not, developers will rebel and won’t use the API. Developer is the customer. Developers come and ago, so need to have continuous communications to socialize principles, standards, etc. and hear their needs and preferences.

## 5. After your organization has decided what API(s) to build, how do you ultimately get them into a production environment?

After going broad, then focused on vertical slices that aligned to projects that university needed. Had stopgap funding to cover extra cost of building the API.

## 6. How does your organization make APIs valuable and usable to third-party consumers?

Must look at the developer as your customer. Did a good job of putting a developer portal in place. Need to improve support beyond just self-service documentation.

Have a strong information governance process, but much of that was in place before APIs, so need to address questions/issues around information use. Making sure the developers aren’t being burdened by this takes a lot of time and isn’t trivial. Need to socialize what APIs are, how they work, etc. with information governance officials in order to get them onboard.

## 7. Do you have a formal API governance program in place? If so, please describe its mission and scope, how it was stood-up and rolled-out, how its structured, how its staffed, how it operates, how it has evolved, and how you plan to evolve it further.

Use a governance process called Architects Council. Bring in architects/developers from across the university to address a range of topics. The governance model is consensus. More informal. Sometimes CIO needs to break ties.

Most of the APIs are developed and managed by central IT group.

Can enforce governance around how developers consuming the API through API management platform.

## 8. If you don’t have a formal API governance program in place, are there any aspects of the API lifecycle that you’re currently governing? If so, please describe how you do that.

n/a

# Appendix G: MuleSoft interview notes

## 1. What role do you play within the organization?

Person #1 - Regional Director for Federal Customer Success; help advise clients on processes and management models for making best use of MuleSoft.

Person #2 - Solutions Consultant Team (pre-sales).

## 2. What’s your general approach to designing software architectures?

Recognize that most impactful thing to focus on is info and business entities. Every digital initiative is driving toward information. Understand and prioritize information types.

Understand and automate key business processes.

Information and processes are most important to digitize.

Ensure there’s alignment between design of architecture and business outcomes, and there are KPIs in place to measure.

## 3. How does your organization decide which APIs to build in the first place?

Partly answered above.

Seen three patterns: (1) driven by specific projects (e.g., what info the app needs); (2) prior knowledge about what info is valuable (they know their business) &mdash they think of their business as a potential platform; and (3) what are the commonalities across the business (what would have highest reusability?), for example, that could accelerate delivery.

## 4. How does your organization define the data models and standards upon which to deliver and operate APIs?

Some organizations just chase after standards because that’s what’s industry is talking about. For example, FHIR.

Mature organizations treat standards as conveniences, for example, when API would be consumed by external entities.

Don’t simply embrace because that’s what everyone else is doing. Industry standard might not be as authoritative or fit for purpose as you think.

For internal models, best to use domain models that are fit for purpose.

For big organizations, you can understand why they might lean toward industry standard.

Industry standards are about interoperability with external players so make sense to use. No point in creating own standard.

If it’s internal issue, industry standard might not be the best approach.

## 5. After your organization has decided what API(s) to build, how do you ultimately get them into a production environment?

Leverage automation as much possible (e.g., using CI/CD), and good DevOps practices in general. Building out self-service capabilities.

## 6. How does your organization make APIs valuable and usable to third-party consumers?

Valuable portion addressed in questions above. If the APIs capture the org’s core value, then they are inherently valuable.

Every API sits in its own business channel. For example, patient portal. API should be fit for purpose based on the channel.

## 7. Do you have a formal API governance program in place? If so, please describe its mission and scope, how it was stood-up and rolled-out, how its structured, how its staffed, how it operates, how it has evolved, and how you plan to evolve it further.

MuleSoft’s Center for Enablement represents how a few of their most mature organizations are managing governance.

Need top-down support for governance.

Different models for standing-up.

Some start with small 3-4 internal people to establish core. Some do shared services model. Others leverage an SI. Can be mix of internal and external resources.

Not heavy-handed governance board. Don’t serve as a gateway. Will just be blockers.

The enablement team works with other projects team in an advisory/guidance support role.

Some organization create multiple support groups to serve different lines of business.

## 8. If you don’t have a formal API governance program in place, are there any aspects of the API lifecycle that you’re currently governing? If so, please describe how you do that.

n/a
