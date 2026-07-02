---
title: "III. The Quarrel That AI Reopened"
date: 2026-06-16
summary: "On why a fifty-year-old argument in design theory has suddenly become a practical question."
linkedin_url: "https://www.linkedin.com/pulse/quarrel-ai-reopened-venkatesh-rajamanickam-ffdsf"
author: "Venkatesh Rajamanickam"
source: "LinkedIn"
---

{{< article-byline >}}

<p class="article-read-link"><a href="https://www.linkedin.com/pulse/quarrel-ai-reopened-venkatesh-rajamanickam-ffdsf" target="_blank" rel="noreferrer">Read on LinkedIn</a></p>

![The Quarrel That AI Reopened](/articles/images/the-quarrel-that-ai-reopened.jpeg "Herbert Simon (left) in a chess match against Allen Newell")

### On why a fifty-year-old argument in design theory has suddenly become a practical question.

<i>Note: This essay extends a series. The [The Brief Always Arrives Wrong](/articles/the-brief-always-arrives-wrong/) argued that design's most consequential work is the constituting of problems, not the production of artefacts. [The Web of Issues](/articles/the-web-of-issues/) drew on Horst Rittel to argue that the design process is irreducibly argumentative. This essay goes back one step further, to the quarrel from which Rittel's position emerged, and to the man on the other side of it.</i>


In 1969 Herbert Simon published The Sciences of the Artificial, a small book with an enormous ambition: to establish design as a rigorous science. Simon was perhaps the most formidable polymath of his century; an economist who would win the Nobel Prize, a founder of artificial intelligence, a cognitive psychologist, an administrator and theorist of organisations. His claim was that design is not the special preserve of architects and engineers but the core of all professional activity. Everyone designs, he wrote, who "devises courses of action aimed at changing existing situations into preferred ones." The doctor designing a treatment, the manager designing a policy, the teacher designing a curriculum: all of them, on Simon's account, are doing the same kind of thing, and that thing can be studied, formalised, and taught [1].

What Simon meant by design was precise. A design problem is a problem space: a set of possible states, a set of operators for moving between them, and a way of recognising when a satisfactory state has been reached. The designer searches this space. She does not optimise; Simon was too good a psychologist to believe in optimisation. Real agents have bounded rationality, limited time, limited attention, limited computational capacity, and so they satisfice: they search until they find a solution that is good enough, and then they stop. This was a humane and realistic correction to the economic fantasies of perfect rationality, and it earned Simon his Nobel. But it kept one assumption intact: that the problem space exists before the search begins. The designer's work happens inside a structure that is given.

Four years later, Horst Rittel and Melvin Webber published the paper that the [previous essay](/articles/the-web-of-issues/) in this series examined at length. Design problems, they argued, are wicked: they have no definitive formulation, because every formulation already implies a direction of solution; they have no stopping rule; their solutions are not true or false but good or bad, and good for whom is always contested. The deepest cut was aimed exactly at Simon's intact assumption. The problem space is not given. Constructing it is the design act, and the construction is political: a judgment about what counts as the problem, made by particular people with particular values, answerable to those affected.

The same year, in a paper titled "The Structure of Ill-Structured Problems," Simon replied in effect, though not by name [2]. Apparently wicked problems, he argued, are wicked only when viewed whole. In practice, the designer at any given moment faces a local sub-problem that is perfectly well structured, and the apparent wickedness of the whole dissolves under decomposition. An architect designing a house does not confront the entire ill-structured problem of dwelling; she confronts, this morning, the tractable question of where the staircase goes. The wicked problem is an accounting illusion; up close, it is tame all the way down.

These two positions are not complementary perspectives. They contradict each other at the root. Either the formulation of the problem is inside the design process, contested and political, as Rittel held, or it is outside it, given or unproblematically constructible, as Simon's framework required. Fifty years of design theory has not resolved the question. It stopped asking it.


### Why the Field Stopped Arguing

Neither side won the quarrel; they partitioned the territory. Simon's account went where formalisation was welcome: engineering design, operations research, computer science, and eventually human-computer interaction, a field that owes its founding vocabulary to him. Rittel's account went where formalisation had visibly failed: urban planning, architectural theory, participatory design, and the design research tradition that runs through the Design Methods movement's second generation. Each side could plausibly claim its own domain as evidence. Bridges and compilers seemed to vindicate Simon. Cities and public services seemed to vindicate Rittel.

Practice, meanwhile, borrowed from both without noticing the contradiction. A contemporary product team runs discovery research in Rittel's spirit on Monday, treating the problem as unsettled and the users as the authority on what matters; and writes acceptance criteria in Simon's spirit on Tuesday, treating the problem as specified and the remaining work as search. The same designer moves between the two framings several times a day without experiencing any friction, because the truce had no practical cost. The tools were weak. Whether design was fundamentally argumentation or fundamentally search made no difference to how Tuesday went.

That has now changed, because one side of the quarrel has been built.


### Simon, Implemented

A generative AI system is Simon's designer, constructed at industrial scale. The correspondence is not loose or metaphorical; it is close to literal. The problem space has become a latent space, learned from the corpus of past design work. Search has become sampling. The evaluation function has become a loss function steered by a prompt. Satisficing has become the human at the keyboard pressing regenerate until the output looks acceptable, then stopping. Even the intellectual lineage is direct: the research programme Simon founded with Allen Newell in the 1950s, modelling problem-solving as heuristic search through symbol structures, is the ancestral form of the systems now generating interface designs on demand [3]. What was a philosophical position in 1969 now ships with a subscription.

