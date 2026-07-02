---
title: "IV. Two Stopping Rules"
date: 2026-06-21
summary: "On how designers decide that the designing is done."
linkedin_url: "https://www.linkedin.com/pulse/two-stopping-rules-venkatesh-rajamanickam-vaxnf"
author: "Venkatesh Rajamanickam"
source: "LinkedIn"
---

{{< article-byline >}}

<p class="article-read-link"><a href="https://www.linkedin.com/pulse/two-stopping-rules-venkatesh-rajamanickam-vaxnf" target="_blank" rel="noreferrer">Read on LinkedIn</a></p>

![Two Stopping Rules](/articles/images/two-stopping-rules.jpeg "Press room in The Times of India office in Bombay, 1898")

### On how designers decide that the designing is done.

<i>Note: This essay continues a series. The [The Brief Always Arrives Wrong](/articles/the-brief-always-arrives-wrong/) argued that design's most consequential work is the constituting of problems. [The Web of Issues](/articles/the-web-of-issues/) drew on Horst Rittel to argue that the design process is irreducibly argumentative. [The Quarrel That AI Reopened](/articles/the-quarrel-that-ai-reopened/) set Rittel against Herbert Simon and proposed a jurisdictional settlement: Simon governs the inside of the problem space, Rittel the drawing of it. This essay takes the quarrel down to its sharpest point of contact, a question both men answered and almost nobody teaches.</i>


Every design project ends. The ending is the least examined event in the entire process. Design education teaches how to begin: how to research, how to reframe, how to generate alternatives. It teaches how to proceed: how to iterate, how to critique, how to test. It does not teach how to stop, and most practitioners, asked when a design is done, will give an answer that is really a description of their calendar. The sprint ended. The budget ran out. The launch date arrived. The client stopped replying. These are endings, but they are not answers; they are what happens in the absence of an answer, and the profession has learned to live inside that absence so comfortably that it has stopped noticing the question.

The question deserves better, because two of the most serious thinkers ever to consider design answered it directly, and their answers are incompatible in a way that has suddenly become practical. Herbert Simon said: you stop when the solution is good enough. Horst Rittel said: there is no rule for stopping; there is only stopping you can defend. Between those two answers lies most of what matters about professional judgment. And alongside them, in the last few years, a third stopping rule has quietly installed itself in design practice, one that neither man proposed and both would have recognised as dangerous: you stop when the output looks finished.

### Good Enough Is a Number

Simon's answer came first and remains the most useful piece of intellectual machinery he gave the field. Real designers, he observed, do not optimise; the space of possible designs is too large, time is too short, and human cognition is too bounded for anyone to find the best solution to anything. What designers actually do is satisfice. They carry an aspiration level, an internal threshold of acceptability, and they search until they find a solution that clears it. Then they stop. The aspiration level is not fixed; when search proves easy, it drifts upward, and when search proves costly, it drifts down [1]. Anyone who has watched a team's ambitions for a feature quietly shrink across a difficult sprint has watched aspiration adaptation working exactly as Simon described it.

Notice how much of design practice is satisficing made institutional. The usability testing convention of five participants is an aspiration level: not the number that finds every problem, but the number folklore settled on as good enough to find the problems worth finding at a cost worth paying [2]. An accessibility target of WCAG AA is an aspiration level: a published threshold that, once cleared, licenses the team to stop. A design system's definition of done, a performance budget, a minimum task-completion rate in testing; all of these are Simon's stopping rule, written into process documents. They have a genuine virtue, which is honesty. A team that says "we stop at AA, tested with five users, above a ninety per cent completion rate" has made its stopping criteria explicit and inspectable, which is more than most teams can say.

Within its terms, the account is unimpeachable. The trouble is the terms. An aspiration level can tell you when you have searched enough. It cannot tell you whether you set the level rightly, or who set it, or who is left outside it when you stop. Those questions are not in Simon's framework. They are the whole of Rittel's.

### Defensible Is Not the Same as Done

Among the defining characteristics Rittel and Webber gave wicked problems, the second is the bluntest: wicked problems have no stopping rule [3]. There is no test that tells a designer the work is complete, because the problem itself has no definitive formulation against which completeness could be measured. The designer stops, Rittel wrote, for reasons that are external to the logic of the problem: she runs out of time, money, or patience, or judges that the result is good enough to proceed with. On the surface this sounds like Simon's satisficing with the optimism removed. It is something different in kind. For Simon, the aspiration level is a feature of the searcher's cognition. For Rittel, the decision to stop is a judgment for which someone is answerable, because every stopping leaves issues closed that could have been closed otherwise, and the people affected by those closures are entitled to an account of them.

Return to the accessibility target, because it shows the difference exactly. Stopping at WCAG AA is a Simon stopping: the level was published, the audit passed, the search ends. But the choice of AA rather than AAA was a closure of an issue. So was the decision about which assistive technologies to test with, and which not to. So was the implicit judgment about whether compliance, a property of the artefact, is the same thing as accessibility, a property of the encounter between the artefact and a particular person using a screen reader on a slow connection in a language the testing never covered. A team can clear its aspiration level and still owe an answer to the question good enough for whom. Simon's rule tells you the search is over. Rittel's account tells you what you now have to be able to defend.

