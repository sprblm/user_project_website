---
title: Design curriculum for Science & Research OSS
slug: design-curriculum
weight: 7
author: Eriol Fox
---
## A curriculum for design and usability in SROSS (sample)

This sample curriculum was developed by our USER researchers to address some of the common development areas for design and usability that came up in our work. This curriculum is a work-in-progress, iterative document that we want to grow, assess, and build upon with both the Science and Research OSS community and the Design and Usability communities. It is separated into some key themes around common development areas for design and usability in SROSS.

**Understanding different contributors’ perspectives and intentions for tool use.**

What gets built with whom is important. Sure, one can develop a "computation for X" and then try to make it usable. But is this mostly helpful for computational approaches to increase a SROSS project’s reach or helpful for addressing users’ current concerns. Understanding what a SROSS tool hopes to achieve for who early on will help with a design approach which is centered on a more broadly relevant spectrum of users.

- **Value propositions** help SROSS projects better identify the core values of the tool and who it serves. Doing many value propositions as a team helps to further narrow down the multiple purposes of an SROSS project from various user perspectives. This also uncovers the differing perspectives from team members, maintainers and community contributors on ‘who’ the SROSS serves and why and helps to communicate overall expectations and goals for the SROSS. It also helps uncover assumptions people working in the SROSS have about their users. We recommend doing this exercise whenever there is strategical shift in the project or user base.
    - Time needed for exercise: 1-2 hours
    - Recommended size of group: 1-8
    - Template: [Value Proposition](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559216889508&cot=14)
- **A stakeholder analysis or map** helps a team to understand their own biases towards certain users types that are present in the team or community already and those that are not. Stakeholder maps ask teams to consider questions like ‘Who is missing from this map?’ and ‘Who do we think is important and for what reasons are they important?’ This helps to identify users and stakeholders that offer different opportunities to the SROSS and can be aligned with their project and science/research goals. For example, a funder might be central as a stakeholder as they offer financial support but they may not actively contribute to improving the code or science/research discoveries in the SROSS and therefore they may move from a central role to a periphery role at different stages the project undertakes. The power of this exercise is in understanding that it is never ‘final’ –  different users become important at different times in an OSS tool’s lifecycle. The ‘map’ is editable and is contributed to and viewed by as many contributors to the SROSS tool as possible. We recommend revisiting this map twice a year.
    - Time needed for exercise: 2-4 hours
    - Recommended size of group: 2-10
    - Template: [Stakeholder analysis or map](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559216889553&cot=14)
- **User personas/User profiles** are a fairly well known term as they’ve become a common talking point for most companies when trying to communicate user needs or ‘on behalf’ of users. Useful User Personas however, are based in facts and reality and use real user information and data as opposed to speculative guess work. Starting with guess work is a good starting point to then investigate and prove correct or incorrect, so start with speculative personas if gathering data is difficult. A user persona is most useful when they are not based on single ‘real life’ individuals but when a persona is comprised of many characteristics of the same type. e.g. You have 5 people that could be described as the ‘Student of Biology, new user image modelling focus’ You would create a single persona from these 5 real life people. A user persona is most useful to advocate for their point of view as opposed to an ‘insider’ point of view such as that of the tool builders/contributors. They are, essentially, a tool with which to ground usability and user-centred hypotheses. With User Personas we can say ‘User Persona A needs a feature that does X, Y and Z while making sure that their workflows are respected and maintained’ rather that ‘I’ statements like ‘As the lead developer I believe we should build the feature for users in X way.’ We recommend building user personas from your stakeholder map.
    - Time needed for exercise: 2-8 hours
    - Recommended size of group: 3-9
    - Template: [User Personas](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559216889595&cot=14)
- **User Journey maps** are a way of fully understanding a user’s pathway into software. We forget that the experiences and processes outside the screen – the thoughts, needs and feelings associated with parts of the journey that are not configuring data and clicking buttons – are important and where we can find critical information on how users fully experience a tool or process and how the tool might better fit areal life action or process.
    - Time needed for exercise: 3 hours to 3 days (depending on how many users there are to map)
    - Recommended size of group: 3-5
    - Template: [User Journey maps](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559314033087&cot=14)

**Critically analysing design, UI, Usability and UX**

Understanding design better and respecting the processes without needing to be ‘experts’ in design came up as a critical part of SROSS’s journey to learn better user-centred processes and usability in their tools. The most difficult part however, is condensing many years of undergraduate and graduate study into a easily digestible format.

- **Primer on what types of design there are and what designers practice.** The best way to learn these terms is to seek out and speak to designers that identify as key job titles and terms as every designer will practice slightly differently. Most designers contributing to and involved in OSS in some way will be a generalist of sorts and practice many parts of the design spectrum in tandem.
    - Time needed for exercise: 1 month
    - Recommended size of group: 1-3
    - Template: [Primer on design](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559304638612&cot=14)