And within its jurisdiction, it works. Ask a generative tool for a checkout flow and it will search the space of checkout flows with a fluency no human team can match, returning in seconds a satisficing point that embodies the accumulated conventions of the genre: the address fields in the expected order, the payment options in the expected hierarchy, the reassurances in the expected places. If the design problem really is what Simon said it is, this is not assistance. It is the thing itself.

Which is precisely why Rittel's objection, written against the paper methods of the 1960s, lands harder against the software of the 2020s. Consider what the checkout tool cannot ask. Should this purchase be frictionless? For a grocery application, perhaps. For a gambling product, a buy-now-pay-later service aimed at people already in debt, a children's game with in-app purchases, the question of whether spending should be made easy is the design problem; everything downstream is detail. But that question does not live inside the problem space. It determines which problem space gets searched. A system that can only search must inherit an answer to it, and the answer it inherits is whatever the corpus embodies: the accumulated commercial preference for frictionlessness, encoded so deeply in existing checkout flows that it no longer looks like a decision at all.

Or consider a government team using a generative tool to draft a benefits eligibility checker. Before the first screen is generated, a position has been taken on a question nobody asked aloud: is the purpose of this system to maximise correct claims or to minimise incorrect ones? Those two purposes produce different question orders, different defaults, different tones, different error states; two different problem spaces, each perfectly searchable, each embedding a different politics about whom the state should inconvenience when in doubt. Simon's framework has no place to put this question. Rittel's framework is about almost nothing else.

This is the pattern the previous essay called closing issues without opening them, and the quarrel explains why it is not an accident of immature tools. It is the position Simon's side of the argument takes, made operational. The closure does not happen during the search, where it might be noticed. It happens in the construction of the space the search runs in, before the first token is generated, invisibly, by no one.

> Simon governs the inside of the problem space. Rittel governs the drawing of it. The machines have industrialised the inside; the outside remains where it always was: between people, in rooms, answerable.

### The Jurisdictional Settlement

It would be a poor conclusion, and an unjust one, to cast Simon as the villain of this story. Bounded rationality and satisficing were humane ideas, framed against a far worse fantasy: the omniscient optimiser of mid-century economics. Simon never claimed designers were calculating machines; he claimed they were limited creatures coping intelligently with complexity, and he was right. He was also right that a great deal of design work genuinely is search. Once a framing is settled, once the issues have been argued and closed and the closure is understood and owned, finding a good solution within that framing is exactly the kind of work he described, and machines that do it well are genuinely valuable. The designer who refuses the help out of professional pride is not defending the discipline; she is wasting the afternoon.

The resolution the quarrel actually admits is jurisdictional. Simon governs the inside of the problem space. Rittel governs the drawing of it. The error of the last fifty years was treating these as rival accounts of the same territory when they are accurate accounts of adjacent ones; the error of the next ten would be letting the automation of Simon's territory quietly annex Rittel's. Because that is the live risk. A tool that requires a well-structured input exerts a steady pressure on organisations to pre-structure their problems: to write the prompt, settle the framing, flatten the web of issues into a specification, faster and earlier and with fewer people in the room. The wickedness does not go away. It is dealt with upstream, implicitly, by whoever writes the prompt, which increasingly means it is not dealt with at all.

The profession's task follows directly. It is not to compete with the search; that competition is lost, and losing it costs nothing that matters. It is to hold the jurisdiction the search cannot enter: the formulation of the problem, the argument over the framing, the explicit and accountable closing of the issues that determine which space is worth searching in the first place. Fifty years ago that was a theoretical position in an academic quarrel. The machines have made it a job description.

The brief always arrives wrong; the issues it contains must be argued rather than optimised. The quarrel between Simon and Rittel tells us why the new tools, however fluent, are not neutral in that argument. They take a side. And the side they take is the one design theory spent half a century learning to distrust; not because it is useless, but because it is incomplete in exactly the place where the consequences live.

The [next essay](/articles/two-stopping-rules/) takes the quarrel down to its sharpest point of contact, on how designers decide that the designing is done.


### Notes

[1] Simon's definition appears in The Sciences of the Artificial (MIT Press, 1969), which went through three editions in his lifetime, each revised. The book originated in lectures delivered at MIT, and its central chapter, "The Science of Design: Creating the Artificial," was for decades the most cited theoretical statement in design research; a status it has gradually ceded to Rittel and Webber's paper, a reversal of fortune that is itself a comment on which account practitioners found truer to their experience.

[2] The coincidence of dates is striking and underexamined: Rittel and Webber's "Dilemmas in a General Theory of Planning" appeared in Policy Sciences in 1973, the same year Simon's "The Structure of Ill-Structured Problems" appeared in Artificial Intelligence. The two papers do not cite each other, but they answer each other almost line by line, and they fix the two poles between which design theory has oscillated since. That Simon published his side in an artificial intelligence journal is, in retrospect, the detail that mattered most.

[3] The lineage from Simon and Newell's General Problem Solver (1957 onwards) to contemporary generative systems is not a straight line; the connectionist methods underlying modern models were for decades the rival camp to Simon's symbolic approach. But the framing survived the change of machinery: a problem is a space, designing is searching it, and the goal is a satisfactory point within it. On that framing, the two camps never disagreed.

### Essays In The Series

[Index of essays on design practice in the age of generative AI](/articles/essays-on-design-practice-in-the-age-of-gen-ai/)