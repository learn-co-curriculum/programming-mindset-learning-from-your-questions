# Learning from Your Questions

## Learning Goals

- Identify effective methods of formulating questions
- Identify community standards for writing help requests

## Introduction

Before we get the right answer, we need to know how to ask the right question.
Figuring out how to ask the right question is a process of clarifying exactly
what we want the result to be as well as taking stock of all the information we
currently have. The more thought we put into asking questions, the better chance
we give ourselves of getting the right answer—either from others, or by
ourselves.

## Identify Effective Methods of Formulating Questions

Sometimes, it's clear to us what we don't know and what we need to ask for. But
often it's not so clear. Often, we don't know what we don't know and that makes
it difficult to formulate a question to ask about it. In these not-so-clear
cases, we can start with a process of determining what we _do_ know. Eventually,
this process will lead us to the right question.

Here's some steps to take when you're coming up with questions:

1. __Focus on small section of code.__ Don’t keep scanning several files for a
bug. Reducing the amount of material to sort through will allow you to isolate
the issues faster and easier.

2. __State your inputs.__ Double-check what data is getting pulled into your
program. Is your code reading the correct file? Were the values entered
correctly? If an input is wrong, it could throw off all of your code.

3. __State your outputs.__ Similarly, double-check what data is getting pushed
out of your program. If you're not getting out what you want, you might be able
to trace it backwards to the source of the problem.

4. __State your expectation.__ In order to determine whether your outputs are
right or wrong, you need to compare what you're getting to what you expected to
get.

5. __State your theory for what should have happened.__ You might have an idea
what you wanted to get as an result, but how did you get that idea? Double-check
your understanding of how the code is working. Did you miss anything that would
explain a different result?

6. __Check the docs to make sure your implementation works like you think it
did.__ As you're exploring your theory, take a look at any relevant reference
documentation. All developers have been in a position where they _thought_
something worked a certain way, but in fact did not. Double-check all the
available documentation for whichever tool or technique you're using so that you
can eliminate that as a contributing factor to the current issue.

7. __Test the implementation in IRB.__ There's no substitute for running bits of
your code in a safe environment to make sure it functions how you intend it to
function. IRB is here to help. You can always test out code there while not
disturbing the rest of what you've written.  Even senior developers often find
themselves entering:

```ruby
x = [1,2,3]
z = []
...
```

So that they can be sure they understand some method (in this case, probably an
`Enumerable` or some aspect of an `Array`).

8. ___If necessary at this point_, submit the question.__ Still have questions?
Now you should at least have a clearer idea of what specifically you need to ask
for. So _now_ you can ask.

Here's the secret about asking questions: when you follow a series of steps like
these, you're running through all of the questions someone else might ask _you_
when they're trying to gather enough information to solve your problem, and,
often, this is enough to uncover the solution on your own. But even if it's not,
you've done all the necessary prework for narrowing down what you need to ask
someone else for help with, which means they will be able to help you more
effectively, and get you back to coding faster.

## Identify Community Standards for Writing Help Requests

When we developers come to a point in our programming where we need to ask for
help, we follow the process above. If the reason still isn't forthcoming we have
a perfectly-formulated question to send out into a professional coding community
like Stack Overflow. Here's how to use those steps with approaching the
community in mind.

- __Avoid posting too much code.__ Professional programmers have very little
time. If you haven't done any work to help yourself, they won't bother to help
you either. Show only the buggy section of code. If you struggle to narrow down
the bit that is causing you trouble, that tells you that you might need to ask a
larger, more fundamental question. Or perhaps you should try breaking down the
code a bit better before you ask your question.

- __Give all available details: inputs, outputs, theories, what you've done so
far.__ Someone reading your question might not have your programming
language installed or they might be on a slow network. Make sure they have
the facts handy so they can mentally "play" your code.

- **Be polite.** Phrases such as "I'm new to..." or "I can get this to work in
(other language)" help your collaborator gauge their response. Always thank the person
who provides the winning response and mark their response as "correct." Keep in
mind that your questions will stay on the site long past your coding snag. Future
employers can decide a lot about how you present yourself and what kind of person
you are to work with from these questions. Leave your best impression, always.

- **Uphold the Community Standards.** It is entirely appropriate to ask colleagues
or collaborators to follow this process when you are asked to help them as well.
If someone asks you a question and it's clear they've not followed these steps,
it's _entirely_ appropriate to suggest these steps so that you can more clearly
understand their problem. Your time, as a developer, is valuable. By insisting
that _others_ respect your time, _you_ will respect it as well.

Additionally, many collaboration sites hold a Code of Conduct. Operate within in
it. While many developers cover their insecurities by being snarky, misogynist,
and generally nasty, Flatiron learners radiate positivity.

## Conclusion

If we follow a set of effective methods for formulating questions, we are
generally able to either come up with the answers on our own or present a
question that is targeted, informed and most likely to produce the result we
need.

## Resources

- [Stack Overflow: How to Ask](https://stackoverflow.com/help/how-to-ask)
