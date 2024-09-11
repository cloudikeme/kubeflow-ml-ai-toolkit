## Open Source Contributors and Their Motivations

Skip to main content
Kubeflow is a machine learning toolkit that runs on Kubernetes. Kubernetes runs on infrastructure that may or may not run on a cloud. That infrastructure can be orchestrated by APIs that are subject to the lifecycle of the underlying orchestration software. Making sure all these moving parts run smoothly requires cross-functional expertise and support that organizations are willing to pay either internal or external teams to provide. 

The demand for support and expertise fuels vendors' efforts to offer resources to end users through paid contributors and build solutions that integrate other tools. Vendor support is ultimately good for the open source community. These vendors contribute on behalf of the organizations, paying them and pushing features based on customer business needs. Vendor contributors can support many customers simultaneously, especially when managing common vulnerabilities. 

Vendor contributors also gain experience from various customer environments, providing insight to the community on what directions may help the project. Customers can tap into a vendor’s expertise and resources when paying them for support. These vendors support open source communities by allocating their resources, such as subject matter experts (SMEs), support teams, and infrastructure, to contribute to project development. In return, these vendors charge their customers a fee to ensure their business's sustainability. Still, vendor contributors are just one type of contributor. 

Non-vendor organizations can decide whether to pay a vendor for support and contributions or hire an internal team to do so instead. Contributors not associated with a vendor contribute to a project in service to supporting their internal customers (in the case of Kubeflow, data scientists or MLEs) as part of an internally facing development team. This type of contributor may have other proprietary integrations or systems that require support; therefore, it's economically viable for their organization to pay a dedicated team to contribute to an open source project while supporting internal tooling. The tribal knowledge the team has of their open source solution’s integration with the organization's systems improves their ability to support internal teams and make specialized improvements to their tooling. Some of these improvements may make sense to push upstream, and others will remain internal to the organization. These contributors provide much-needed input to directly support an open source project and often push features based on their specific end-user needs. These features can then be leveraged across the community.

This type of contribution is frequently the kind that we associate with open source, especially if we were introduced to open source through musings such as The Cathedral and The Bazaar by Eric S. Raymond, 2001. The story goes that a developer runs into a need based on their current role within an organization, develops a solution, and then opens sources the project to benefit others. Other teams across other organizations adopt the solution and push their improvements. These granular improvements happen across many organizations quickly, providing a stable and robust solution. After a solution has gained traction, a vendor may step in or be created by community members.

Being a paid vendor contributor or a specialized internal consumer of an open source solution is not the only type of contributor. Some contributors are not paid at all for their contributions. In the next section, we will explore these types of contributor profiles further.


## Why Do Contributors Contribute?

Communities' wants and needs are complex, and we cannot create perfectly grouped categories for all contributor motivations. Still, we can provide some common examples to help us appreciate the types of contributors within a community and their motivations.

At a high level, some types of contributors and their motivations are:

Hobbyists (unpaid) are enthusiasts who contribute to projects for personal satisfaction, learning, or passion for technology or the community. They may or may not have commercial interests in their contributions.

End User Contributors (paid) are often employed by organizations that use open source software and may contribute fixes, features, or improvements that their employer needs. Their organization's practical needs drive their contributions.

Vendor Contributors (paid) are individuals contributing on behalf of companies that offer products or services built around the open source project. Their contributions might aim to ensure compatibility, enhance features, or fix bugs that benefit their commercial offerings.

Portfolio Contributors (unpaid) work on projects to build their professional portfolio, gain experience, or transition into new technical areas. Their motivation can be career advancement, learning, or transitioning into a new field.

Founding Contributors (varied motivations) initiate open source projects, often intending to solve a specific problem or fill a niche. While they might envision potential commercial applications of their project, such as forming a company or adopting an open core model, their primary motivation can include a solid commitment to open source principles, community engagement, or personal passion for the project. These open source commitments are crucial for the success of these contributors because, to curate a healthy community sustained by contributors, they must set the initial direction and framework of the project while focusing on practicality and commonality rather than personal glorification.

We want to clarify that you do not need permission to contribute to an open source project. Everyone is welcome, even if they don’t fit the above categories.

## Who Can Contribuite and How?

Skip to main content
Many people think that they need to write code to contribute to projects. We do not believe this is true. There are many ways to contribute. You may see yourself as someone who fits into one of the following groups:

