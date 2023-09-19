---
title: Literature Review
slug: literature-review
author: Jan Dittrich
weight: 2
---
# Research on Usability and Open Source Software

## Intro

Analyzing the difficulties to integrate open source development with methods to improve project’s usability go back at least two decades to Nichols/Twidale (2003). At the time of writing, the question remains open and is still researched (e.g. recent contributions by Wang et.al. 2022). This overview looks at different key points of the research, structuring it in sections on: 

* Involvement of experts
  
* Focus on a community of developers

* Modularity of work

* Communication and coordination methods

* Distance to end users

* Attempted interventions to integrate design and open source work
## Usability Experts in Open Source Projects

Usability experts are rarely involved in open source projects (Raza, Caprez 2012; Andreasen 2006, Wang 2022). This is reflected in the research that tries to find ways to involve experts (Benson et.al. 2004, Bach 2009, Hedberg, Iivari 2009, Rajanen et.al 2015). Rajanen et.al. 2015 shows how usability experts are kept out of participation via the tactics of “non-response, social exclusion, and false acceptance”. While there might be several systemic factors that makes it less likely for Usability experts to participate, there can also be an aversion to the idea of expert involvement per se, as documented by Andreasen 2006, who describes concerns that expert involvement is incompatible with the group-based deliberation by community members (see Coleman 2012 for a discussion on this way of making decisions).

## Open Source Projects as communities of developers

Open Source projects are often defined as communities of developers or hackers. This can be already found in Reymond’s “The Cathedral and the Bazaar” in which he suggests “Treating your users as co-developers”. As Bødker describes: “the strong sense of emotional belonging that the community commands tends to preclude the possibility of seeing beyond their own motivations.” Raymond also claims that “given enough eyeballs, all bugs are shallow.” which Nicols refers to when saying: “The OSS approach fails for end user usability because there are 'the wrong kind of eyeballs' looking at, but failing to see, usability issues.” Dunguid points out that the principle, even within software development, only focuses on fixing bugs, not on other aspects of development. Despite these limits to apply developer’s methods to non-code creations, Rajanen (2015) notes that skills in programming can help to get design improvements accepted.

## Modularity, Coherence, Architecture

