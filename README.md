# Questionable

> How do I ask a good question?

**That is a great question!**

## TL;DR

Use this copypasta to answer every *questionable* questions.  
Make sure to include the source when quoting this guide :)

```markdown
How do I ask a good question?

## "Can anyone help me with ABC?"
- Don't ask if you can ask, just ask.
- Ask for an answer, not 'someone who can help'.

## You have problem X, you tried Y.
- How do I make Y work? (X)
- How do I solve X? I tried Y. (O)

## "It doesn't work" just doesn't work.
- What's the goal?
- What have you tried?
- What's wrong with current behavior?

## Read the damn error. Seriously.
- 90% of the time it tells you exactly where and what is wrong.

Learn more at <https://github.com/WieeRd/questionable>
```

## 1. Don't Ask For Help, Ask a Question

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

That is *not* a question, that's a complaint.  
What is "it"? What exactly is "not working"?

- **Clarify the goal** in terms of expected input, output, and their relation.

- **Provide the code** to be inspected.  
  Extract the relevant part of the code to eliminate unnecessary details.  
  Ideally, make the extracted part [executable by itself][MRE].

- **Explain what's wrong** with current behavior.  
  Get a sample output and compare it with the expectation.  
  Always provide *full* error message. Not just the error code.

```text
I want my program to {expected output} upon {expected input}.
I tried {code example} but it produces {error | sample output}.
This was not expected because {reason}.
```

[MRE]: https://stackoverflow.com/help/minimal-reproducible-example

## 4. Ask for What to Ask

You might be so clueless that you don't know where to even start.  
But don't be tempted to ask a bad question that lacks information.  
Instead, ask for a way to improve your question.

- **Ask for a way to gather more information.**  
  e.g. If a program freezes, ask for a way to check the logs.

- **Ask for learning materials.**  
  Don't dive straight to your abstract, ambiguous, and overambitious goal.  
  When it is clear you lack knowledge about the topic, you should learn.  
  e.g. How do I create my own Jarvis? → What are some good resources for ML?

## Learn More

Many details were omitted to keep this guide absolutely minimal.  
Below are list of more comprehensive materials for a further reading.

- <https://stackoverflow.com/help/how-to-ask>
- <http://catb.org/~esr/faqs/smart-questions.html>
- <https://codeblog.jonskeet.uk/2010/08/29/writing-the-perfect-question/>
- <https://codeblog.jonskeet.uk/2012/11/24/stack-overflow-question-checklist/>

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)
