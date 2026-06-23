---
title: "The Web of Issues"
date: 2026-06-10
summary: "On design as argumentation, and why the process is the work."
linkedin_url: "https://www.linkedin.com/pulse/web-issues-venkatesh-rajamanickam-nxo9f/"
author: "Venkatesh Rajamanickam"
source: "LinkedIn"
---

{{< article-byline >}}

<p class="article-read-link"><a href="https://www.linkedin.com/pulse/web-issues-venkatesh-rajamanickam-nxo9f/" target="_blank" rel="noreferrer">Read on LinkedIn</a></p>

### On design as argumentation, and why the process is the work.

Note: This essay began as a footnote to the previous essay [The Brief Always Arrives Wrong](/articles/the-brief-always-arrives-wrong/), and refused to stay one.

In 1972 Horst Rittel, an architect and design theorist who had left the HfG Ulm to teach at Berkeley, published a paper that gave the profession one of its most useful and least used ideas. The paper argued that design problems are not problems in the technical sense: bounded, solvable, capable of a correct answer that can be verified after the fact. They are, in his phrase, wicked -- open-ended and intrinsically controversial, resistant to closure, reshaped by every attempt to resolve them. But Rittel did not stop at the diagnosis. What interested him was what followed from it: that because design problems cannot be closed by logic or evidence alone, the process of designing is unavoidably an argumentative process. The designer debates with herself, or with others. Issues arise. Competing positions form. Arguments are assembled for and against each position. Eventually a judgment is made; not derivable from the evidence alone, but made despite its incompleteness, under the pressure of time and the weight of the stakes involved.

Rittel called this structure a web of issues, and he was precise about its components. An issue is a design question that has been opened and not yet closed: not "what colour should the button be"; that is a preference, answerable by convention; but "what should the primary action of this screen be, and for whom?" A position is an answer to an issue, together with the reasoning that supports it. An argument is the case for or against a position, which may raise new issues, loop back into earlier ones, or reveal that something that appeared settled was not. The web is not a diagram of a method. It is a description of what is actually happening when designers work, whether they know it or not. The process, Rittel observed, "appears as one of formation of judgement, alternating with the search for ideas."

### The Issue That Will Not Stay Closed

Interaction design is the field in which Rittel's web is most immediately and most relentlessly visible. Every interaction design problem is simultaneously a problem about behaviour -- what will a user do; and a problem about intent, what should we enable them to do, and what should we make difficult? Those two questions are not the same, and they do not converge naturally. The gap between them is where the design work lives.

Consider the design of a notification system for a mobile application. The stated brief might be a technical task: implement alerts that inform users of relevant events. Open that brief five minutes into a working session and you find it is not a brief at all but a cluster of unresolved issues, each connected to others. How many notifications are too many? That depends on what the application is for and how often a user will reasonably want to be interrupted; which depends on who the user is and in what context they are using the product, which may not be the context the product team imagined. What counts as relevant? That is not a data question; it is a value question, and the product team will have different answers to it than the users will. Should the user be able to configure their own preferences, or does that merely shift the burden of a design decision onto someone who came to use an application, not to administrate one? Should the default be permissive or conservative? Each answer opens others.

This is not failure. It is the normal condition of an interaction design problem in progress. The issues are not embarrassing gaps to be papered over; they are the actual substance of the work. A designer who moves from brief to wireframe without passing through this territory has not avoided the web; she has left its issues unexamined, where they will reappear later; in user testing, in a product review, in the support queue, in the slow decline of a feature that nobody turns off because nobody turns anything on.

A designer who moves from brief to wireframe without passing through the web of issues has not avoided the arguments. She has merely deferred them to a point where they are more expensive to resolve.

### Closing Is a Political Act

The most challenging aspect of Rittel's account; and the one that sits most awkwardly with professional self-presentation; is his insistence that the closing of issues is neither logical nor neutral. It is political. When a design team decides that the notification system will default to minimal and require users to opt into more, they have not solved a problem; they have made a judgment reflecting values about user autonomy, about the relationship between product and person, about what kind of attention is worth claiming. Someone with different values would close the issue differently. Neither closure is wrong in a technical sense. Both are answerable for their consequences.

This matters because the closing of issues does not happen in a vacuum. It happens in organisations, between people with different authority, different expertise, and different stakes in the outcome. The interaction designer sits in a room with a product manager accountable for engagement metrics, a brand strategist who wants the application to feel present in users' lives, and an engineer who knows what is and is not feasible in the sprint. All of them have a position. None is derivable from the evidence. What happens in that room; who speaks, who listens, whose framing takes hold; shapes the design. The outcome is not produced by analysis. It is produced by an argument that someone wins, or that ends in a compromise nobody fully endorses.

