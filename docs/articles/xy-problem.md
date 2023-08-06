---
description: "The XY Problem and how to avoid it!"


---

# XY Problem

The XY Problem has wasted countless time on Github issues and technical support channels since their inception &mdash; and it likely existed in some form even before the computing era.

Here's how the XY Problem is typically described, in the context of Open Source.

A developer wants to do X, and comes to the conclusion that they need Y to achieve it.
The developer attempts Y but runs in to problem(s) with the implementation.
Not wishing to give up, the developer goes to the maintainer's tech support forum to ask for help with Y.

The problem occurs when Y is *not* the best solution for X.
The maintainer wants to help, but Y seems like a strange application of their code they hadn't conceived of.
This can lead to an extended back and forth where the maintainer gets more confused as to what the developer wants, and the developer feels that the maintainer is being intentionally difficult.

Such fruitless exchanges can be eliminated if only the developer explained what problem they were trying to solve.
This gives the maintainer the opportunity to offer an alternative solution, which is more likely to work.

It's a very human problem.
I'm sure there are a lot of psychological factors involved.
Very likely the [sunk cost fallacy](https://en.wikipedia.org/wiki/Sunk_cost) is at play: the more time and effort the developer has put in to Y, the more they will resist attempts to dissuade them.
It's also not related to the developer's technical ability.
Experienced developers can still fall in to this trap.

## What can the developer do?

The best way to avoid an XY Problem is to summarize what you are trying to achieve in the first paragraph when you ask for help with your solution.
It doesn't need to be detailed: one or two sentences is generally enough.

## What can the maintainer do?

It is not always easy to recognize the XY problem, but if there does seem to be a disconnect between you and the developer, it is very often this issue.
If the developer wants to do something with your code you consider out of scope, you may want to inquire why the developer considered it a requirement.
It may be a genuine use case you hadn't considered or it may be the XY problem. But you won't know until you understand the developer's thought processes.

## Links

- [XY Problem on Wikipedia](https://en.wikipedia.org/wiki/XY_problem)
- [xyproblem.info](https://xyproblem.info/)
- [XY Problem on StackExchange](https://meta.stackexchange.com/questions/66377/what-is-the-xy-problem)
