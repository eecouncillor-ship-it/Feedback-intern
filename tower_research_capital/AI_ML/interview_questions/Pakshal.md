# Interview Questions
**Company:** Tower Research Capital
**Profile:** AI ML

**Result:** Shortlisted - 5 shortlisted, 4 rounds.

**Round 1**
A simple NLP problem: given a list of docs (str), a query and k, retrieve the k
nearest docs to that query. I had to explain my approach and then code it live
(allowed to refer to documentation online). I started with TF-IDF; he asked what
its disadvantages are - I stated them and then suggested using GPT-2 embeddings.
He asked why GPT-2, it should be an encoder architecture. I argued a bit about
how GPT-2 embeddings can work equally well. (I later realised my approach was
very inefficient and accepted that an encoder would have been better.)

**Round 2** (in person)
Implementation - integrate some functionality into an existing AI system and code
it live. Suppose you have a coding agent (blackbox for now) and it needs to take
inputs from multiple sources (gmail, telegram, user-defined etc.) and broadcast
its output to multiple destinations (gmail, github, user-defined etc.). Define
what classes would be needed and what functions each should have. It is important
to know what dataclasses and inheritance are and why they will be useful here. I
also suggested things beyond what he asked, like a `status_code` attribute on the
Output class to handle errors and a `session_id` attribute on both classes to
keep context. Then I coded it all. He seemed pretty satisfied with it.

**Round 3** - HR + technical, mainly on resume and projects. He asked whether I
know numpy, pandas and such but did not test me on them. He asked if I had worked
on time series data; I said no but would love to explore that domain too.

**Round 4** - By their global AI head, about a real agentic AI problem they are
currently working on and my approach to it.

All rounds except the 2nd were online. Overall, research projects on LLMs and a
project on agentic AI helped quite a lot.
