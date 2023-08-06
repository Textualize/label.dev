# The Art of the Minimal Reproducible Example

When submitting an issue you can greatly improve the chances of getting a quick fix by including a minimal reproducible example (MRE).

!!! tip

    We aren't talking about Meals, Ready to Eat here.

## What is a MRE?

Simply put, an MRE is a short piece of code that can reproduce the issue.

If you can boil your problem down to a few lines, it will help the maintainer diagnose the problem. The maintainer can use it as a starting point for their investigation, and may end up using your code in a regression test.

Here are a few tips to create an MRE:

- Mention any external libraries your code requires.
- Make sure it runs by simply cutting and pasting the code.
- Include any additional files your code may need.
- If it's not obvious, include brief instructions to the maintainer on how to run the code.

An MRE is good practice for solving bugs in general.
You may find after doing the work that you understand the issue better.
In fact, it may reveal that the bug is not where you thought it was!

## What if you can't make a MRE?

It isn't always easy to produce some code to reproduce an issue.
Perhaps the problem occurs only under certain conditions or with data that you can't copy in to the issue.
Or it could be that it is very difficult to narrow down the problematic code.

Maintainers will understand this. So don't worry if you can produce a MRE.

## Links

- [Craft Minimal Bug Reports](https://matthewrocklin.com/minimal-bug-reports.html) by Matthew Rocklin
