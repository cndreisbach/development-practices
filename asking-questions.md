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

## Ask your question

Once you are armed with research and have identified your question, it's time to ask.

Sasha Laundy, in her talk ["Your Brain's API"](https://www.youtube.com/watch?v=hY14Er6JX2s), gives great advice for how to ask a question effectively. She recommends letting the person you're asking know how done the code you're showing them is. If you are 30% done and run into a bug, letting the person you're asking know you're 30% done will help them calibrate their answer. At that early stage, they may recommend changing your approach altogether as you haven't invested that much into it, but they likely won't say anything about your code formatting, for example. If you're 90% done, they're more likely to point out small tweaks you can make.

Laundy's second tip is to say what you've already done. She provides two great templates for how to phrase this:

-   "My current understanding is \_\_\_\_. I expect to see \_\_\_\_ here but instead it's doing \_\_\_\_. What's going on?"
-   "I want to do \_\_\_\_ and I'm trying it by \_\_\_\_. What do you think?"

Do not be timid about asking questions. It is important that you realize that even if you are asking someone with a lot more experience than you, you know things they do not know and they know things you don't. The real answers often come where your knowledge and theirs overlaps.

## Follow up

After you get an answer, restate that answer in your own words to make sure you understood it. Point out places where you think you may have a misunderstanding.

When you start to implement the advice you've been given, you will come up with new questions. Do your research! Armed with the previous answer, research the parts you're unfamiliar with. Once you have done that, you're ready to ask a new question.

## Resources

-   [Your Brain's API](https://www.youtube.com/watch?v=hY14Er6JX2s)
-   [Getting Answers](https://www.mikeash.com/getting_answers.html)
-   [How to Ask Good Questions on Technical and Scientific Forums](https://www.biostars.org/p/75548/)