This is why the two stopping rules are not rivals so much as layers. The aspiration level governs the inside of the work: it is how a bounded team gets anything finished at all. The defensibility requirement governs the setting of the level itself, and it cannot be delegated to a threshold, because thresholds are exactly the things it interrogates. A profession needs both, and needs to know which one it is using at any given moment. Which brings us to the third rule, whose entire danger is that it erases the distinction.

### The Third Stopping Rule

A generated design arrives finished. This sounds like praise and is actually the problem. A human designer's work-in-progress declares itself: the sketch is rough, the wireframe is grey, the prototype has lorem ipsum in the corners, and this roughness is information. It tells everyone in the room how settled the thinking is, which questions are still open, how much weight the artefact can bear. A generative system produces no such signal. Its first draft has the typographic polish, the consistent spacing, and the confident microcopy of a final one, because surface finish is what the corpus taught it best. The rendering is complete even when the reasoning has not begun.

This creates a stopping rule that operates on the viewer rather than the maker: you stop when the output looks done. Watch a team use a generative tool and the rule is visible in the loop itself. Prompt, generate, glance, regenerate; prompt, generate, glance, accept. Each glance is a stopping decision, made in seconds, on the only evidence available at a glance, which is plausibility. Nobody in the loop set an aspiration level, because nobody articulated what the design needed to achieve before the generating began; the threshold is being discovered by feel, output by output, and the feel is calibrated by surface coherence. This is Simon's stopping with the aspiration level set by the corpus instead of the team, and Rittel's accountability located nowhere, because a stopping made by glance leaves no one who decided and nothing that was decided, only an output that survived.

The failure is not hypothetical. The previous essays described how a generated onboarding flow closes issues invisibly; the stopping rule explains why the closures stay closed. A team that receives a rough sketch interrogates it. A team that receives a finished-looking artefact reviews it, and review is a fundamentally weaker posture: it accepts the framing and inspects the execution. Plausibility does not just end the search prematurely. It demotes everyone present from designer to approver.

<blockquote style="font-size: 1.2rem; font-style: normal;">Simon's rule, used knowingly, is a tool. Rittel's requirement, taken seriously, is a discipline. The third rule, left unexamined, is a surrender that does not know itself to be one, performed one glance at a time.</blockquote>

### A Studio That Took Stopping Seriously

The practical response is not to ban the tools; it is to take the stopping decision back from them, and that turns out to be concrete, teachable work. It would mean setting the aspiration level before the first generation rather than discovering it by glance: writing down, in advance, what this design must achieve, for whom, at what threshold, so that generated output is measured against a criterion the team owns rather than a finish the corpus produced. It would mean treating every acceptance of a generated artefact as a closure in Rittel's sense and recording it as one: what issues does this output settle, who is settling them, on what grounds. It would mean a stopping memo at the end of every project, a single page that no current process document contains: we stopped here, this is who decided, these are the issues we closed knowingly, these are the ones we left open, and this is what we gave up. And it would mean design education teaching stopping as a named skill, with the same seriousness it teaches research and ideation; not how to end a project, which the calendar already enforces, but how to end one defensibly, which nothing currently enforces at all.

None of this slows the work. The aspiration level takes an hour to set; the stopping memo takes an afternoon; the closures are happening anyway and recording them costs only the honesty of admitting they are closures. What it changes is where the stopping decision lives. Simon's rule, used knowingly, is a tool. Rittel's requirement, taken seriously, is a discipline. The third rule, left unexamined, is neither; it is a surrender that does not know itself to be one, performed one glance at a time.

The brief always arrives wrong, and the issues it contains must be argued rather than optimised. But arguments, like searches, have to end, and a profession is defined as much by how it ends things as by how it begins them. The machines have made ending effortless. That is exactly why it can no longer be left unexamined: the one decision the tools now make by default, the decision that the work is done, is the one decision that was always, irreducibly, ours to defend.

In the [next essay](/articles/the-resolution-of-the-argument/) I return to the web of issues and ask the question the earlier essay left unexamined: what are the issues, positions, and arguments made of?

### Notes

[1] Satisficing first appears in Simon's "A Behavioral Model of Rational Choice" (Quarterly Journal of Economics, 1955), with roots in Administrative Behavior (1947); the term was Simon's deliberate coinage to mark the distance from optimising. The dynamics of aspiration levels, rising when search is cheap and falling when it is costly, are developed there and in his later work on bounded rationality, and they remain one of the few pieces of mid-century decision theory that describes observable studio behaviour without embarrassment.

[2] The 5 participant convention in usability testing derives from work by Jakob Nielsen and Tom Landauer in the early 1990s on the diminishing returns of additional test users. Its afterlife is a study in how an aspiration level hardens into folklore: a cost-benefit calculation made under particular assumptions about problem frequency and study design became, within a decade, a number teams cite without the assumptions, which is to say a stopping rule with its rationale amputated. Rittel would have recognised the pattern; it is design rationale lost in transmission, at the scale of an entire profession.

[3] The absence of a stopping rule is the second of the ten characteristics of wicked problems in Rittel and Webber's "Dilemmas in a General Theory of Planning" (Policy Sciences, 1973). It is worth noting how carefully it is phrased: the claim is not that designers never stop, which would be absurd, but that the stopping is never derivable from the problem itself, which relocates it from logic to judgment, and therefore from method to accountability.

### Essays In The Series

[Index of essays on design practice in the age of generative AI](/articles/essays-on-design-practice-in-the-age-of-gen-ai/)