Maintainers are individuals or groups responsible for the project's direction, reviewing and merging contributions, and ensuring its health. They might be unpaid volunteers or sponsored by organizations.
Casual Contributors contribute infrequently, or on a one-off basis, such as fixing a bug they encountered or adding a minor feature they needed. Their engagement level is low compared to other personas.
Advocates/Community Evangelists contribute through community building, advocacy, education, and outreach rather than direct code contributions. They play a crucial role in growing and supporting the community.
Research Contributors are individuals or groups from academic or research institutions who contribute to projects as part of their research work. Their contributions include new features, performance improvements, or integrating the project with academic research.
Documentation Contributors focus on writing, updating, or translating documentation. This role is crucial for the accessibility and usability of open source projects.
No matter what kind of contributor you are, you are celebrated, and the list we provided is not exhaustive. Software is never finished because the context of the problem it solves constantly changes as the world evolves. Due to this evolution, people need software support, including bug fixes, vulnerability management, documentation, integration, upgrades, and deployment improvements. These tasks all take energy and time. We are incredibly grateful to any individual willing to answer a question, improve documentation, provide a new perspective within a community, or contribute in their way. Time is precious; without it, a community and associated solutions are subject to entropy and degradation.

Luckily, Kubeflow has a ton of fantastic and dedicated individuals who support projects as part of their jobs, hobbies, or interests. To contribute to the Kubeflow project, visit the official contributing page and join the Kubeflow Slack. If you are attending a Kubecon, you can visit Kubeflow at The Project Pavillion( a vendor-neutral space; projects are prohibited from giving sales pitches to attendees about a product or company) and chat with community members in person. They would be more than happy to help you get involved.

The question then arises—how do organizations or end users navigate the complexity of contributors when they need reliable support for their production systems?

## Open Source Support

Support can be divided into two groups: vendor support and community support. It is worth noting that just using one doesn’t mean you are barred from using the other. We are all in this together, and in the end, we are simply looking to ensure our tools are secure, robust, and reliable. Let’s explore these support models and trade-offs a bit further.

Vendor support typically involves a formal agreement or subscription with a company that offers expert services for an open source project. This support model can include guaranteed response times, dedicated personnel for troubleshooting, regular maintenance updates, and security patches. Organizations often opt for vendor support when they rely on open source software for critical business operations and need the assurance that any issues will be promptly addressed. The primary advantages of vendor support are reliability and accountability; however, it comes at a financial cost. This model benefits businesses that require a certain level of service level agreement (SLA) and cannot afford downtime or unresolved issues.

Community support, on the other hand, is based on the goodwill and expertise of the project's community. It includes forums, mailing lists, community chats, and other platforms where users can ask questions and share their knowledge. Community support is inherently collaborative and can be incredibly efficient, tapping into the collective wisdom and experience of a diverse group of users and developers. The trade-offs here include variability in response times and the reliance on community volunteers' availability and expertise. However, it also offers a prosperous learning environment where users can benefit from various perspectives and solutions to their problems. Community support is not built on the financial market but the trust market, where reputation and volunteer time are the currencies of choice.

Additionally, engaging with the community can lead to more robust networks, a deeper understanding of the software, and opportunities for collaboration. You can gain many skills by being involved in the community, including soft skills, which are in higher demand than technical skills for engineers. 

Navigating between vendor and community support requires understanding the needs and resources of your organization. Vendor support might be the preferred route for critical issues where downtime means lost revenue or severe impact. For developmental, non-critical, or educational purposes, community support offers a wealth of knowledge and the opportunity to contribute to the project. We often see vendors hiring community members to improve their offerings. We also see community members who were introduced to a project as part of their job at a vendor still contributing after transitioning to a different role. You may hear the rallying cry, “one team, different companies,” referring to the fact that a role or organization does not determine if a user can (or should) contribute to any open source project. Community membership does not depend on your employment status.

Engaging with both types of support can optimize your experience. Utilizing vendor support for critical infrastructure needs while participating in and contributing to the community can enhance your team's skills, improve the project's health, and ensure you are up to date with best practices and innovative uses of the software. The benefits of being part of the community are why vendors participate in the first place, since community support can enrich commercial support and vice versa.

## Summary

Skip to main content
In the open source ecosystems, where various projects with different scales and complexities exist, the Cloud Native Computing Foundation (CNCF) recognizes the importance of understanding and engaging with the support structures and maintainers that drive these initiatives. The CNCF advocates for a balanced approach, where the professional assurance provided by vendors complements the collaborative spirit of the open source community. This approach aims to navigate the challenges and leverage the opportunities inherent in adopting open source software, contributing to the project's success and sustainability.

## Conformance Standards and Testing in Open Source Communities

Skip to main content
Software conformance ensures that every vendor and community version of an application supports the required APIs. It enables interoperability from one installation to the next and allows the flexibility to choose between vendors or community projects. Without conformance, customers can be locked into certain distributions. Not only that, but defining a project’s core, the standard APIs and services that make up a project, is impossible without conformance. 

