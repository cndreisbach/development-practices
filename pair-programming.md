# Pair programming

Pair programming is a practice where two developers work together on the same project at the same time, one "driving" -- writing code and typing -- and one "navigating" -- watching, commenting, and discussing.

Developers often invoke pair programming as a way to speed up development, reduce bugs, and transfer knowledge. To do it well, you need to practice it and have a set of guidelines. It is more than sitting together and taking turns at the keyboard.

## Who to pair with

It is tempting to pair senior and junior developers together so that the senior developer can teach while coding, but in practice, this doesn't result in writing much code. This can be a good technique if the primary goal is knowledge sharing and both developers are open to learning from one another, but it's not a good technique if the goal is to write code. Pairing with a developer around your own skill level, even if you have different areas of expertise, is much more effective.

It is also tempting to have the same pair for long periods of time so they can bond. In my experience, pairing together for up to a week or two can be great. You can dig deep into a problem that way. It is a good idea to switch up pairs at least that often to get new perspectives and prevent knowledge from getting siloed. In addition, people don't always get along, but if you know you only have to pair with a person for a week, it's easier to deal with the friction.

## Equipment

Pair programming does not require a lot of equipment. The ideal setup is one large monitor or two smaller mirrored monitors and two sets of mice and keyboards. You can get away with less than that. The monitor is the most important part. You can easily pass a keyboard and mouse back and forth, but you always want both participants to be able to see the screen without craning their heads.

You need to find a common denominator for your shell and editor when pair programming. While it is enjoyable to try out less common options for yourself -- I personally use fish shell and Emacs -- no one enjoys working in a unfamiliar environment. Use a simple editor with common key mappings like [Atom](https://atom.io/) or [Sublime Text](https://www.sublimetext.com/), both of which work on all major operating systems.

## How to get started

You may work somewhere where pair programming is already a wide-spread practice. If so, that is great and you will learn a lot from the people already experienced in it. If not, you get to be an agent of change and bring in a good practice.

The easiest way to get started is to first get someone to help you solve a problem. If you are stuck on a bug or don't know how to finish implementing something, ask another developer if they can help you. Sit down side-by-side at your computer. If possible, plug into a monitor to help you both see. Walk through what you've done line-by-line, and explain what you currently know and what you don't. Go slow. Pause frequently. Make sure they have chance to read what you're showing them. Talk through the problem together. If you see your partner struggling with how to explain something, offer them the keyboard and ask if they could show you in code. If you are struggling to understand something, ask if you can try writing out some code to see if you have it right. Do this and you will have a short pair programming session!

If you can pull off pair programming through a problem a few times, move to the next level. When you have to implement something that seems challenging to you, ask someone -- maybe the developer you've built up trust with by pairing on problems -- if they'd like to work on it with you. Start by talking through the problem and then move organically from there into working on it, using a similar flow to how you solved problems earlier.

## Communicating while pairing

The secret of pair programming is that it gives a structured way to communicate. So communicate! Ask questions constantly. Talk while you are typing, explaining what you are doing, or even reading the code out loud.

The [WikiWikiWeb page on Pair Programming Tips and Tricks](http://wiki.c2.com/?PairProgrammingTipsAndTricks) lists some statements and questions to make sure you are using:

- Here are my intentions.
- What are your intentions?
- What should we do now?
- What is the next step?
- Did we miss something?
- Let's ask the code.
- How does this code work?
- What's the test for this code?
- I do not understand. Can you draw me a picture?

## Driving and navigating

Being the driver -- that is, writing the code -- while pairing can be nerve-wracking. You may find that you make typos more often. Most developers are not used to having someone else watch us code. Driving becomes easier with time, but you can make it easier on yourself by making sure to breathe with your belly, talk while typing if you can do that, and swapping regularly.

In my experience, people swap the driver and navigator roles often. Swapping every 15-30 minutes is normal and you should try for that. You will also see "micro-swaps," where the navigator has an idea that is easier to show than tell and so drives long enough to type a few lines of code.

Communicate about how you are feeling. If you want the other person to drive, do not wait for them to offer. Tell them. Likewise, if the driver has been driving for a while and you have the urge to drive, say so.

In a particular pair, one person may drive more than the other. This is normal and usual. However, make sure that this is not too imbalanced. If one person is doing almost all the driving, talk about it and change that up.

## Taking care of yourself

Pair programming is extremely tiring. Working with someone else eliminates the micro-breaks we often take to check our email, social media, or news. Communicating is mentally and emotionally exhausting. Take a break every 60-90 minutes, and never pair for more than eight hours in a day.

> When I started at a consultancy that paired 100% of the time, having only paired infrequently earlier, I fell asleep by 8 PM every night for the first week. I would get home and already be yawning. I couldn't even look at a computer in the evenings. I was writing some of the best code of my life, though.

## Pairing with someone more senior

## Pairing with someone more junior

## Pairing remotely

## Resources

- [All I Really Need to Know about Pair Programming I Learned in Kindergarten](http://anh.cs.luc.edu/170/Kindergarten.pdf)
- [Pairing with Junior Developers](https://www.devmynd.com/blog/2015-1-pairing-with-junior-developers/)

http://wiki.c2.com/?PairProgrammingTipsAndTricks

Engaging
* Could you help me?
* Let's do it together!
During pairing
* Let me drive!
* Could you drive?
* Here are my intentions
* What are your intentions?
* What should we do now? What is the next step?
* Did we miss something?
* Let's ask the code
* How does this code work? Let's step into that Unit Test.
* What's the Test?
* I'm bored. What's going on?
* I do not understand. Draw me a picture! Explain me!
Resting
* Can we break?
* Can we stop?
* Can we switch peer?
* Let's play frisbee outside!
Maybe
* Can I take a look a this alone for a moment? (It is not pair programming but may give some relieve after intensive pairing. As long as 'a look' is only 'a look'.)
Do not
* This sucks

http://wiki.c2.com/?RecordYourCommunicationInTheCode

[All I Really Need to Know about Pair Programming I Learned in Kindergarten](http://anh.cs.luc.edu/170/Kindergarten.pdf)
* http://anh.cs.luc.edu/170/Kindergarten.html

https://www.agilealliance.org/glossary/pairing/

http://www.compsci.hunter.cuny.edu/~sweiss/course_materials/csci135/csci136tutorials/pair_programming_tutorial.pdf