A commonly cited aphorism by “Brook’s Law” suggests that adding more developers to a delayed project will delay it more (Brooks, 1995: “Oversimplifying outrageously, we state Brooks's Law: Adding manpower to a late software project makes it later.”). Open Source projects allow parallel development and seem to avoid this problem (Nicols 2002, Feller, Fritzgeralt 2001, Raymond 1997). However, this mode of collaboration demands modularity (Benkler 2002). Not all products can be worked on with such a peer-production approach, since they might not be easily modularized without sacrificing essential traits; Benkler suggests that e.g. “Novels…are likely to prove resistant to peer production”; Duguid (2006), too, shows that other modes of production might also run into problems, even if they already use a mode of peer-production (e.g. Wikipedia). Dunguid suggests that software production, particularly the fixing of bugs, might be a mode that works very well in peer production but the principles of it might not easily transfer to other media (like user interface designs). Hill and Monroy-Hernández (2013) evaluate the claim that peer production improves the quality for results empirically. They find that the artistic quality of computer games does not benefit from peer production.

## Media, Communication, Coordination

To coordinate large projects, one might assume that roadmaps, design documents and other artifacts might play an important role in defining requirements of the software. However, such artifacts are not very prominent in many open-source projects (Alspaugh/Scacchi 2013). The coordination happens in forums and mailing lists (Bødker 2007, Alspaugh/Scacchi 2013) in ongoing deliberation. Additionally, the code itself is a resource for structuring collaboration (Bolici et.al. 2016). The coordination via ongoing communication and working on code is different from the common modes of working for designers, who often coordinate via representations of users and future products (Dix 2011 or Bødker 1998 for a general overview, but also Wilkie, 2010; Akrich 1995;) That many typical representations for UX work are absent in open source projects is also noted by Benson et.al. (2004), pointing out that both user profiles and representations of the work process for designers don’t exist in the project they analyzed. 

## Elitism and distance from non-technical users

Achieving technological competence is particularly valued in the community of open source hackers (Coleman 2012). Learning from documentation and participation in the community of hackers is expected and can actually lead to limited support for newcomers, since helping them too much “will undercut their ability to prove their worth and intelligence within a group” (Coleman 2012)

The non-skilled person is the “other” that the hacker is not. Andreasen et.al. (2006) cites a participant saying: “...hackers code for fun, and sure it is more fun to add support for some protocol feature than fixing a dialog for grandma”. (Note, that the imagined opposite to a fun task for the competent and often young and male hacker is supporting an old woman). The distance between the in-group and the out-group by their hacking ability is not new, and described in Levy’s “Hackers” (2010) as how members of the MIT AI Lab in the mid to late 60s divided their social world: “Winners” who are good at hacking, and “Losers” who are not.

A distinction between knowledgeable insiders and outside people who do not know how a computer works is not limited to open source hacking; it might be common in programming in general. Phil Agre (1995) describes the idea of the user in the “technical mindset” in which the user is seen as a part of the technological system – but a particular unruly one. Woolgar (1990) details how people in his field-site, a tech company, divide the world into the creators and “the user” (in general). In usability tests, the creators tried to evaluate their assumptions about users while at the same time upholding them: If a test participant would unexpectedly have knowledge of technology, they would be seen as a non-typical user.

## Strategies and tactics for UX and FOSS collaboration

To integrate user experience work and open source development, there are different strategies for change. A rough taxonomy could be categorizing the suggestions by what is changed (roles, technical infrastructure, politics, education) and whose practices are taken as a model to be adapted by others (Do UX designers learn to code or developers to adapt UX methods?)

Rajanen (2013)  reports a successful collaboration when designers adapted to the code-focussed ways of work in an open source project. However, they thus risk losing focus on core values of design work, particularly representing non-technical users (Rajanen 2013) Rajanen (2015) sees designers in a position of low power in the context of open source projects which makes the adaption plausible despite the risk. 

Reimayr (2006) describes collaboration with several open source projects, particularly describing the need to find people with influence, clearly defining project goals and establishing communication channels. This can be seen as focussing on project politics. Other interventions focus on technical/social  infrastructure – Bødker et.al. (2007) describe the introduction of a mailing list and learning materials; Bach et.al.(2009)  suggest changes to a (developer) collaboration platform, introducing a UX workspace in the software. Nichols/Twidale (2003) suggests a broad range of interventions: academic involvement, involving end users, discussion infrastructure, lightweight usability testing, involvement of experts and evangelism for design, but does not provide an evaluation of these methods. 

## Conclusion

The question of how design work can improve the usability and usefulness of open source software for non-developers remains open – while some researchers can report successful collaborations, there are strong differences between UX designers and open source developers in what a good outcome is and in the methods to achieve it. Thus, despite research on the topic going at least back to the 2000s, the relation remains conflictual. While the research I have reviewed here has been on UX work in open source software projects in general, it is likely that the described conflicts also exist in scientific open source software projects. 



# Open Source Software, Hacker Culture and their relation to Academia 

## Intro

The idea that code should be shared and collaborated on is strongly related to what is called “hacker culture,” a group of people concerned with the creative and self-directed use of computers and code. There are plenty of programmers who would not call themselves “hackers” but nevertheless participate in open source projects, sometimes with great enthusiasm. But the culture of hacking creates and maintains the values and practices that a lot of open source software is built upon. For various historical reasons, this is not named “open source culture”. This is because “open source” is a politically laden term, connected to “free software”. “Open Source” is sometimes used as equivalent to “Free Software” and sometimes used as opposed to it. Also, when looking at culture, both “Free” or “Open Source” focus on the software and the legal treatment of its code rather than the practices and values. Thus, particularly in sociological discourse, “hacker culture” is the more common label. 

For our purposes it is relevant how hacker culture (and with that open source and free software) are related to academia.

## Hacker culture’s value system mirroring academia

Hacker culture and Academia both use the idea of “meritocracy”: Fame and power rests with the people who contributed to the community's progress the most. Both cultures rely on sharing of information, imagine themselves as being part of a global community, and of progressing, step-by-step, to a greater goal. The “merit” that people have in their communities is tracked in publications for researchers and in code contributions for hackers; if their research or code is cited or used, it adds to their fame. Both cultures are, at the same time communitarian with their concerns for sharing, documenting and circulating knowledge, yet also very antagonistic and individualistic by harshly criticizing contributions by others with the justification that this is needed for both the progress of science and code, lest the objects of concern will be tainted with bad contributions. 

## Hacker culture’s origins in academic institutions

It is unsurprising that hacker culture and academia share similarities: hacker culture’s origins are at universities. Particularly MIT is relevant here, both as an institution in general but particularly its Model Railway Club and its Artificial Intelligence Laboratory. Before home computers were widespread, universities were one of the places where computers were available—and linked to each other via the internet, mainly to other large research universities like Carnegie Mellon, and government research institutions. This allowed hackers  to collaborate and socialize through computers. Today, collaboration with online platforms seems normal, but  in the late 1970s and 80s it sparked new practices to work and to imagine oneself as part of a larger community. 

## Conclusion

In our research, people were occasionally frustrated with conflicts between open development and academia. Both systems do not match perfectly. This should not detract from their strong similarities in many areas: Their cultural values, particularly the idea of belonging to a community in which individuals gain merit are similar, which is plausible since early hacker culture was often based in universities.
