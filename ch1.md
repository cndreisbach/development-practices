# Asking technical questions

Asking technical questions is the fundamental skill of a developer. All other skills build on this skill. Whatever your skill level, even as a senior developer, you will have questions you cannot answer by yourself. Asking questions is hard. It can feed our worries about our own skills. It can make us feel embarrassed.

## Before asking

Before you ask a question, you need to do your own research. While doing this research, you must make certain not to dig a hole. Do not spend so much time researching that you become frustrated and more confused. Do not try so many things that you cease to know how your code works.

Most technical questions are about how to use a piece of technology or how to fix a bug. You approach these in similar ways.

If your question is how to get started with a task or technology, start by reading or listening to a podcast or watching a video if that applies. I'll refer to all this as reading from now on. Record what you have read. The amount of time you spend will vary by your skill level. If you are a junior developer, spend no more than 15 minutes!

If you try to get something working in code, keep that code as an example. Do not delete attempts that don't work. Make a new attempt and keep each of them.

If your question is about a bug, reading will also be your first step. Read the error message, including its stacktrace. This is a hard problem for junior developers. Terms and conditions, as well as arcane error messages, have conditioned modern technology consumers to ignore walls of text. This is a bad habit that you must correct to be a good developer. Read the error message. If there are terms in the error message that you do not know, that may be a good thing! Specific error messages are easy to search for with Google.

**TODO**: insert image of stacktrace

A stacktrace shows where the program errored out and bubbles up through all the function and method calls that got the program to that line of code. Your bug may not have occurred on that line. With modern software frameworks, a stacktrace may start deep within the framework. Look until you find your own code.

Once you have read about your bug and think you have an idea of how to fix it, give that a try. When doing this, record what you tried and back out of your attempt before trying something new. Too often, I have seen people dig a hole by layering fixes on top of one another, ending up with them making code changes they don't understand to see what happens. Stop long before you get there. A junior developer should spend no more than 15 minutes trying to debug their problem.

## Identifying your question

The first thing you must do is identify your actual question. While this is a common struggle for junior developers, I've seen senior people with the same issue. Too often I've had people show me 100 lines of code and say "It doesn't work" instead of formulating a question.

If your question is how to get started with a task or a technology, identify what you have read, watched, or listened to so far. Dig in. What specific details do you understand? What details do you not understand?

> I was doing a project with the [Hugo static site generator](http://gohugo.io/). I needed to create a simple "about me" page, but couldn't figure out how. Digging deeper, I saw how to make blog posts and other serialized content, but now how to make a page that didn't become part of a larger feed. I tried to make a page, but it showed up as a post on my home page. Before asking someone else what to do, I gathered a list of the parts of the documentation I had read, and an example of what I had tried. My question was "How do I create a page in Hugo that is not treated like a blog post?"

If your question is about a bug, make a list of what you have tried and what the outcomes were. _Make sure not to dig a hole!_ What did you expect to happen? What actually happened?

With this information, you can form a specific question.


## Notes

### Your Brain's API

-   both asking and helping can be hard
-   how we help and ask for help is the culture of our development environment
-   errors can equal "damnit!" or errors can equal "interesting!" -- this is culture
-   "the little voice"
    -   "i'm never going to get good at this"
    -   "maybe i'm just not cut out for this"
    -   "what are they all going to think of me?"
-   even when talking to a senior person, remember that you know stuff and they know stuff, and you know stuff they don't
-   "confusion is a sign you're about to learn something"
-   asking tools
    1.  pick a good place to work
    2.  ask early -- 15-minute rule
    3.  demonstrate competence. audit your speech patterns. delete the "i think"s.
    4.  Tell them what you need. "30% feedback." Let them know how done the thing you're working on before asking for feedback. Feel free to ask for feedback early.
    5.  Say what you've already done. "I read the docs, but I didn't understand this particular section."
    -   "My current understanding is \_\_\_\_. I expect to see \_\_\_\_ here but instead it's doing \_\_\_\_. What's going on?"
    -   "I want to do \_\_\_\_ and I'm trying it by \_\_\_\_. What do you think?"
    -   After getting an answer, _say it back_ to them to check your understanding.
-   recap of asking tools
    1.  pick a good team
    2.  15-minute rule
    3.  say what you need
    4.  say what you've done
    5.  say it back to them
-   helping mindset
    -   the "curse of knowledge" -- being an expert makes it hard to remember what it was like to learn
    -   every question you get asked is a chance to build up your team
    -   model not knowing
-   Before you ask (from Flatiron School)
    1.  Google it
    2.  Read the error message (!!!)
    3.  Ask another student
    4.  Then you can ask a teacher.
-   helping tools
    1.  welcome questions. Reward question-asking. _Don't Shoot the Dog_ by Karen Pryor.
    -   Too many questions? Teach them to fish
    2.  People will always remember how you made them feel.
    -   Assume competence
    -   "How familiar are you with \_\_\_\_?"
    -   Praise in public, critique in private.
    3.  Share the how and the why not just the what
    4.  Don't grab the steering wheel
    5.  Watch your language ~easy~ ~just~ ~obviously~
    6.  Don't coddle: push + support
-   Summary
    1.  Welcome questions
    2.  Make them feel good
    3.  Share the how & why
    4.  Ask for the wheel
    5.  Watch your language

### Getting Answers

Ten principles:

1.  Explain what doesn't work
2.  Provide everything up-front
3.  Post your code
4.  Do your research beforehand
5.  Do your research during
6.  Do your research afterwards
7.  Don't post the same question repeatedly
8.  Follow up after you get an answer
9.  Treat the list like people
10. Always consider the answer

## Resources

-   [Your Brain's API](https://www.youtube.com/watch?v=hY14Er6JX2s)
-   [Getting Answers](https://www.mikeash.com/getting_answers.html)
-   [How to Ask Good Questions on Technical and Scientific Forums](https://www.biostars.org/p/75548/)
-   Bad resource: [How to Ask Questions the Smart Way](http://catb.org/esr/faqs/smart-questions.html)
