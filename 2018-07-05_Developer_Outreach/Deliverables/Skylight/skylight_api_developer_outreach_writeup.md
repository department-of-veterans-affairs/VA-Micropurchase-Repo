# API DEVELOPER OUTREACH RESEARCH WRITE-UP

This is [Skylight’s](https://skylight.digital/) report for the U.S. Department of Veterans Affairs (VA) microconsulting project, "[Developer Outreach](https://github.com/department-of-veterans-affairs/VA-Micropurchase-Repo/issues/26)." The VA undertook this project in order to better understand how private- and public-sector organizations approach Application Programming Interface (API) developer outreach.

In preparing this report, we drew on nearly a decade’s worth of our own API developer outreach expertise, as well as information obtained through interviews with seven different organizations. For each interview, we followed an interview script (see Appendix A) and took notes. The Centers for Medicare & Medicaid Services (CMS) Blue Button API program (see Appendix B), the Census Bureau (see Appendix C), the OpenFEC program (see Appendix D), and Salesforce (see Appendix E) all agreed to releasing our notes publicly. The other three organizations (a large social networking site, a government digital services delivery group, and a cloud communications platform) preferred to keep them private.

We structured this report to largely reflect the interview conversations that we held with people who are involved in developer outreach programs and activities. These conversations focused around the following questions:

1. What is the purpose and scope of your API developer outreach program?

2. What does success look like for you?

3. What are the key elements or practices (e.g, documentation, demos, webinars, conferences, blog posts) that you are using to drive and sustain effective adoption of your API(s)?

4. Do you make use of an API developer sandbox to drive and sustain adoption? If so, please describe how you've designed that environment to be useful and usable to developers.

5. What types of metrics do you use to measure adoption effectiveness and to inform future decisions about how you evolve your program?

6. How is your outreach program structured and staffed? How did it start out and evolve over time?

7. Imagine that you are charged with ensuring the complete failure of an API developer outreach program. What things would you do to ensure that failure?

8. What big ideas do you have for evolving your outreach program to make it even more effective?

if we were forced to distill all of the interviews and all of our existing information down to a single essential piece of advice, it would be this: involve the programmers who are going to be using your APIs. By "involve," we mean:

1. Engage them early.

2. Support the users with documentation, hackathons, forums, and other types of engagement activities.

3. Measure the happiness of the programmers who are using your APIs, as well as the number of times that they use them and how they use them.

4. Prioritize your APIs so as to maximize the utility to would-be programmers.

In the pages below, you will find a large number of specific suggestions culled from extensive interviews and our collective personal experience. All of these specific techniques are in service to the idea of designing the API program with the programmers who will use the API in mind at all times.

# Research findings and thoughts

## Purpose and scope of developer outreach programs

### What we learned

Different API programs have different purposes, and these purposes are fulfilled by varying levels of API outreach resources. Just as organizations have invested differing amounts of resources into their web presence over the last 25 years, the API providers we talked to are each at different stages in their API journey. This variety presented us with a range of informative stories concerning outreach programs.

#### The purpose behind APIs

Our interviews revealed a number of potential purposes for API development, a number of which are presented below:

* **Build it and they will come:** It is common for companies, organizations, institutions, and government agencies to launch an API effort with no specifically-stated purpose. They make resources available, build awareness amongst developers, and encourage innovation. While such organizations may not know what the future will hold, they believe that their investment in their API platform in a sensible and pragmatic way will attract developers and the inevitably innovative applications they will bring.

* **A focus on APIs as a product:** Some interviewees we spoke to are fully invested in their API efforts, treating their APIs as a product in and of themselves. They develop formal programs around their API operations, treat API consumers as end customers, and consistently ensure their programs have the resources they need. In short, they treat API operations like a business and run them as efficiently as possible, even if commercial sales is not the end goal.

* **A focus on APIs as an enabler:** Other interviewees we consulted focus on ensuring the availability of APIs as a means to support an existing web or mobile application; in a sense, the API is relegated to a secondary role relative to the primary application’s existence. APIs for these kinds of organizations serve to drive traffic, adoption, and integration when it comes to a larger vision, but the APIs themselves are simply enablers for the overall platform.

* **A focus on the developer:** Beyond the API as a product &mdash; and the web and mobile apps they power &mdash; API efforts tend to focus on the developer. Development-focused APIs emphasize what developers will bring to the table when they have the resources and support they need, and are thus central to the investment and engagement necessary for successful outreach/development.

* **Attract unique entities:** API platforms are often aimed at attracting the attention of interesting/progressive companies, universities, institutions, and other entities. These external entities can often put API resources to use in new and innovative ways, and in doing so, they can bring attention and potential partnerships to the platform.

* **Leverage the network effect:** Some API providers we interviewed expressed an interest in joining a wider network of collaborative open data and API efforts. They felt that working in concert with others, by bringing together many different federal, state, or municipal agencies, would benefit the platforms. Further, they felt this would allow the API initiatives to be led by either policy or private interests.

* **Save developers time:** Overall, the most positive motivation for API development expressed by existing providers was to streamline API onboarding and integration. Further development would help internal, partner, and 3rd party public developers be more successful in putting API resources to work in their web, mobile, and device applications.

#### The scope of API investment

The programs we spoke to each had differing levels of investment, access to resources, and primary purposes. Since the scope of an API investment is naturally a function of these factors, this meant that the organizations we interviewed had different intended scopes for their API projects. We have collated a selection of these scopes below.

* **Starting small:** A common theme across API operations we spoke with was the importance of starting small and building a stable foundation before attempting larger infrastructure development. Beginning with a basic, yet valuable set of API resources, fleshing out the entire lifecycle, and processing around what is necessary to be successful before scaling and increasing the scope of API operations was routinely described as a critical part of any API scope.

* **Invest as it makes sense:** A lack of resources is a common element of slow growth and unrealized API operations. Bringing significant levels of investment to projects while simultaneously applying appropriate human and technological capital to API operations were universally mentioned by our interviewees as critical to seeing desired results.

* **Working with what you have:** Almost all the API programs we spoke to worked in resource-starved environments. They wished to do more and to be more, but lacked the time, human investment, and technical resources to make it happen. This forced the organizations to work with what they had, making the most of their limited opportunities while hoping for eventual greater contributions.

* **A focus on improvement:** All the API programs we interviewed expressed that they wanted to be doing more with their programs. They want to formalize their approach and increase their resource and labor investment in the areas in which they have seen success. Ultimately, their target scope was to focus not on just meeting expectations, but on moving towards excellence and mastery of what it takes to scale their API efforts.

Every API effort clearly has its own personality, and while there are common patterns, the environment, team, and amount of resources available appears to dictate much of the scope of developer outreach programs. However, the scope of any effort will always start small and move forward incrementally as confidence grows.

### What our thoughts are

We learned a lot talking to API providers about the purpose and scope of their API operations. Our interviews also reinforced much of what we know about the API operations of leading providers like Amazon and Google. When it comes to the motivations for developing APIs, ensuring an appropriate level of investment and planning for future scalable growth are necessary steps in giving an API the best chance to succeed.

Augmenting what we learned from providers, we recommend focusing on the following areas in order to achieve API purposes, grow and scale API operations, and integrate API technology into the fabric of an organization’s overall operations.

* **APIs are a journey:** Always view API operations as a journey and not a destination, setting expectations appropriately from the beginning. Do not raise the bar too high when it comes to achieving goals, reaching metrics, and getting the job done. API operations will always be an ongoing effort, with both wins and losses along the way.

* **Always start small:** Reiterating what we researched in the API sector as well as what we confirmed in our interviews, it is important to build a small, stable base before moving forward. This does not mean you cannot develop rapidly, but before you do, make sure you’ve researched the API and planned for its success, understanding what will be needed throughout the lifecycle of all APIs you intend to deliver.

* **Center on the end user:** It is always important that every goal and purpose you set for your API platform center on its end-users. While the platform and developer ecosystem is always a consideration, the end-user is the central focus of the "why" and the “how” for API technologies, especially consider the scope of operating an API in both the private and the public sector.

* **A dedicated team:** Even if it is a small group, always work to dedicate a team to API operations. While APIs will ultimately be an organization-wide effort, it will take a dedicated team to truly lead the API to success. Without centralized, dedicated leadership, APIs will never attain true relevance within an organization, leaving to be a side project that rarely delivers as expected.

* **Everyone pitches in:** While a dedicated team is a requirement, an API’s development should always invite individuals from across an organization to join in the process. Ideally, API operations are a group effort led by a central team. It is important to encourage individual API teams to feel a sense of ownership over their API, just as it is important to encourage business users to participate in development conversations.

* **Striving for excellence:** API operations will always be forced to deal with a lack of resources. That is simply a fact of dealing in APIs. However, each API program should be seeking excellence, working to understand what is needed to move APIs forward in a healthy way. Improving upon what has already been done, refining processes that are in motion, and making sure all APIs are iteratively improved continually benefits a platform’s end users.

* **Continued investment:** Always be regularly investing in the API platform. Continued input of both human resources and financial resources helps to ensure that a platform is not starved along the way. Otherwise the API-in-question will constantly fall short and threaten the viability of the platform in the long term.

While the purpose of an API may depend on the mission of its developing organization, in the end, APIs always exist to serve end-users while protecting the interest of a platform. The scope of any such API will depend on the commitment of an organization, and as such, there is no "right answer" to the question of determining the purpose of any single API platform. The only true constraint is the assurance that the API remains in alignment with an organization's mission as it grows and scales.

## How success is defined

With a variety of possible purposes, scopes, and approaches, an API’s success can be defined in a myriad of ways. Depending on the motivations behind the API, and the investment made, the measure of success will depend on what matters to the organization. However, there are some common patterns to defining success, which we extracted from both the interviews we conducted and the research we performed as part of this outreach study.

### What we learned

Along with what we learned about the purpose and scope of API platforms, we discovered more about the different ways in which API providers are defining success. We have collected the highlights among these metrics below.

* **Building awareness:** API success revolves around building awareness that an API exists, as well as awareness of the value of the API resources that are being made available. Awareness is not simply a consumer side consideration, though; providers, too, must possess an awareness of the value of their resources in relation to both other API developers and consumers alike.

* **Attracting new users:** Bringing attention to an API and attracting new users is one of the most common ways of measuring the success of API operations. While new users won't always immediately become active users, their interest and involvement will bring attention to and awareness of what the API platform can deliver. Attracting new users is one of the easiest and most accessible ways to measure the success of any API, according to our interviews, but importantly, none of the platform providers we spoke to recommended that an organization should stop there.

* **Incentivizing active users:** While attracting new users is easy, producing active users is much harder. The easier it is to onboard with an API and make the first series of API calls, the greater the likelihood that API consumers will integrate the platform into their own resources and work, which is a critical metric for any API provider.

* **Applications:** Applications and development are the cornerstones that incentivize API providers to invest in APIs, and across the board, our interviewees cited application integration and involvement as a prime candidate for determining an API’s success. This could be quantified both in terms of new applications relying on the API platform, as well as active application processes that integrate with the API’s platform. In either case, measuring usage was considered an excellent means to justify the existence and growth of an API platform.

* **Entities:** Getting the attention of companies, organizations, institutions, and other government agencies is an important part of the the API journey. In particular, developing an awareness of and encouraging the usage and adoption of APIs among groups already leveraging the technology is an important metric by which success can be determined.

* **End users:** Of course, API providers articulated the importance of serving end-users. Besides serving an organization’s mission, the true purpose of an API is to satisfy an end-user, and so measuring success based upon how much value is created and delivered to these users and customers, and even the public at large, can directly verify that an API is living up to its billing.

* **Stakeholders:** Further discussions with API providers implied that success is also defined in terms of involvement with other stakeholders. Ensuring that the definition of success was crafted in an inclusive way allows everyone involved and impacted by the project to input their voice. This widens the target audience to make sure success is a large umbrella that covers as many individuals within an organization as possible.

* **New resources:** An additional area that was used to define success was the number of new API resources added to a platform. If an organization is currently in the development phase and deploying APIs into production, it is likely that a platform already has a handle on what it takes to successfully deliver APIs throughout their lifecycle. Making new APIs a great way to understand the velocity of any platform, and how well it is ultimately doing.

Measuring the success of an API platform is a much more ambiguous goal than determining scope, purpose, and investment. Our interviews revealed that success often means different things to different providers. Moreover, an organization’s understanding of success is also something that will evolve over time. We learned a lot from API providers about pragmatic views on what API success looks like, and now we would like to translate that into some basic guidance on how to help ensure the success of providing APIs.

### What our thoughts are

Defining, measuring, and quantifying the success of API operations is not easy. As discussed above, measuring success functionally amounts to hitting a moving target. It is important to start with the basics, be realistic, and define success in a meaningful way. Adding to what has been gathered from interviews with API providers, we recommend a consideration of the following factors when it comes to defining just exactly what success is.

* **Know your resources:** Understand the resources you are making available via an API. Ensure that they are well defined and made accessible in ways that consider security, privacy, and the interests of all stakeholders. Do not just open up APIs for the sake of delivering APIs &mdash; make sure the resources are well defined, designed, and serve a purpose.

* **Manage your APIs:** API management is essential to measuring success. It is extremely difficult to define success without requiring all developers to authenticate, log, quantify, and analyze their consumption. Measuring these kinds of consumption activities helps to quantify the value produced by the API and its related platform, and an understanding of this value serves as the foundation for any API’s future success.

* **Have a plan:** There is no success without a plan. A set of plans are required to apply at the management level in order to quantify the addition of new accounts, define whether they are active or not, and understand how applications are putting resources to work. Providing a plan for how resources are made available, and how they are consumed, generates a framework to think about and measure what API success means.

* **Measure portal activity:** Treat your API developer portals as you would any other web property and actively measure its traffic. Apply data-analytic solutions to track sessions, time, and visitors, and use this information to contribute to a sales and marketing funnel that can be used to understand how developers are using portal resources. Importantly, this kind of analysis can also discover points of friction that developers may be encountering when trying to use your API platform.

* **Analyze and report:** Produce weekly, monthly, quarterly, and annual reports from data gathered across the API stack, API portal, and from social media. Developing an understanding of what is happening based upon actual data, and consistently reporting upon findings with all stakeholders in API operations, ensures both transparency of API knowledge and information access to formulate plans for growth.

* **Discuss and evangelize:** Have a strategy for taking any analysis or reporting from API operations and disseminating it amongst stakeholders. With these resources distributed, consider conducting regular on- and off-line discussions around what they mean. Work with everyone involved to understand the activity across a platform, and use these discussions to transform the understanding of success as platform awareness grows.

* **Make things observable:** Make every building block of API operations observable. Ensure that everything has well defined inputs and outputs, and consider how these can be used to better understand whether the platform is working or not. Allowing every single aspect of the platform to be able to contribute to an overall definition of what success means by providing real-time and historic data around how resources are being used can signal important insights about an API and how it might be improved.

The success of an API platform will mean different things to different groups and will evolve over time as awareness around an organization's resources grows. Know your resources, properly manage your APIs, and have a plan, but make sure you are constantly reassessing exactly what success means while having ongoing conversations with stakeholders. With more experience, you will find that API platform success becomes much more nuanced, but importantly, it also becomes easier to define once you know what it is that you want.

## Key practices for driving and sustaining adoption of APIs

After a decade of leading tech companies operating API programs, and a little over five years of government agencies following their lead, a number of common practices emerged that helped drive the adoption of APIs and support relationships between provider and consumer. We spent some time talking to API providers about their approaches, while also bringing our existing research and experience to the table, and have collected our responses and analysis below.

### What we learned

This is one area where we believe that our existing research outweighed what we learned in talking to API providers, but the conversations did reinforce what we know while also illuminating some new ways to look at operational components. Here are the key practices our interviewees provided for driving and sustaining the adoption of APIs.

* **Documentation:** Documentation is the single most important element that needs to accompany an API that is being made available. This transforms the process of learning about what an API can do from static to interactive (such as by using OpenAPI specifications) and renders the API a hands-on experience.

* **Code:** Providing samples, SDKs, start solutions, and other code elements is vital to making sure developers understand through demonstration how to integrate with APIs in a variety of programming languages.

* **Content:** Content is critical. Invest in blog posts, samples, tutorials, case studies, and anything else you think will assist your consumers in their journey. We heard over and over how important a regular stream of content is for attracting new developers, keeping active ones engaged, and putting API resources to work.

* **Forums:** Provide a forum where developers can find existing answers to their questions while also being able to ask new questions. Offering a safe, up to date, well moderated place to engage in asynchronous conversations around an API platform ensures that dialogue is always happening, which means that use and progress are in continued development.

* **Conferences:** Conducting workshops and attending relevant conferences where potential API consumers will be is an important practice in furthering the outreach of an API platform. Engage with your community &mdash; both consumers and developers &mdash; instead of just pushing content to them online.

* **Proactive:** Make sure you are proactive in operating your API platform by constantly marketing your work to developers (remember, continually attracting new attention is vital). At the same time, work to provide existing developers with what they will need based upon common practices across the API sector. Investing in developers by giving them resources they will need before they have to ask for it makes an API’s community feel alive and healthy.

* **Reactive:** While proactivity is important, an API team must also be able to react to any questions, feedback, and concerns submitted by API consumers and other stakeholders. Ensuring people do not have to wait very long for an answer to their question makes consumers, developers, and stakeholders alike feel like they are considered a relevant and important part of the API community.

* **Feedback loops:** Having feedback loops in place are essential to driving and sustaining the adoption of APIs. Without one or more channels for consumers to provide feedback, as well as responsive and attentive API providers who analyze how the feedback can fit into the overall API plan, API operations will never quite rise to the occasion.

* **Management:** Almost all API providers we talked to articulated that having a proper strategy for API management, as well as an investment in services and tooling, was essential to onboarding new consumers. Additionally, this kind of investment facilitates an understanding of how to engage with and incentivize the usage of API resources by existing users. Without the ability to authenticate, define access tiers, quantify application usage, log all activity, and report upon usage and activity across dimensions, it is extremely difficult to scale platform adoption.

* **Webinars:** For an enterprise audience, webinars were a viable way to educate new users about what an API platform offers, as well as helping to bring existing API consumers up to speed on new features. Not all communities are well-suited for webinar attendance, but for those that are, it is a valuable tool in the API toolbox.

* **Tutorials:** Providing detailed tutorials on how to use an API, understand business logic, and take better advantage of platform resources were all common elements of existing API provider options. Breaking down the features of the platform and providing simple walkthroughs that help consumers put those features to work can streamline the integration and onboarding process that users face when working with APIs.

* **Domain:** Our interviewees mentioned that having a dedicated domain or subdomain for an API developer portal significantly helped in attracting new users by providing a known location for existing developers to find the resources they are looking for.

* **Explorer:** In some cases, it is important to provide a more hands-on, visual way to explore resources available within an API rather than simply listing or describing such features in documentation. For new and particularly inexperienced users of API technologies, resources that can "connect the dots" between the API’s functional support and the actual implemented pathway of using a particular API tool can be immeasurably important in user retention.

We learned that many API providers in the public sector are actively learning from API providers in the private sector. They employ many of the same elements used by leading API providers who have been doing it for a while now. However, we also found evidence of innovation by some of the public sector API providers we interviewed, especially in the realm of onboarding and retaining new users.

### What our thoughts are

Below, we have constructed a list of common building blocks that should be considered when developing, operating, and evolving any API platform. These recommendations are the results of formalizing what we learned as part of the interview process, as well as leveraging eight years worth of research. Our objective is to give API providers the elements they need to attract and engage with new users, while also pushing existing users to be more active. We have broken down our recommendations into eleven separate areas, which are further discussed below.

#### Portal

It is important to provide a single known location where API providers and consumers can work together to integrate the offered resources into a variety of web, mobile, device, and network applications, as well as directly into other systems. Several components play into the successful adoption and consumption of APIs published to a single portal.

* **Overview:** A simple overview explaining what a platform does and clearly defining the value the API offers to consumers.

* **Getting started:** A simple series of steps that help onboard a new user so that they can begin putting API resources to work.

* **Documentation:** Interactive documentation for all APIs and schema (preferably created in OpenAPI or another interactive API specification format).

* **Errors:** A simple, clear list of all the possible errors an API consumer will encounter, starting with HTTP status codes and then proceeding to any specialized schema used to articulate when API errors occur.

* **Explorer:** A visual representation of the resources available within the API that allows consumers to search, browse, and explore all available resources without needing to know or write code. Note: it is always helpful to provide a direct link to replicate a search using the API.

These elements set the foundation for any API operations, providing the basic elements that will be needed to onboard with an API. They establish an interface for the other features that will be needed to incentivize deep and sustaining integrations with any platform.

#### Definitions

Besides the basic functionality described above, industries have turned toward a suite of machine-readable definitions to drive API integrations. Due to the ubiquity of a number of these definitions, we have collected a handful of specification formats that we recommend making a part of the base of any API operations.

* **OpenAPI:** An interactive documentation standard that describes the functionality of an API in a machine-readable way.

* **Postman:** A standard collection that provides a transactional, runtime-oriented definition of the feature interface of an API for use in client tooling.

* **JSON Schema:** A widely used specification that describes the objects, parameters, and other structural elements of the consumption of API resources.

* **APIs.json:** A discovery document that provides a machine-readable index of API operations with references to the portal, documentation, OpenAPI, Postman, and other building blocks of an API platform.

#### Code

It is common practice for API providers to invest in a variety of code-focused resources to help jumpstart the onboarding process for API developers. This reduces the number of technical steps necessary for the technology to successfully integrate with other platforms. Here are the building blocks we recommend considering when crafting the code portion of any developer outreach strategy.

* **Github/Gitlab:** Use a social coding platform to manage many of the technical components used to support API developers.

* **Samples:** Publish simple examples of making individual API calls in a variety of programming languages.

* **SDKs:** Provide more comprehensive software development kits in a variety of programming languages for developers to use when integrating with API resources.

* **PDKs:** Provide platform development kits that help developers integrate with existing solutions they may already be using as part of their operations.

* **MDKs:** Provide mobile development kits that help jumpstart the development of mobile applications that take advantage of a platform APIs.

* **Starters:** Publish complete applications that provide starter kits that developers can use to jumpstart their API integrations.

* **Embeddables:** Provide buttons, badges, widgets, and bookmarklets for any API consumer to use when quickly integrating with API resources.

* **Spreadsheets:** Offer spreadsheet connectors that allow API consumers to use platform APIs within Microsoft Excel and Google Sheets.

* **Integrations:** Invest in a suite of existing integrations with other platforms that API consumers can take advantage of, providing low-code or no-code solutions for integrating with APIs.

While we have presented a variety of code-related resources, we want to point out the caveat that these tools should only be employed if an organization possesses the resources to properly maintain and support them. These elements can provide some extremely valuable coding solutions for developers and consumers to put to work, but if not properly done, they can also quickly become a liability, driving developers away.

#### Event-driven

In addition to simpler request-and-response delivery and documentation methods, we also recommend thinking about the following event-driven possibilities, which can also be used to incentivize deeper engagement and workflow with an API.

* **Webhooks:** These can provide ping and data push opportunities, which allow API consumers to be notified when any event occurs across an API platform.

* **Streams:** Providing high-level or individual streams of data allow for long-running HTTP or TCP connections with API resources.

* **Event types:** In many cases, it is helpful to publish a list of the types of possible API events, as well as opportunities for subscribing to webhook or streaming channels.

* **Topics:** Similarly, developers and consumers alike may find a published list of platform-related topics useful, particularly one that allows API consumers to search, browse, and discovery exactly the topical channels they are interested in.

These event-based tools help augment existing APIs and make them more usable by API consumers at scale. They facilitate a meaningful application experience for end-users, allowing them to stay tuned to specific topics. This in turn fine-tunes the experience for developers,which further drives adoption, ultimately establishing more loyal consumers at the API integration and application user levels.

#### Management

One of the cornerstones for defining, quantifying, and delivering successful API onboarding and engagement is API management. The following list contains some core elements of API management that should be considered as any API provider is planning, executing, and evolving their operational strategy.

* **Authentication:** Providing clear options for onboarding using Basic Auth, API Keys, JWT, or OAuth keeps things standardized, well-explained, and frictionless to implement.

* **Plans/tiers:** Establishing well-defined tiers of API consumers in terms of how they access all available API resources can inform the provision of structured plans that define how an API’s resources are being utilized.

* **Applications:** Individual applications should be at the center of consumer API engagement. In particular, applications that help onboard new users so that they can begin consuming API resources are imperative.

* **Usage reporting:** Tools and metrics that provide real-time and historical data, as well as access to multi-dimensional reporting across all API consumers is useful in analyzing the API’s usage and performance. This information can be helpful to developers in defining the stage of their API journey, as well as any additional resources they might wish to consider.

There are many other aspects of API management, but these building blocks reflect the consumer-facing elements that help onboard new users and drive increased engagement with existing consumers. API management is an area in which API providers should not be reinventing proven methods that already work: the best practices established over the last decade by leading API providers already account for strong engagement and retention levels for users and service providers.

#### Communications

Engagement is important for consumers not only with the tools of the API, but the communications and news surrounding the API. Streams of information across multiple channels can help unite a communications strategy for any API platform. We have collected the best examples of such information feeds below.

* **Blog:** An active blog with an Atom feed, one for each individual API and/or overall platform.

* **Twitter:** A dedicated Twitter account for the entire API platform, providing updates and support.

* **GitHub:** A GitHub organization dedicated to the platform, with accounts for each API team member. The organization leverages the platform for content as well as code management.

* **Reddit:** A helpful forum for answering questions, sharing content, and engaging with consumers on the social bookmarking platform.

* **Hacker News:** Another helpful discussion board for answering questions, sharing content, and engaging with consumers.

* **LinkedIn:** A business social network enterprise devoted to engaging with consumers. An established LinkedIn page for the platform can be useful for regularly publishing content, as well as engaging in conversations via the platform.

* **Facebook:** Similar to LinkedIn, a Facebook page for the platform is helpful in engaging with API consumers via their social media presence. It can be used to regularly publishing content and engage in network-broadcast conversations via social platforms.

* **Press:** A platform section detailing the latest releases, as well as a feed that users can subscribe to in order to receive a regular stream of news on the platform.

A coherent communication, content, and social media strategy will be the number one driver of new users to the platform while also keeping existing developers engaged. These communication building blocks provide a regular stream of information and signals that API consumers can use to stay informed and engaged while putting API resources to use in their applications.

#### Direct support

Besides communication, direct support channels are essential to completing the feedback loop for the platform. There are a handful of common channels API providers use to provide direct support to API consumers, allowing them to receive support from platform operations. We recommend the following selections.

* **Email:** Establish a single, shared email address for the platform in which all platform support team can provide assistance.

* **Twitter:** Provide support via Twitter, pushing it beyond just a communication channel and making it so that API consumers can directly interact with the platform team.

* **GitHub:** Do not just use GitHub for code or content management: leverage individual team member accounts to actively support using GitHub issues, wikis, and other channels the social coding platform provides.

* **Office hours:** Provide regular office hours where API consumers can join a hangout or other virtual group chat application in order to have their questions answered.

* **Webinars:** Provide regular webinars around platform specific topics, allowing API consumers to engage with team members via a virtual platform that can be recorded and used for in-direct, more asynchronous support in addition to live feedback.

* **Paid:** Provide an avenue for API consumers to pay for premium support and receive prioritization when it comes to having their questions answered.

With a small team, it can be difficult to scale direct support channels properly. It makes sense to activate and support only the channels you know you can handle until there are more resources available to expand to new areas. Ensuring that all direct support channels are reactive in terms of communication will help deliver value by bringing the feedback loop back full circle.

#### Indirect support

After direct support options, there should always be indirect/self-support options available to help answer API consumers’ questions. Such options allow users to get support on their own while still leveraging the community effect that exists on a platform. There are a handful of proven indirect support channels that work well for public as well as private API programs.

* **Forums:** Provide a localized, SaaS, or wider community forum for API consumers to have their questions answered by the platform or by other users within the ecosystem.

* **FAQ:** Publish a list of common questions broken down by category, allowing API consumers to quickly find the most common questions that get asked. Regularly update the FAQ listing based on questions gathered using the platform feedback loop(s).

* **Stack Overflow:** Leverage the question and answer site Stack Overflow to respond to inquiries and allow API consumers to publish their questions, as well as answers to questions posed by other members of the community network.

Indirect, self-service support will be essential to scaling API operations and allowing the API team to do more with less. Outsourcing, automating, and standardizing how support is offered through the platform can make API support available 24 hours per day, turning it into an always-available option for motivated developers to find the answers they are looking for.

#### Resources

Beyond the documentation and communication, it is helpful to provide other resources to assist API consumers in onboarding and to strengthen their understanding of what is offered via the platform. There are a handful of common resources API providers make available to their consumers, helping to bring attention to the platform and drive usage and adoption of APIs.

* **Guides:** Providing step by step guides covering the entire platform, or individual sections of the platform, helps consumers understand how to use the API to solve common challenges they face.

* **Case studies:** Examples such as real-world case studies of how companies, organizations, institutions, and other government agencies have put APIs to work in their web, mobile, device, and network applications can help demonstrate the variety of functions that an API platform can perform.

* **Videos:** Make video content available on YouTube, and other platforms. Providing video walkthroughs of how the APIs work and the best way to integrate features into existing applications can demystify the process of onboarding with API technologies.

* **Webinars:** While webinars can be a helpful source of information to API consumers trying to understand specific concepts, maintaining and publishing an archive of webinars can serve as a historic catalog of such searches, which can provide targeted Q&A for how to put API platforms to work.

* **Presentations:** Provide access to all the presentations that have been used in talks about the platform, allowing consumers to search, browse, and learn from presentations that have been given at past conferences, meetups, and other gatherings.

* **Training:** It can be immensely helpful to invest in formal curriculum and training materials to help educate API consumers about what the platform does. This provides a structured approach to learn more about the APIs and gives developers access to comprehensive training materials users can tap into on their own schedule.

Like other areas of this recommendation, these resource areas should only be invested in if an organization has the resources available to develop, deliver, and maintain them over time. Providing additional resources like guides, case studies, presentations, and other materials help further extend the reach of the API platform, allowing the API team behind operations do more with less, as well as reach more consumers with well constructed, self-service resources that are easy to discover.

#### Observability

One important attribute of API platforms that successfully balance attracting new users and creating long term relationships is platform observability. Being able to understand the overall health, availability, and reliability of an API platform allows API consumers to stay informed regarding the services they are incorporating into their applications. There are several key areas that contribute to the observability of an API platform.

* **Roadmap:** A simple list of what is being planned for the future of a platform, one that provides as much detail and ranges as far into the future as possible.

* **Issues:** A document of any open issues that exist, allowing API consumers to quickly understand if there are any open issues that might impact their applications.

* **Status:** A dashboard that describes the health of the overall platform, as well as the status of each individual API being made available via the platform.

* **Change log:** A simple list of what has changed on a platform, taking the roadmap and issues that have been satisfied and rolling it into a historical registry that consumers can use to understand what has occurred.

* **Security:** Share information about platform security practices and the strategies used to secure platform resources, and share the expectations held of developers when it comes to application security practices.

* **Breaches:** Be proactive and communicative around any breaches that occur, providing immediate notification of the breach and a common place to find information regarding current and historic breaches on the platform.

Observability helps build trust with API consumers. In order to develop this trust, platform providers have to invest in APIs in ways that make consumers feel like the platform is stable and reliable. The less transparent that the elements of the platform are, the less likely that API consumers are going to expand and increase their usage of services.

#### Real-world presence

The final set of recommendations centers on maintaining a real-world presence for the platform. It is important to ensure that the platform does not just have a wide online presence, but is also engaging with API consumers in a face-to-face capacity. There are a handful of ways that leading API providers get their platforms face-time with their community.

* **Meetups:** Speaking at and attending meetup events in relevant markets.

* **Hackathons:** Throwing, participating in, and attending hackathon events.

* **Conferences:** Speaking, exhibiting, and attending conferences in relevant areas.

* **Workshops:** Conducting workshops within the enterprise, with partners, and the public.

These four areas help extend and strengthen the relationship between the API platform provider and consumers.

## How API developer sandboxes are used to drive adoption

One of the more interesting and forward-thinking aspects of this research is around the delivery of sandbox development, labs, and virtualized environments. Providing a non-production area of a platform where developers can play with API resources in a much safer environment than a live production area can encourage creativity and innovation as well as exploration of the API’s resources.

### What we learned

Some of the API providers we interviewed for this proposal had sandbox environments. Their insights into the merits of these environments provided us with some ideas to reduce friction for new developers when onboarding, as well as to help certify applications as they mature with their integrations. Here is what we learned about sandbox environments from the API providers we talked to.

* **Sandboxes are used:** Sandbox environments are used, and they do provide value to the API integration process, making them something all API providers should be considering.

* **Sandboxes are not default:** Sandboxes are not a default feature of all APIs but have become more critical when PII (personally identifying information) and other sensitive resources are available.

* **Data is virtualized:** It was enlightening to see how many of the API providers we talked to provided virtualized data sets and complete database downloads to help drive the sandbox experience.

* **Doing sandboxes well is difficult:** We learned that providing sandbox environments that reflect the production environment is, quite simply, hard. It takes significant investment and support to make it something that will work for developers.

* **Safe onboarding:** Sandbox environments allow for the safe onboarding of developers and their applications. This helps ensure that only high-quality applications enter into a production environment, which protects the interests of the platform as well as the security and privacy of end-users.

* **Integrated with training:** We learned how sandbox environments should also be integrated with other content and training materials. This facilitates access for API consumers to test out the training materials they need while also directly learning about the API.

* **Leverage API management:** It was interesting to learn the role that API management plays in being able to deliver both sandbox and production environments. API gateways and management solutions are used to help mock and deliver virtualized solutions, but also to manage the transition of applications from development to a production environment.

Talking to API providers, it was clear that sandboxes provided value to their operations. It was also clear that they aren't essential for every API implementation and took a considerable investment to do right. API virtualization is a valuable tool when it comes to engaging with API consumers, and it is something that should be considered by most API providers, but it should be approached pragmatically and realistically, with an awareness of both the costs as well as the benefits of moving from transition to production environments.

### What our thoughts are

Sandboxes, labs, and virtualized environments are commonplace across the API sector but are not as ubiquitous they should be. We commend the presence of virtualized building blocks for any API that is dealing with sensitive data. A sandbox should be a default aspect of all API platforms, but should be especially applied to help ensure quality control as part of the API journey from development to production. Here are some of the building blocks we recommend when looking at structuring a sandbox environment for a platform.

* **Virtualize APIs:** Provide virtualized instance of APIs and a sandbox catalog of API resources.

* **Virtualize data:** Provide virtualized and synthesized data along with APIs in order to create as realistic an experience as possible.

* **Virtualized instances:** Consider the availability of virtualized instances of an API as computable instances on major cloud platforms, allowing for the deployment of sandboxes anywhere.

* **Virtualized containers:** Consider the availability of virtualized instances of an API as containers, allowing API sandboxes to be created locally, in the cloud, and anywhere containers run.

* **Bake into onboarding:** Make a sandbox environment a default requirement in the API onboarding process, providing a place for all developers to learn about what a platform offers and pushing applications to prove their value, security, and privacy before entering a production environment.

* **Applications:** Center the sandbox experience on the application by certifying it meets all the platform requirements before allowing it to move forward. All developers and their applications get access to the sandbox, but only some applications will be given production access.

* **Certification:** Provide certification for both developers and applications. Establishing a minimum bar for what is expected of applications before they can move into production helps developers understand what it takes to move an application from sandbox to distribution, which ensures a high-quality application experience at scale.

* **Showcase:** Always provide a showcase for certified applications as well as certified developers. Allow for the browsing and searching of applications and developers, while also highlighting them in communications and other platform resources.

When it comes to API resources that contain sensitive data, virtualized APIs, data, and environments are essential. They should be a default part of ensuring that developers push only high-quality applications to production by forcing them to prove themselves in a sandbox environment first.

## Types of metrics for measuring adoption and making decisions

This area of our research overlaps somewhat with the earlier section on measuring success, but here, we provide a more precise look at what can be measured to help quantify success while also ensuring that findings are used as part of the decision-making process throughout the API journey.

### What we learned

Our interviews reminded us that it is useful to consider that not all API providers have a fully fleshed out strategy for measuring activity across their platforms. However, we did come away with some interesting lessons from those providers that were using metrics to drive API decision making.

* **Look at it as a funnel:** Treat API outreach and engagement as a sales and marketing funnel. Attract as many new users as you can, but then profile the target demographic to try to understand who they are and what their working objectives comprise. From there, devote efforts to incentivizing users to "move down the funnel" through the sandbox environment and eventually to production status. In short, treat API operations like a business and platform users like they are customers.

* **Do not have formal metrics:** It was illuminating to also learn that some providers felt that having an overly formal metrics strategy might constrain developer outreach and engagement. Providing words of caution when it comes to measuring too much, as well as only examining data when it comes to making critical decisions, can keep outreach efforts more constructively interacting with API consumers regarding their needs.

* **API keys registered:** For data accessibility purposes, it is worthwhile to ensure that all developers have an application and API key before they can access any API resources. Requiring all internal, partner, and eternal developers to pass along their API key with each API call allows all platform activity to be measured, tracked, and used as part of the wider platform decision-making process.

* **Small percentage of users:** We also heard that it is common for a small percentage of the overall platform users to generate the majority of API calls to the platform. This makes it important to measure activity on the platform in terms of which users are the most salient (and thereby driving the majority of value on a platform).

* **Amount of investment:** Importantly, the usage rates of a platform’s resources can provide a strong justification for investing more resources into the platform’s success, making tracking that data of paramount importance. This transforms investment into a data-driven decision that responds to the actual needs of the platform.

The interview portion of our research provided a valuable look at how API providers are measuring activity across their platforms. Data and metrics are not only being used to define success, but are also used as part of the ongoing decision making process around the direction API providers take their platform, particularly when it comes to measuring adoption of API resources across a platform.

### What our thoughts are

When it comes to measuring adoption and understanding how API consumers are putting resources to work, we recommend starting small. Activity tracking is something that will change and evolve as the organization develops a better understanding of platform resources and the interests of internal stakeholders, partners, and 3rd party consumers. These are just a handful of areas we recommend collecting data on to begin with.

* **Traffic:** Measure and understand traffic (network and otherwise) across the platform developer portal.

* **New accounts:** Track and profile all new accounts signing up for API access.

* **New applications:** Track and profile all new applications registered for access.

* **Active applications:** Measure and track the usage of the active platform applications.

* **Number of API calls:** Understand how many APIs are being called in different dimensions.

* **Conversation:** Measure all conversation happening across the platform and use these estimates to develop awareness.

* **Support:** Measure all support activity in order to pinpoint the needs of API consumers.

* **Personas:** Quantify the different types of consumers who are putting a platform to use.

Begin here when it comes to tracking: develop an awareness of the community and get to know what is important. Then expand from there. Add and remove the metrics that make sense for your organization without tracking metrics for no reason (i.e. all tracking should add value to the API platform or its decision making process).

## Structuring and staffing outreach programs

Each platform will have its own mandate for how API programs should be staffed, but there are some common patterns that exist across the space.

### What we learned

The API providers we talked to had a lot to share about what it takes to staff their operations, including their structures (or in a few cases lack thereof!).

* **Dedicated evangelist:** Make sure there is a dedicated evangelist to help talk-up and support the platform.

* **Include marketing:** Include the marketing team in conversations around amplifying the platform and its presence.

* **Provide support:** Invest in the resources to support all aspects of the platform effectively, not just those that are consumer-facing or particularly visible.

* **Conduct regular calls:** Conduct regular calls with internal, partner, and external stakeholders in order to bring everyone together to discuss the progress of the platform.

* **Use a CRM for automation:** Put a CRM to use when it comes to tracking and automating outreach efforts for the platform. Do not reinvent the wheel; leverage an existing service to track all of the details that can be automated.

* **Include other teams:** Do not just invest in an isolated API team; make sure other teams across the organization are included in the API conversation.

* **Develop an in-person presence:** Make sure to obtain human resources that can be sent to meetups, conferences, and other in-person events so that the organization can expanding and strengthening the presence of the platform.

* **Speak to leadership:** Regularly invest time to report platform results and progress to leadership, making sure they understand the overall health and activity of the platform.

We learned that a dedicated evangelist is essential, as well as significant investments in marketing and support. It was good to hear how important in-person events were, supporting stakeholders and leadership when it came to overall outreach efforts. Overall, the conversation we had reflects what we have been seeing across the landscape with other public and private sector providers.

### What our thoughts are

Echoing what we heard from our conversations with API providers, we have some advice when it comes to structuring and allocating resources to API efforts. This is a tough area to generalize because different platforms will have different needs, but there are well established traits of successful API providers, with the following characteristics making the top of the list.

* **Dedicated program:** Establish a formal program for overseeing API operations across an organization to make sure it gets the attention it needs.

* **Dedicated team:** Allocate a dedicated team to the API program and platform to represent its needs and push for its continued advancement.

* **Business involvement:** Make sure to involve business groups in the conversation, bringing them in as stakeholders to give their thoughts on the organization’s API program.

* **Marketing involvement:** Make sure marketing teams play an influential role in amplifying the message coming from a platform. This is especially important to ensure that a platform does not just speak to developers, but to consumers and users as well.

* **Sales involvement:** Ensure that a platform has the sales resources to actually close deals when necessary. This ensures that a platform has continuing end-user participation and the resources it needs to function. Remember, though, that sales is not always about selling commercial solutions.

* **External users:** Make a place for external actors to take part in advancing the API-relevance conversation. External users can often rise to highly influential levels within a community, and this influence can be put to work assisting with outreach efforts (but only if the culture of a platform allows for it).

* **Contractors:** Consider how vendors and contractors will be contributing to the overall outreach effort by creating a means for vendors to assist with logistics and communication channels, allowing the core team to focus on moving the platform forward while contractors tackle the details.

It will take dedicated resources to move the API conversation forward at a large organization. However, it will also take the involvement of other stakeholders to get the business and political capital to legitimately spark the platform initiative. How a program gets structured, and the amount of resources dedicated to evangelism, communication, support, and other critical areas will set the tone for the platform and determine the overall health and viability of the API.

## Anti-patterns

One unorthodox part of our research involved asking API providers about the things they felt would contribute to the failure of their API platform. Below, we have collected some thoughts about the "anti-patterns" that might generate friction on the platform, chase developers away, or make things harder for everyone involved.

### What we learned

The API providers we talked to had plenty of ideas for how to run developers off and make integration with platform resources harder. We’ve provided a list of things API providers can avoid when operating their platforms and when reaching out to developers. (To be clear, each of the things presented in the list below is a bad practice &mdash; the bolded phrase is a "mistake" an API provider could make, and the text that follows further explains the nature of the poor practice.)

* **Do not take a build it and they will come approach:** Building API operations with tremendous resource investment before consumers ask for certain functions or resources is a poor way to achieve stable platform growth.

* **Do not reach out to developers:** Not being proactive about contacting developers makes it hard to build working relationships that clarify development needs.

* **Hand built documentation:** Providing hand-crafted, bloated, or out of date documentation is not only difficult to maintain, it reduces the value of the API to developers.

* **Breaking changes:** Changing the platform too often or too fast may introduce too many breaking changes for developers to deal with, reducing the platform’s effectiveness.

* **Do not communicate:** Not communicating platform operation updates leaves developers in the dark about what is happening with the very tool they rely on.

* **Do not listen to your developers:** Not listening to developers or including their feedback in the roadmap is sure to eventually run developers off.

* **Do not measure happiness:** Measure everything except for the happiness of developers, because such a metric (if you can even operationalize it as such) will never really lead to understanding if they are truly happy about how the platform is being run.

* **Gated content:** Putting documentation, content, and other resources behind a login or paywall, or else restricting what developers have access to, is a great way to get developers to ignore your platform.

* **Do not provide a developer edition:** Avoid providing developers with a set of APIs to play with simply for the sake of "experimentation." Without being able to see the value of real, production-strength applications, users will not be building their projects on the platform any time soon.

* **Do not reach out to partners:** Focusing on general developers without identifying and reaching out to potential partners can rob a platform of trusted allies, who might have otherwise facilitated operations, integrations, and even broader application development.

It was clear that the API providers we interviewed were aware of the pitfalls that could jeopardize an API’s success. They provided us with a comprehensive look at what an organization should avoid when it comes to operations and investment.

### What our thoughts are

Adding to what the API providers mentioned during their interviews, we have some additional recommendations based on some common deficiencies we have seen. These are the areas all API providers should be investing in to strengthen their operations and to avoid the anti-patterns highlighted so far.

* **Documentation:** Make documentation a priority by keeping it simple, updated, and interactive for developers.

* **Entry level:** Ensure there is entry-level access to a platform, allowing developers to onboard without commitments or procedural friction.

* **Communication:** Develop a robust communication strategy for ensuring a platform has a regularly updated stream of new content about what is happening.

* **Support:** Ensure that a platform is supported, and that API consumer's questions are being answered in a timely manner.

* **Feedback loops:** Make sure that feedback loops exist and are strengthened by communication, support, and actually listening to developers’ needs.

* **Evangelism:** Invest in evangelism amongst leadership, partners, 3rd party developers and all stakeholders to make sure the platform is always being spoken for.

* **Observability:** Insist on observability for all components involved in operating a  platform to maximize measurements and comprehension of the system.

* **Partners:** Seek out partners. They are critical to taking the platform to the next level. Cultivate developers and applications, and produce strong partners who can help take things into the future.

We see anti-patterns as deficient areas of platform operations that can largely be avoided with proper time and resource investments.

## Future plans

We concluded our provider interviews with a few questions on what they believe the future holds. Their visions for their growth and development can serve as strong examples and recommendations for what other platforms can include in their own plans.

### What we learned

It was interesting to learn about the desires our interviewees possessed when it came to future investment in their platforms. We have generated this short list of areas that API providers can think about when it comes to building out their roadmap.

* **Go with what works:** Make sure to continue investing in and scaling the parts of the platform that are earning attention for their success.

* **Product excellence:** Emphasize product excellence over simply responding to new developments.

* **Marketing and evangelism:** It has never bad to augment marketing efforts to broadcast information about a platform.

* **Attend conferences:** Increase the platform's presence at relevant conferences.

* **Throw hackathons:** Invest in throwing hackathons to encourage developers to do more.

* **Conduct conferences:** Invest in and produce conferences that support the API community.

* **Building community:** Do what it takes to keep building and strengthening the community.

* **Publish more to GitHub:** Publish more code, content, and other resources to the GitHub or other version control platform.

* **Make connect more discoverable:** Work to make resource more discoverable so that developers can find what they need.

* **Publish to code.gov:** Publish code to code.gov, making code open source and available as part of the wider government effort to make resources available.

The common theme we heard from API providers was that allocation for future investment should be spent reinforcing the building blocks already in place that made the API platform successful in the first place. We learned a lot about the motivations and visions of the API providers we interviewed, which helped shape our recommendations for what could be next.

### What our thoughts are

With so many possibilities for the path that an API platform’s development can take, it is easy to get caught up in the next step without reflecting on the fact that what is next usually involves reinforcing what is happening now. Our recommendations involve focusing on what matters, and not just what is new, with the following areas of investment:

* **Continue investing in what works:** To once again echo our interviewees, continue to invest in building what is already working. Further develop the API platform and its associated vision conversation by looking to what already exists rather than looking for new ways to get things done.

* **Excellence and mastery:** Invest in perfecting the process, refining how things get done, and operating the platform in a way that benefits everyone involved. Doing it well, and do it it right, will pay off in the long run.

* **Involve other teams:** Expand involvement with the API to include other teams across an organization. This helps distribute the workload of  operating the API platform and allows all subgroups within an organization to have a voice in the future of the API.

# Conclusion

To produce this research, we spoke with leading API providers from across the public and private sector while also leveraging eight years of analysis gathered from directly studying the API sector. This research should provide a wealth of options to consider when it comes to helping the VA be more effective in reaching out to developers. However, this is not meant to be a complete list of building blocks to consider, but rather, is meant to present a selection of proven elements that can be implemented with the right teams to execute. While things like API documentation are critical, there is no single element of this research that will make or break API outreach efforts; when the right elements are combined and executed properly, the results can be extremely positive.

This research reflects the experience of platform providers like SalesForce who have been iterating upon their API platforms and engaging with consumers since 2001. It also follows the lead of next generation providers like Twilio who have been making developers happy for almost a decade, while also managing to take their company public. It looks at how CMS, Census, and FEC are approaching the outreach around their API programs, bringing in the unique perspective of federal agencies who are finding success with their APIs. Finally, the insights gathered across these API providers is organized, augmented, and rounded off with insight gathered by the API Evangelist as part of research on the business of APIs, research that has been ongoing since July of 2010.

We want to end this look at developer outreach by emphasizing once again that this is a journey. While there are many common patterns in play across the API sector, no two API platforms are the same. The types of developers attracted to a platform, as well as the ones that remained engaged, will vary depending on the organization, the types of resources being made available, and the tone set by the teams(s) operating the platform. It is up to the VA to decide what type of platform they will operate and what kind of tone they will set when reaching out to developers. There will not be any single right answer to how the VA should be reaching out to new developers, but with the right amount of planning, communication, support, and observability, the VA will undoubtedly find its footing.

# Appendix A: interview questions

For each interview, we asked the following questions:

1. What role do you play within the organization?

2. What is the purpose and scope of your API developer outreach program?

3. What does success look like for you?

4. What are the key elements or practices (e.g, documentation, demos, webinars, conferences, blog posts) that you're using to drive and sustain effective adoption of your API(s)?

5. Do you make use of an API developer sandbox to drive and sustain adoption? If so, please describe how you've designed that environment to be useful and usable to developers.

6. What types of metrics do you use to measure adoption effectiveness and to inform future decisions about how you evolve your program?

7. How is your outreach program structured and staffed? How did it start out and evolve over time?

8. Imagine that you’re charged with ensuring the complete failure of an API developer outreach program. What things would you do to ensure that failure?

9. What big ideas do you have for evolving your outreach program to make it even more effective?

10. Any other thoughts you’d like to share? If so, please feel free!

# Appendix B: CMS Blue Button API interview notes

## 1. What role do you play within the organization?

Product Manager.

## 2. What is the purpose and scope of your API developer outreach program?

CMS is offering several APIs. One approach is put it out there and hope they come. Second approach is leveraging APIs on the Socrato platform and hoping there’s adoption. Third approach is partnership agreements with various private partners.

Purpose of the Blue Button outreach program is to drive adoption of the API.

## 3. What does success look like for you?

Worked with various stakeholders to define the metrics in terms of value. For example, number of unique organizations who are experimenting with the API. Originally set a target of 500 organizations. Up to 450 currently. Use it as a proxy measurement of value. Not sure how beneficiaries are benefiting yet, but adoption is proxy indicator.

Also measuring number of beneficiaries who have linked their data to Blue Button API &mdash; for example, Google Verily.

## 4. What are the key elements or practices (e.g, documentation, demos, webinars, conferences, blog posts) that you're using to drive and sustain effective adoption of your API(s)?

Documentation is the first key element. Originally hosted documentation on GitHub pages, but now using bluebutton.cms.gov.

Had challenges over the year making clear what Blue Button is, value, etc.

Relaunched during recent HIMSS conference. Resulted in a number of sign-ups from press.

Set up a blog to provide a getting started guide, how sign-up works, etc. Working pretty well.

Assigned a designated Developer Evangelist, who pushes content, participates in forums, and hits the niche conference circuit.

## 5. Do you make use of an API developer sandbox to drive and sustain adoption? If so, please describe how you've designed that environment to be useful and usable to developers.

Sandbox has been a big part. Have a synthetic dataset. In healthcare, this is essential from a privacy standpoint.

Have had challenge with synthetic data in terms of making them realistic.

Have a streamlined process for accessing and onboarding into environment. Experience is not currently great, and working on improving.

Developer portal is only for sandbox environment. No portal for production, so disjointed at this point.

## 6. What types of metrics do you use to measure adoption effectiveness and to inform future decisions about how you evolve your program?

Look at the adoption as a funnel. That has helped to drive a culture shift around how folks think about metrics and the role they play.

Top of funnel is evangelism/traffic/etc., portal sign-ups, registered an app, and how many of those who have registered made API calls.

## 7. How is your outreach program structured and staffed? How did it start out and evolve over time?

Have a developer evangelist.

Periodically, team gets on phone with developer evangelist and talks about ideas for building awareness and driving adoption.

Using email + CRM tools for outreach. Trying to improve marketing automation.

## 8. Imagine that you’re charged with ensuring the complete failure of an API developer outreach program. What things would you do to ensure that failure?

Don’t take a "build it and they will come" approach.

Not acting quickly enough on insights gained from the funnel process, including reaching out to individuals to help them through the process (i.e., proactive outreach).

## 9. What big ideas do you have for evolving your outreach program to make it even more effective?

Double down on what’s working to incrementally grow &mdash; conferences, webinars, etc.

Serving as a blueprint for other organizations, particularly at a state & local level.

## 10. Any other thoughts you’d like to share? If so, please feel free!

N/A

# Appendix C: Census interview notes

## 1. What role do you play within the organization?

Developer engagement lead, serving as the comms arm for Census’ API efforts. First-line of defense for any developer engagement. Participate in hackathons, etc.

Also working on CitySDK. This was in response to the observation that developers were having trouble working with Census APIs. SDK currently not being maintained because lost lead developer and funding for it. Personally learning how to develop in order maintain myself.

## 2. What is the purpose and scope of your API developer outreach program?

Save developers time and help them understand the nuances of Census data and how to use the data. Engage in communications and help inform the development of API products.

## 3. What does success look like for you?

Happy developers.

## 4. What are the key elements or practices (e.g, documentation, demos, webinars, conferences, blog posts) that you're using to drive and sustain effective adoption of your API(s)?

Proactive engagement: work on driving the government’s engagement in National Day of Civic Hacking in collaboration with NASA and Code for America. Hackathons are great for user research and testing new features.

Reactive: have a Slack and Gitter channel.

Haven’t tried blog posts yet. Thinking about interviewing developers who are using APIs and turning their stories into blog posts. Haven’t been able to get legal approval yet for that.

Being able to figure out what data Census has and how that data can be made available to developers is key.

Webinars are good, especially those focused on showing how to use Census data and build something simple using the API.

Use a data search tool &mdash; [American FactFinder](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml); developers can use this to find out what variables they are interested in and then trace that data back to an API that they can use to access programmatically.

## 5. Do you make use of an API developer sandbox to drive and sustain adoption? If so, please describe how you've designed that environment to be useful and usable to developers.

No, haven’t done anything like yet. Have a discovery tool that is part of the API.

## 6. What types of metrics do you use to measure adoption effectiveness and to inform future decisions about how you evolve your program?

Initially focused on number of API keys registered. Starting focusing on metrics of use. A small number of users drive 80% of the API use. Developers tend to move data into their environment for performance purposes (e.g., caching). Plus, they worry about government shutting down and data not being accessible.

## 7. How is your outreach program structured and staffed? How did it start out and evolve over time?

One person focused on outreach.

Entire team dedicated to building the APIs and making the data available and accessible. Each product gets its own endpoint; there are about 30 now and planning to do 70 more.

## 8. Imagine that you’re charged with ensuring the complete failure of an API developer outreach program. What things would you do to ensure that failure?

Create terrible, hand-rolled documentation with a lot of pictures; don’t give developers a channel to communicate; don’t listen to them; don’t give them a way to test out data before granting a key; and don’t have metrics for measuring developer happiness and just focus on usage metrics.

## 9. What big ideas do you have for evolving your outreach program to make it even more effective?

Focus more on product excellence and marketing. A lot of developers don’t like being pushed to. Most developers go to hackathons for social interaction and career progression, not because they love working with your data and using your APIs.

## 10. Any other thoughts you’d like to share? If so, please feel free!

Instead of trying to focus too much on attracting random developers, focus on the developers who are engaged now and reach out to them. Would like to introduce a CRM system to help manage these relationships better.

Learned it’s important to grab as much data during the registration process in order to gain better insight into developer intent, behavior, and characteristics. Found it’s very hard to get information after developers have gained access; they don’t typically respond to email requests for information.

Hackathons, etc. are huge investment of time and resources.

Biggest lesson learned is to always focus on the principle of how to make it as easy for the developers as possible.

Make heavy use of GraphQL because it’s introspective and helps developers understand the API in greater detail. Like GraphQL because it can evolve without breaking things.

# Appendix D: OpenFEC interview notes

## 1. What role do you play within the organization?

Tech Lead at FEC, mostly focused on OpenFEC. Involved in FEC campaign finance data for ten years.

## 2. What is the purpose and scope of your API developer outreach program?

Don’t have an overarching formal approach in place yet, but do provide support to developers through a variety of channels when they reach out.

## 3. What does success look like for you?

Number one measure of success is providing developers accurate data, and making sure that is available at all times. Also making sure that developers can find the data that they need.

## 4. What are the key elements or practices (e.g, documentation, demos, webinars, conferences, blog posts) that you're using to drive and sustain effective adoption of your API(s)?

Don’t have a formally developer outreach program. Have small team of developers, designers, content designers, and product managers.

Would like to be more proactive about engaging.

Do have some mechanisms for getting feedback. For example, the project is open source, which encourages developers to add issues, contribute, etc. Developers can send emails to [apiinfo@fec.gov](mailto:apiinfo@fec.gov). Existing team tries to get back as quickly as possible. Would like to have a ticket management system to help facilitate workflow around support. Do have a google group in which community of developers can ask and answer questions.

Do have a developer page. And work hard to keep those up-to-date.

Use GSA’s API umbrella to manage users, which handles rate limiting and caching.

Have a try-it-out feature on developer page powered by Swagger API, and can just put params in to see how the API works.

## 5. Do you make use of an API developer sandbox to drive and sustain adoption? If so, please describe how you've designed that environment to be useful and usable to developers.

Don’t have a sandbox, but do provide instructions for setting up locally. And also provide a sample database that can be copied. Since all data is public, don’t have to worry about PII. Amazon provides a free sandbox environment to anyone with .gov domain that can be used to set-up a test environment.

## 6. What types of metrics do you use to measure adoption effectiveness and to inform future decisions about how you evolve your program?

Don’t have formal metrics. Using the GSA API Umbrella, there is some data available, not currently using that data to drive decisions.

## 7. How is your outreach program structured and staffed? How did it start out and evolve over time?

The existing team of developers, etc. are providing outresearch support.

## 8. Imagine that you’re charged with ensuring the complete failure of an API developer outreach program. What things would you do to ensure that failure?

Making breaking changes and don’t tell anyone; not responding to and fixing data quality issues, which would undermine the credibility of the API; couldn’t serve the data in an efficient manner.

## 9. What big ideas do you have for evolving your outreach program to make it even more effective?

Have discussed holding a hackathon or conference, similar to what Blue Button is doing.

Holding a quarterly developer conference call to starting answering questions and discuss ideas.

Regardless of activity, starting to build a community.

Pushing our code to code.gov to increase awareness.

## 10. Any other thoughts you’d like to share? If so, please feel free!

There are commercial restrictions around the use of open FEC data.

# Appendix E: Salesforce interview notes

## 1. What role do you play within the organization?

Vice President of Developer Relations. My team doesn’t create APIs but we drive awareness and adoption through producing:

* Technical content

* Demos & sessions at events

* Tools like SDKs and interactive docs

* Marcom (social, email, etc)

* Community Building

## 2. What is the purpose and scope of your API developer outreach program?

Unlike companies who solely monetize services, our primary purpose is to enable developers to create custom integrations with Salesforce.

As an advanced enterprise software platform, its critical that Salesforce work well with all the other enterprise apps you might have.  In addition, many of our customers are building custom web or mobile apps that need access to customer data.

Because we are a platform, our purpose is not limited to just "API outreach" but is inclusive both of our APIs and also our app development platform.

Some of the primarily use-cases for our APIs are to extract data for archival purpose, surface customer data in third-party or bespoke apps, or to enable business systems to work together in other ways. We also have a family of machine learning APIs known as Einstein Vision and Einstein Language that can be used by any application to create predictions from unstructured images and text.

## 3. What does success look like for you?

Ultimately, we know that our customers are demanding more skilled Salesforce Developers every day to support their custom implementations so our primary metrics are monthly signups and active monthly usage.

Our goal is to keep the growth of our developer population in line with our overall customer growth to ensure there are enough developers in the ecosystem to service our customers needs.


We also measure job postings for Salesforce Developers, traffic to our website, engagement with our events like Dreamforce and TrailheaDX, and usage of our online learning portal trailhead.salesforce.com.

## 4. What are the key elements or practices (e.g, documentation, demos, webinars, conferences, blog posts) that you're using to drive and sustain effective adoption of your API(s)?

Blogging, webinars, documentation (including an API Explorer), training classes, sample code, first-party events (we do regional workshops called DevTrails, large regional events called Salesforce World Tours, and big global events called Dreamforce and TrailheaDX)

In addition, we have built a substantial community program with over 200 developers groups around the world and an MVP program to recognize top contributors in the community. We’re in the process of expanding our open source footprint (sample code, apps, and SDKs).

## 5. Do you make use of an API developer sandbox to drive and sustain adoption? If so, please describe how you've designed that environment to be useful and usable to developers.

We have a free environment called the Salesforce Developer Edition that anyone can sign up for. There is no expiration date so you can use it as long as you’d like, and you’re allowed to sign up for as many as you’d like for the times that you need a "clean sandbox."

We’ve also tightly integrated these developer editions into the Trailhead learning platform, so that as a developer is going through an online course (called a module) or a tutorial (called a project) they can actually complete hands-on challenges in their developer environment and get validation that they have done it correctly.

To protect our business interests, these developer environments have limits in terms of API usage, storage, user licenses, etc. With these limits, we do our best to find a balance between empowering the developers and protecting the business. And we have a process where developers can request increased limits.

## 6. What types of metrics do you use to measure adoption effectiveness and to inform future decisions about how you evolve your program?

We use our CRM platform to measure all the ways we touch our developers and how that impacts success.

## 7. How is your outreach program structured and staffed? How did it start out and evolve over time?

When we launched the program, we started small. 1-2 evangelists, a program manager for community/events, and a web developer.  It grew from there.

We don’t share details about our current team size publicly. However, the key components of our program are as follows with approximate percentages:

* Marketers (12%)

* Evangelists (35%)

* Community Program Managers (12%)

* Event Producers/Program Managers (13%)

* Marketing Operations: Email, Development, Creative, etc (25%)

## 8. Imagine that you’re charged with ensuring the complete failure of an API developer outreach program. What things would you do to ensure that failure?

Gate all the content.

Don’t provide a developer edition.

Don’t share use-cases or sample code.

Don’t find any partners.

Don’t engage with your users or help them be successful.

## 9. What big ideas do you have for evolving your outreach program to make it even more effective?

We have a ton of content but it’s not all discoverable.

Working on making our pages more data-driven and dynamic so we can expose all our resources.

We’re also moving a lot of our content to GitHub as well as creating a more organized process to store our code samples.  

Many of them are orphaned in blog posts and other places.

## 10. Any other thoughts you’d like to share? If so, please feel free!

N/A