By running conformance programs, foundations like the CNCF can act as a third party to keep vendors and community editions accountable. One such example is the Certified Kubernetes Conformance Program and associated working group. Currently, the Kubeflow project does not have a conformance program but is working to build a Kubeflow conformance program in partnership with the CNCF.

## The Importance of Conformance

Skip to main content
To explore conformance further, let’s continue to use Kubernetes as an example. The value proposition of Kubernetes being portable is protected by conformance. Your workloads running on any cloud can ensure their API calls to Kubernetes remain the same. Working groups develop tests to ensure that anyone running the code of an application fits the standards set by the conformance teams. The standard tools for running these tests for Kubernetes are Sonobuoy and Hydrophone. These tools can ensure that your Kubernetes distribution’s APIs match the global requirements to be a Kubernetes distribution.

API standardization, versioning, and deprecation standards are critical for end users. Imagine being part of a Kubeflow platform team responsible for managing Kubeflow instances for 50 data scientists running pipelines. You must be sure that any environmental changes won’t impact your end users. If changes impact your end users, you must provide them with a migration path. Your data science teams could be running hundreds of development and production pipelines. If your Kubeflow system makes changes to the API because you switched vendors, you may end up with a plethora of failing pipelines.

Upgrades or distribution switches with undocumented or improperly communicated changes can heavily burden operations teams and create expensive outages. Conformance, through certification and standardization across distributions, helps us ensure our environments behave as expected. 

Now that we understand conformance and a project's core, you may wonder about the point of having different distributions if their APIs are all locked in by conformance. Relating this to Kubernetes, savvy individuals know that Kubernetes distributions are hardly ever JUST Kubernetes. Otherwise, how could they compete with each other? We must consider the differences between a core set of open source and conformant code bases vs. an open core solution that provides additional paid add-ons vs. an integrated open source solution. Let’s dive into this further in our next section.

## UnitOpen Source vs. Open Core

If all of this code is open source and conformant, how do vendors make money if they don’t use the solution internally? You may think the answer to this question is that the vendors provide support. Still, a distribution can be profitable in other ways besides delivering support on a fully open code base. To navigate an organization's open source distribution options, we must understand the difference between open source and open core, and how they impact our tooling decisions.

## Open Source Skip to main content

In its early stages, Terraform by HashiCorp exemplified the open source model's collaboration, transparency, and community-driven development principles. Terraform enables users to define and provision data center infrastructure using a high-level configuration language. From its inception, Terraform was designed to be fully open source, facilitating widespread adoption, contributions from the developer community, and rapid iteration.

Terraform was originally released under the Mozilla Public License 2.0 (MPL 2.0), a permissive license that allows the software to be used, modified, and distributed freely. The initial release under MPL 2.0 ensured that Terraform could be both accessible to the community for contributions and enhancements and also secure in terms of intellectual property rights, providing a balance that encouraged both collaboration and innovation.

This open source approach underpinned Terraform's early growth and enabled a diverse range of users—from individual developers to large enterprises—to adopt and contribute to the project. The vibrant community that formed around Terraform contributed significantly to its development, helping to identify bugs, add new features, and improve the software for all users. By leveraging the open source model, Terraform established a strong foundation, which facilitated its evolution into a vital tool for infrastructure management. The tool was so successful that companies began to form that used Terraform at their core, but with additional functionality. Let’s investigate this further.

## Open Core Model

Skip to main content
The open core model is a business strategy used by some software companies that offer a core version of a software product as open source while offering enhanced versions with additional features or services, such as proprietary paid software. This model allows the company to benefit from open source development's collaborative and innovative nature while also generating revenue by selling premium features or services unavailable in the open source version. The open core solution could also provide an integration code between conformant open source solutions, such as glue code. The glue code is external to the individual projects themselves, and if it is not open source, the solution is categorized as open core. Glue code needs conformance standards to be portable and open source; otherwise, it is deemed proprietary. 

To understand this better, let’s explore a popular open core solution that uses Terraform. 

While Terraform is a widely used tool that enables infrastructure as code, companies like Scalr have built services around Terraform that exemplify the open core model. Scalr offers Terraform as a core component of its infrastructure management platform, leveraging Terraform's capabilities to provide value-added services. Scalr's platform enhances Terraform's open source core with a commercial offering that includes advanced role-based access control, policy enforcement, cost management, and a multi-tenant architecture. These features cater to enterprises seeking scalable, secure, and efficient infrastructure management across multiple teams and cloud environments. By building on the open source foundation of Terraform, Scalr can offer a service that addresses specific business needs while contributing to the broader ecosystem.

The exact definition of open core can get tricky. Some companies advertise themselves as open core (think GitLab), whereas others may not advertise as open core but are still labeled as such by external teams or community members. Ultimately, the primary differentiator is whether the solution has proprietary components beyond the open source project it supports. Now, let’s dive into what a purely open source solution integrated with a core offering looks like.

