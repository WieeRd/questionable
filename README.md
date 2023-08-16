# Questionable

> How do I ask a good question?

**That is a great question!**

[[English](https://github.com/WieeRd/questionable)]
[[한국어](/i18n/ko.md)]

## TL;DR

Use this copypasta to answer every *questionable* question.  
Make sure to include the source when quoting this guide :)

```markdown
> How do I ask a good question?

## "Can anyone help me with ABC?"
- Don't ask if you can ask, just ask.
- Ask for an answer, not 'someone who can help'.

## You have problem X, you tried Y.
- How do I make Y work? (X)
- How do I solve X? I tried Y. (O)

## "It doesn't work" just doesn't work.
- What's the goal?
- What have you tried?
- What's wrong with the current behavior?

## Read the damn error message. Seriously.
- 90% of the time it tells you exactly where and what is wrong.

Learn more at <https://github.com/WieeRd/questionable>
```

## 1. Don't Ask for Help, Ask a Question

> Can anyone help me with ABC?  
> Is there anyone who uses ABC?

You're wasting time. Just ask the question.  
This also implies that you're asking for "someone who can help";  
expecting someone else to solve the problem for you.  
Don't. Write a proper question and ask for an *answer*.

Learn more at <https://dontasktoask.com/>

## 2. Describe the Goal, Not the Solution

You have problem X, your solution Y failed.

- How do I make Y work? (X)
- How do I solve X? I tried Y. (O)

**What if Y was a wrong approach in the first place?**  
It can end up wasting both you and the answerer's time with confusion.  
Remember that the real goal is to solve X, not fixing Y.

Learn more at <https://xyproblem.info/>

## 3. Provide Enough Information

> It doesn't work.

That is not a question, that's a complaint.  
What is "it"? How exactly is it "not working"?

### What's the Goal?

Describe the problem in terms of input, output, and their relation.

### What Have You Tried?

Describe your attempt in detail, with the used code.  
Extract the relevant part to eliminate unnecessary details.  
Ideally, make the extracted code [executable by itself][MRE].

[MRE]: https://stackoverflow.com/help/minimal-reproducible-example

### What's Wrong?

Describe the current behavior and compare it with the expectation.  
Always provide the *full* error message. Not just the error code.

```text
I want my program to {expected output} upon {expected input}.
I tried {code example} but it produces {error | output example}.
This is not what I intended because {reason}.
```

## 4. Read the Damn Error Message

> (screenshot) Why am I getting this error?

Errors are not just scary wall of text meant to frustrate us.  
With the exact line number and brief description of the cause,  
90% of the time they are more than enough to solve the problem.

**Before you ask, please *read*, and not just *see*, the error message.**

## Learn More

This guide is meant to be absolutely minimal for fast and easy read.  
If you're looking for more detailed resources for a further reading,  
Here are some of the most useful and well known resources.

- <https://stackoverflow.com/help/how-to-ask>
- <https://stackoverflow.com/help/minimal-reproducible-example>
- <http://catb.org/~esr/faqs/smart-questions.html>
- <https://codeblog.jonskeet.uk/2010/08/29/writing-the-perfect-question/>
- <https://codeblog.jonskeet.uk/2012/11/24/stack-overflow-question-checklist/>

## Contributing

Want to help out improving and translating this guide?  
See [CONTRIBUTING.md](/CONTRIBUTING.md)
