---
title: "VII. No Ultimate Test"
date: 2026-07-27
summary: "On why the adequacy of a generated design cannot be verified, even in principle."
linkedin_url: "https://www.linkedin.com/pulse/vii-ultimate-test-venkatesh-rajamanickam-bnt8f"
author: "Venkatesh Rajamanickam"
source: "LinkedIn"
---

{{< article-byline >}}

<p class="article-read-link"><a href="https://www.linkedin.com/pulse/vii-ultimate-test-venkatesh-rajamanickam-bnt8f" target="_blank" rel="noreferrer">Read on LinkedIn</a></p>

![No Ultimate Test](/articles/images/no-ultimate-test.jpeg "Tacoma Narrows Bridge, Nov 7, 1940")

### On why the adequacy of a generated design cannot be verified, even in principle.

<i>Note: This essay continues a series. [The Brief Always Arrives Wrong](/articles/the-brief-always-arrives-wrong/) argued that design's most consequential work is the constituting of problems. [The Web of Issues](/articles/the-web-of-issues/) drew on Horst Rittel to argue that the design process is irreducibly argumentative, and that closing its issues is a political act. [The Quarrel That AI Reopened](/articles/the-quarrel-that-ai-reopened/) and [Two Stopping Rules](/articles/two-stopping-rules/) set Rittel against Herbert Simon over whether the framing of problems and the ending of work can be formalised. [The Resolution of the Argument](/articles/the-resolution-of-the-argument/) examined the representations in which the arguing happens. [A Sketch Is a Question](/articles/a-sketch-is-a-question/) took the claim to the design of interactive digital products, whose subject matter is behaviour, which are inherently hard to represent. This essay returns to Rittel one last time, to the least quoted and most consequential of his claims.</i>

Rittel and Webber gave wicked problems ten characteristics. The fourth is the one almost nobody cites, and it is the one this whole series finally rests on. It says that a wicked problem has no test of its solution, neither an immediate one nor an ultimate one [1].

There is no immediate test because a design's consequences take time to appear. The redesigned benefits form looks fine in the lab. What it actually does emerges over months, in the lives of people the team will never meet.

There is no ultimate test for a deeper reason. Any test must first say what the solution was meant to achieve. But Rittel's first characteristic has already established that a wicked problem has no final formulation. You cannot check an answer against a question that can never be fully stated. So evaluation is not an escape from the wickedness. Evaluation is part of it.

This also tells us how to read a claim made earlier in this series: that closing an issue is a political act. The claim is reluctant, not triumphant. Rittel is not saying politics as a good way to settle design questions. He is pointing out that nothing else is available, because no criterion outside the participants can do the settling for them. And once we see the closure as forced rather than chosen, it gives the series something it has lacked: a clean way to tell design problems apart from every other kind.


### The Residue Is the Design

Some closures need no judgment. Call these criterial. A proof closes a theorem. A compiler closes the question of whether code is valid. A load test closes the question of whether a beam holds the floor up. Where a criterial closure exists, the problem is tame. It may still be fiendishly hard, but the difficulty lies in finding the answer, not in saying what would count as one.

A design problem is one where no such closure exists. Is this form right, for these people, at an acceptable cost to everything else that matters? No compiler can answer that. No proof, no load test. Judgment has to stand in, and judgment is answerable rather than correct.

This gives the Simon and Rittel quarrel its sharpest form. Simon's wager was that the part of design needing judgment could be made very small. Break an ill-structured problem into small enough pieces, he argued, and each piece becomes tame, closeable by a criterion, automatable in principle. Rittel's reply was that breaking the problem up is itself an act of judgment. The judgment can be moved around, but it cannot be removed. And it is not a leftover surrounding the real work. It is the work. Everything criterial in a project, everything that compiles and validates and passes, is exactly the part that was never design to begin with, however much skill it took. Design is what is left when every available test has been run and the question is still open.


### Two Senses of Working

Now put a generated prototype in front of this distinction, and watch the word working split in two.

A team prompts a tool and gets a working data visualisation. It renders. The axes are labelled. The interactions respond. The palette is colour-blind safe. The code passes its checks. Every one of these is a criterial closure, and every one is real. Nothing in this series disputes the machine's authority over them.

But there is a second sense of working, and it is the one the team actually cares about. Does the visualisation support the decisions it will be used for? Does its encoding mislead about cause and effect? Does it show these particular readers, under real time pressure, what they most need to see first? Who does it quietly disadvantage? None of these questions has a criterial closure. They are the wicked sense of working. And the prototype's fluency in the tame sense answers none of them, while looking as though it has answered them all.

This is the masquerade at the centre of current practice: a tame closure dressed as a wicked one. Earlier essays described how an artefact that arrives finished demotes the team from designers to approvers. The truth is worse than that. What the approvers are inspecting cannot, however carefully they look, reveal what was decided in the making of it. Even in tame work, Dijkstra warned that testing shows the presence of bugs, not their absence; a test can confirm a criterion is met but never prove it is fully met [2]. In the wicked sense of working there is no criterion at all to fall short of. So the prototype is not merely unverified. It is unverifiable.


### The Gap Is Not Ignorance

It is tempting to think this is a documentation problem, the kind better tools could fix. It is not, and seeing why means separating two different gaps.

