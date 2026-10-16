# Who Is Jev?
## Fun with Decision Models

Talk Abstract

Just when you had gotten used to LLMs, the next hype arrived: decision models. Since September 2026, everyone has been talking about Jev, a model that can't write a single sentence and is proud of it. So who is Jev, and should you care?

A decision model doesn't generate text. You hand it a state and a set of typed questions, and it answers with a choice, a score, or a probability, in a fraction of a second and at a fraction of the cost of an LLM call. That makes it a good fit for the many small decisions hidden in our software, the ones we solve today with if-else cascades, hand-written rules, or an LLM that is far too big for the job.

First, a quick look at what happened and why the hype took off. Then we open the IDE: in live coding, I take a decision buried in ordinary code and hand it to Jev, showing how you call a decision model, what comes back, and where it sits next to an LLM and plain old code. Jev isn't the only option, though, so we also look at the alternatives, from local models you run on your own machine to proprietary ones. Finally, we go through use cases, from sensible ones like routing, moderation, and sorting to the purely fun ones. And what is a game, if not a state and a question about the next move? So we end by letting Jev play, live on stage.

Key Takeaways

- What a decision model is, and how it differs from an LLM, a classic classifier, and a rules engine.
- How to call a decision model from your own code, shown live in the IDE.
- Which alternatives to Jev exist, local and proprietary, and when to pick which.
- How to spot good candidates in your codebase, and when an if-else or an LLM is still the better choice.