## Integrated Open Source

Skip to main content
The distinction between open core and open source models often hinges on adding paid premium features developed from an open source base. However, what happens when those premium features are offered for free? When a project goes beyond the core APIs of a single project and integrates with another, we call it an integrated open source model. This model is characterized by integrating multiple open source projects, using custom code to create a cohesive solution that addresses complex or specific use cases. Unlike the open core model, which centers on a core open source project with additional proprietary features, integrated open source relies entirely on open source components, including the integration mechanisms. 

While integrated open source offers numerous benefits, it also presents specific considerations, such as: 

Integration Complexity: Ensuring seamless integration between different projects can be challenging, especially when they have distinct architectures or are not designed with interoperability.
Maintenance and Support: The organization or community that developed the integrated solution is often responsible for maintaining it and providing support, which can require significant effort and expertise.
Conformance and Compatibility: While the individual projects may conform to specific standards or expectations, ensuring that the integrated solution remains conformant can be complex, especially when updates or changes are made to the components.
Integrated open source solutions can be a fantastic methodology for demonstrating the power of a core solution's ability to function with other open source tools. Today, Kubeflow can benefit from open source projects such as Volcano, Kserve, and MLFlow. Many integrated projects may seek to become deeper conformant integrations through a proposal to the community. Ultimately, this can lead to a more robust and conformant core project.

## The Role of Neutral Parties in Open Source

Skip to main content
On August 10, 2023, HashiCorp announced a license change for its products, including Terraform. It was moved under a non-open source Business Source License BSL v1.1 for the 1.6 version. As a result, the Terraform community collaborated and created OpenTofu, an open source alternative to Terraform, managed by the Linux Foundation. Members included companies such as Harness, Gruntwork, Spacelift, env0, Scalr, Digger, Terrateam, Massdriver, and Terramate. The OpenTofu story emphasizes a neutral party's value in managing a core code base and ensuring conformance. Organizations may depend on a tool only to have the license adjusted. The licensing adjustment can impact how an organization uses and distributes code based on the core project.

In some cases, this may affect a company's core business. HashiCorp had every right to change its licensing to do what it believed was best for its business. OpenTofu became a fork of the initial project for organizations that still want to contribute and use an open source version of Terraform (now OpenTofu). 

Kubeflow has been donated to the CNCF, reducing the concern that one organization may be able to change a license and prevent open source and open core distributions.

## The Cost of Core Contributors

Skip to main content
On November 13, 2023, the company Tecton decided that it could no longer support the open source project Feast. Their reasoning was mainly because they wanted to focus on building a reliable feature store infrastructure for AI and no longer allocate resources to the Feast project. Tecton did not choose to pull in and relicense the Feast project but instead sought to onboard new maintainers. This way, the current maintainers would only need to fork the project if they want to continue working on it in a neutral capacity. On February 23, 2024 a blog post was released announcing new maintainers, Red Hat, Affirm, and J.P. Morgan. The new maintainer announcement was good news for the community, but we’d like to be transparent about what was at risk here.

Losing core contributors can leave a project directionless. As discussed, founding contributors of open source projects often intend to solve a specific problem or fill a niche. As the project grows in maturity and reach, these founders become elders within a community, guiding members toward the inner rings of the community. The loss of leadership can leave communities without these critical elders, who help protect the community boundaries for current members and bring in new members. Kubeflow and Feast are two projects that were able to adapt, evolve, and grow despite major community adjustments, but not all communities do. You can learn more about the value of winding down projects from this Open Source Guide offered by the Linux Foundation.

## Summary

Skip to main content
Understanding open source vs. open core helps us be more strategic with our distribution choices by helping us understand the implications of our vendor relationships. Some code may be owned by a neutral party and subject to conformance, thus enhancing our portability. Other codes may be proprietary glue codes or premium features. 

Proprietary code and vendor-backed distributions are okay. The vendors pay teams to contribute to open source and improve the stability of the project as a whole while providing other premium features. It may make sense for teams to benefit from both community and vendor support and implementations.

Additional implementations to a core project do not need to be premium or proprietary; the open source integration model demonstrates the ability to build open source solutions with open source to create a complete offering and bridge communities.

All of these models rely on freely using a project’s conformant core. The OpenTofu story is an example of organizations seeking a neutral party so businesses can use the core code without worrying about license changes.

Organizations that choose to remove themselves from a project must hand off the community to new maintainers or risk the project going stale. 

Kubeflow's membership in the CNCF ensures its neutrality. It also enhances its longevity, making conformant distributions a safe investment for organizations of all sizes worried about licensing changes through the governance and standardization of the Kubeflow project.