When a human team makes an artefact, it works through the web of issues incompletely, tacitly, and almost never on paper. The design rationale literature spent two decades complaining about exactly this. But the working-through happened. There is a real answer to why the navigation is shaped this way, held in the heads and meetings that produced it, and it can be recovered: you ask the designer. Even a rough, after-the-fact reconstruction rests on a deliberation that genuinely took place. The gap here is one of record. The knowledge exists; it was simply never written down.

When a generative system makes the artefact, no deliberation took place at all. There is no answer to why, because the structure is merely the most probable continuation of a prompt against a corpus. This gap is of a different kind. No tooling can close it, because there is nothing on the far side to recover.

And here is the part with teeth. Asking the system why does not retrieve a reason. It produces one, generated under the very same conditions as the artefact, fluent and plausible and causally unconnected to how the thing was actually made. The explanation is no more grounded than the artefact it claims to explain. The same is true of a generated test suite, and of generated evaluation criteria, and of any other instrument the team might reach for to check the work. Each layer of checking is made by the same process whose output it is meant to check. Call it verification regress. The prototype is not just well-formed. It is unknowably well-formed, and that unknowability is not ignorance waiting for better instruments. It is a fact about how the artefact came to exist.

> The human web of issues is incomplete, but somebody is inside it. The generated web is incomplete too, but nobody is. There is no one there to recognise anything.


### The Inhabited Web

There is an honest objection here, and meeting it makes the argument stronger. Human designers also cannot list all the issues in their own webs. Much of the work is tacit; we know more than we can tell, as Polanyi put it, and that is truer of design than of almost any other practice. If the problem were simply that the web cannot be fully enumerated, human and generated artefacts would be in the same trouble.

But enumeration was never the point. The real difference is occupancy. The human web is incomplete, but somebody is inside it. Someone was present when the issues were closed. Their judgment was at work even where words were not, and they can be questioned and held to account. Above all, they can recognise an issue they had missed once it is raised. When a senior nurse says that patients reaching this screen have just been given a hard diagnosis, the designer's "I never thought of that" is a real event: an issue that was closed swings open again, in a mind that now holds it open. The generated web is incomplete too, but nobody is inside it. There is no one there to recognise anything. When the system acknowledges the issue, that acknowledgement is just one more generated continuation. The web does not reopen, because no one ever closed it in the first place [3].

This is also why testing the prototype cannot save it. Designing the test is itself an act of design. Someone has to say what working as intended means, and intended by whom has no answer here. The prompt-writer's intention covered only a few of the closures; the corpus supplied the rest; and no one owns the join. A test plan is a wicked artefact pressed into service as a criterial tool. Writing it with a generative system only adds another floor to the regress.


### Adoption

The conclusion is not to abstain from the tools, nor to demand that they explain themselves, which they cannot. It is to change the standing we give what they produce. A generated prototype should not be received as finished design waiting for sign-off. It should be received as a proposal that still owes its deliberation: an artefact in debt.

Paying the debt means re-entering the web the generation skipped. You walk the artefact one decision at a time. For each visible choice you ask what question it silently answers, whether that question was ever really ours, and whether we would answer it the same way. Then you record those closures as closures, this time with owners. Call it adoption. You do not audit an adopted child against a specification; you take responsibility for a history you did not write, knowing it can never be fully known. The tame closures can keep their automated tests, honestly labelled as tame. The wicked ones need a name beside them.

This is where the series' distinction finally pays out. The machines now perform, superbly, every closure a criterion can perform. What is left is everything a criterion cannot reach, which is to say the design. There is no immediate test, no ultimate test, and now, with generation, no inherited deliberation either. What there can still be is someone answerable. That was always the only verification a wicked problem ever had.


### Notes

[1] The fourth characteristic appears in Rittel and Webber, "Dilemmas in a General Theory of Planning" (Policy Sciences, 1973): a wicked problem has no immediate and no ultimate test of its solution, because any solution sends out waves of consequences over an unbounded period, and these cannot be fully appraised until they have run their course, which they never finally do. Read together with the first characteristic, the absence of a definitive formulation, it follows that the criteria for evaluating a design are themselves designed. The point this essay extends to generated artefacts was therefore present in the framework from the start.

[2] Edsger Dijkstra's remark dates from 1969 and concerns program correctness, a criterial domain; its force here is all the greater. If testing falls short of proving adequacy even where the standard of adequacy can be stated exactly, it cannot begin to prove adequacy where no such standard exists. Software engineering answered Dijkstra with formal verification, proving a program correct against a specification. That answer is closed to design, because in design the specification is the wicked part.

[3] The distinction between a gap of record and a gap of substance bears on the research direction often called explainable or interpretable AI. Whatever such methods recover about a model's inner computation, they recover facts about how an output was produced, not deliberations about the design situation, because no such deliberations occurred. An account of how a continuation was computed is not an account of why a navigation should be shaped this way. The tacit dimension of human design knowledge is treated in Michael Polanyi's The Tacit Dimension (1966) and runs throughout Schön's The Reflective Practitioner (1983); the argument here is that tacit knowledge with someone inside it and tacit knowledge with no one inside it are different conditions, however alike they look on the surface.

### Essays In The Series

[Index of essays on design practice in the age of generative AI](/articles/essays-on-design-practice-in-the-age-of-gen-ai/)