Rittel saw this not as a deficiency to be corrected by better methods but as an irreducible feature of the domain. Design problems are about what should be, not merely about what is. Questions about what should be can only be answered by people with values, answerable to each other. No optimisation function can settle them. No model trained on past design decisions can resolve them, because those past decisions were themselves political closures made under particular conditions by particular people, and those conditions have changed.

### What Gets Lost When the Process Is Skipped

The prospect of generative AI accelerating interaction design raises a specific and serious question: what happens to the web of issues when the output arrives before the arguments have been made? This is already the mode in which many teams are beginning to use generative tools; not to assist in working through a problem but to bypass it, moving quickly from a brief to a solution that looks finished and therefore creates a psychological pressure to be accepted. [1]

A generated set of screens for a banking application's onboarding flow will have decided; implicitly, without deliberation; how much information to request at each step, in what order, with what level of explanation offered to the user. These are design decisions. They encode a position on every issue the team has not yet opened. The danger is not that the position will be wrong, although it may be; the danger is that it will be invisible. Because the output looks resolved, the issues it has closed without debate remain closed. The team moves forward carrying the weight of decisions it did not make, toward consequences it has not examined.

The documentation of design rationale; which Rittel advocated through his Issue-Based Information System, and which the field has approached with instruments from QOC to design history templates [2]; is precisely the record of which issues were opened, what positions were considered, and on what grounds a judgment was made. It is not bureaucratic overhead. It is the only reliable way to know, when a product fails or succeeds, what decisions produced the outcome. Without it, there is no learning; only repetition.

### The Designer as the One Who Keeps the Issues Open

The most important thing an interaction designer does is not to solve problems but to keep the right problems open for long enough that they can be solved well. The discipline this requires is the discipline to distinguish the issues that must be closed by argument from those that can be closed by testing, and both of those from the issues that are not yet open because nobody has yet noticed them.

A senior interaction designer working on a government service; a tax filing interface, or a benefits eligibility assessment; is doing something structurally different from what a generative model does when it produces a UI for the same task. The model has learned from existing interfaces and will produce something that looks like they look: interfaces built by people who faced the same time pressures and political constraints, whose judgments are now embedded in the training data as though they were the natural shape of the solution space. The designer who knows that a benefit claimant arriving at a digital form has recently experienced a significant life disruption, that the form will be read by people whose first language is not English, that the consequence of a misunderstood question is not a failed submission but a months-long gap in income; that designer is not doing what the model does. She is holding open the issues that the model has already, invisibly, closed.

Rittel's insight was that design problems have no stopping rule. There is no moment at which a design problem is objectively solved; there is only a moment at which the designer; for reasons that are practical, political, financial, or simply human; decides to stop. What makes that stopping defensible is not that all the issues have been closed but that the important ones have been opened, examined, argued over, and closed with full knowledge of what was given up. That is not a process that accelerates with better generation. It requires people who understand what they are doing and why, and who are willing to be accountable for the answer.

The image of design that the AI displacement argument offers is of a profession organising the production of resolved solutions to understood problems. Rittel's account offers something truer and more demanding: a profession organising the argumentation that makes any resolution possible at all. The designer is not primarily a maker. She is the person who understands which questions must be answered before anything should be made, who can hold those questions open in a room full of people who want to close them prematurely, and who carries the judgment; and the accountability; for when enough arguing has been done.

Generative systems will produce more and more plausible-looking resolutions. The profession's task is to remain the part of the process that asks whether those resolutions address the right problems, argued for the right reasons, on behalf of the right people. That task does not diminish as the generation becomes more fluent. If anything, it becomes more necessary; because fluency, unaccompanied by argument, is not design. It is the appearance of design, which is a different thing entirely, and a considerably more dangerous one.

---

### Notes

[1] The observation that AI-generated outputs render prior design decisions invisible; and that this invisibility creates pressure to accept those decisions without examination; is structurally identical to the problem Rittel identified with first-generation design methods: the illusion that a rational process can produce a determinate solution, obscuring the political judgments that shaped it. The difference is one of speed and surface finish. The problem is the same.

[2] Rittel's Issue-Based Information System (IBIS) was developed together with Werner Kunz and first published in 1970, with the argumentative model of design reasoning elaborated through the 1970s and formalised in "The Reasoning of Designers" (1987, published Stuttgart 1988). The IBIS notation; issues, positions, arguments; was subsequently implemented in digital form as gIBIS (Graphical Issue-Based Information System) in the late 1980s and influenced the design rationale research programme that extended through the 1990s, producing tools including QOC (Questions, Options, Criteria) and a substantial body of work on how design reasoning is documented, or fails to be. The core insight; that the argumentation is the process and the rationale is its record; remains largely unimplemented in mainstream practice, which continues to document outputs rather than deliberations.