- **Understanding Usability heuristics (Rules of thumb that help to find problems with existing interfaces) and adding your own heuristics that are specific to scientific and research OSS** is a way that SROSS can better understand the practical applications of design by applying a series of rules and questions to aspects of a ‘designed’ tool or application. This works best with a tool that includes a GUI/UI or some way the user interfaces with a command line but can also be applied to concepts, ideas and aspects of future design in a tool. However, it is better to use a ‘design principle’ to apply to tools without a GUI. Creating and amending a projects own heuristics can empower the team to understand what unique aspects of science and research software are not represented in existing design guidance and help communicate the values the science and research has in it’s tooling.
    - Time needed for exercise: 2-5 days
    - Recommended size of group: 4-6
    - Template: [Usability heuristics](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559305132753&cot=14)
- **Interface inventory and GUI/UI library build.** Useful for projects that have a ‘GUI/UI’ and also useful for projects that are a series of documentations and commands in terminals/other softwares. A guide of how the interface should be constructed is useful documentation for teams and projects and often unearth where there are gaps, inconsistencies and miscommunications are in a GUI or content pattern. We recommend using Brad Frost’s template to categorise GUI/UI before analysis and library component creation.
    - Time needed for exercise: Interface inventory 1-3 days, GUI/UI library build: 5 days +
    - Recommended size of group: 3+
    - Template: [Interface inventory and GUI/UI library](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559312695913&cot=14)
- **WCAG and A11y web accessibility analysis** using the official guidelines for accessibility is the best way to ensure you’re meeting minimum standards for accessibility for impaired and disabled users. We recommend pairing accessibility guidelines with heuristic evaluation and other methods of assessing how well a design, UI or content is suited to users.
    - Time needed for exercise: 5 days +
    - Recommended size of group: 3-8
    - Template: [WCAG and A11y web accessibility](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559312979961&cot=14)

**Involving users in research gathering and research synthesis**

- Most SROSS projects already interact with users via ad hoc communications methods like community chat channels, issues and bug reports in Github, support emails and feature requests. They also gain insights in person at science and research conferences directly from users and, uniquely, from others’ science and research papers that cite usage of their SROSS tool. Collecting relevant data for design and categorizing it a allows to share the data with the wider community, for example by checking it in the project’s repository. This way it can be used to discuss design ideas together in the context of their likely use. This is one way of taking user feedback seriously. But, expanding beyond the ad hoc ways of generating user research is key to evolving and maturing the design and usability practice of an OSS project.

![Emergent forms of design](https://raw.githubusercontent.com/simplysecure/user_project_website/main/static/images/emergent-forms-of-design-sma.jpg)

- **Write and send user feedback surveys and perform moderated or unmoderated user tests.** These practices can be done ****in a lightweight way and can leverage the [Adoptable Dev’s guide to…](https://simplysecure.github.io/devs-guide-to/a-dev-guide-to-usertesting/) understanding how to make sense of the research and science purposes (of a tools use) from these user testing methods are going to be key to a specific project’s success and cannot be templated as each SROSS project often has unique science and research goals . Encourage and ensure that ‘not just devs’ or expected user types respond to surveys and other user feedback collection. Exercises for defining who your users are (like stakeholder mapping and user personas) help an SROSS team to understand who they want to hear from the most.
    - Time needed for exercise: 3 weeks average
    - Recommended size of group: 3-6
    - Template: [Write and send user feedback surveys](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559313400343&cot=14)
- **Planning and Designing an open roadmap (with the community)** is a great way of making sure the feature requests start and remain user led. However, without clear criteria and guidance this can get speculative and have a sense of ‘fictional magic technology’ quickly. Ensure that as the team responsible for implementation you are keeping the features, improvements and fixes within the realms of possibility or communicating clearly why they would be difficult to build while still honouring the validity of the user need and exploring as many implementation options as possible. We created a feasibility worksheet to facilitate the complexity of features and work on OSS tools to help with this.
    - Time needed for exercise: 5 days to 3 months
    - Recommended size of group: 3-8
    - Template: [Planning and Designing an open roadmap](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559313472268&cot=14)
- **Bringing in design and usability into every feature issues and acceptance criteria.** This can be done by making design a part of the pipeline process where tasks/issues move from labelled stage to stage with a built-in design review or design QA phase. Design review can be done at the estimation phase and design QA is done at the pre-release phase. This is difficult to implement if you do not already have phases of work and are not yet open about how work gets decided on. This is also feasible when you have some reliable design resource or are able to run through design review and QA without identifying as a designer.
  - Time needed for exercise: 3 days per round of design reviews
  - Recommended size of group: 2-4
  - Template: [Design and usability into every feature](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559313472664&cot=14)
- **Building an OSS design team** is arguably one of the most complex and labour intensive exercises on the journey to great design and usability in OSS. It requires reaching out to designers in OSS communities such as [Open Source Design.net](https://opensourcedesign.net/) and ensuring you are asking for support in design and usability that will be implemented in the tool. Designer OSS volunteer turnover can be high due to many complex factors. Onboarding and ensuring that the designers are valued is critical to their success.
  - Time needed for exercise: Minimum of 3 months of onboarding and continued communication.
  - Recommended size of group: 1-3
  - Template: [Building an OSS design team](https://miro.com/app/board/uXjVM2k3my8=/?moveToWidget=3458764559313472784&cot=14)
