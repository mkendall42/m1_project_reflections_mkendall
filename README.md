You will need to copy this markdown, by either creating your own **private** gist, or creating a google doc. Paste this markdown into your own gist or google doc. After each project, you will take time to come back to your log and answer each of the questions that are outlined for you below. 

# M1 Interview Prep - Project Log

## First Solo

### Project Overview

#### List out the tools you used:
1. `pry` and `irb`
2. RSpec
3. Internet resources (mostly Ruby docs, also a little Googling / Stack Overflow / Reddit)

#### Write a 1-2 sentence synopsis of what this project does:
The flashcards application (called via `ruby flashcard_runner.rb`) provides an interactive game where a deck of cards with trivia questions and answers is constructed by loading from a specified text file.  These questions are presented to a user, who makes guesses, and at the end of the round the game finishes, where it presents scores based on number and percentage correct (including by category).

### Reflection Questions: 
**1. Pick 1 technical concept you used for this project (look back at our lessons and the learning goals of the project to pick this). Explain what this concept is, how it works, and give an example of where you used this in your code.**<br />
I'll go with iterations.  They are utilized on a number of occasions in my code (I'm grouping `.each` here as well, as even though it is an enumerable, I really don't see a big difference between it and an equivalently written `for` or `while` loop).  Iterations run a segment of code repeatedly until a condition is met (e.g. the elements of an array are exhausted, some boolean evaluates to `true`, a `nil` value is returned) which allow that segment of code to keep changing / updating variables or calling methods.  I use this several times: a couple of notable examples including running the main game round, where we must iterate through each card in the deck and consequently ask for user input repeatedly; or where I construct the full list of categories based on the cards present (this one was especially fun, since I ended up needing to nest iterations/enumerables).  

**2. How do you approach solving something when you don’t have all the information?**<br />
First, I try to look at general purpose and goal, both at the project level (what are we trying to get it to do / accomplish / output), and at the local level (for example, if I'm trying to make a class - why should it exist, what does it need to do, and how should it work with other classes and methods).  This usually will help me in building out at least a skeleton for coding.  I may re-read any instructions or requirements as well, as it is easy to forget a detail that may end up being important / provide a hint, or even be at the crux of a problem to solve.  

**3. What was your process when you got stuck?**<br />
At first, I would usually carefully go through error messages and try to isolate areas in the code that were problematic, or use pry / irb to look at current values in variables.  Over time, I've worked on trying to incorporate tests more early and often to help me motivate building methods and functionality out - i.e. walk the "TDD" line.  I admit I'm struggling with this, especially in some scenarios, but I can see the rationale.  I leaned into the productive struggle - I love figuring something out on my own - but a few times (and after banging my head against a wall for long enough), I decided that a little internet research would be best for solving an issue.  I tried to avoid borrowing direct code, and instead just learn a method that might help me for a situation, so that I didn't just use code that I didn't fully understand.  

**4. If you had to do this project again, what would you do differently and why?**<br />
I'm pretty pleased with how this project shook out for me.  I prioritized the project while not forgetting other work, and was able to pace myself relatively well (I had iteration 3 done last Friday, and iteration 4 on Sunday, so Monday was just tweaks / cleanup / extra features for fun).  My main change would be to utilize resources beyond me a little bit sooner.  I can definitely get too caught in the weeds or even paralyzed by obsessing with trying to solve it myself.  There is value in this to a degree, but eventually there's no need to re-invent the wheel.  This will be a long-term battle for me, and I will look to guidance and advice from others periodcially on this.  

**5. What was your most effective strategy for getting through blockers during this project? How did this help your process?**<br />
Much of this I believe I addressed in #3 above, but another thing I found useful was to change gears periodically.  Whether it was putting down the work and going to exercise / walk around my home / talk with a friend / play a game, or even just changing what Turing work I was doing (for example, switching to the ruby_exercises or following up on a conversation or link), this helped clear my mind when I returned.  Usually it just meant I had a refresh, and occasionally may have even yielded a solution more quickly to me.  

**6. What was the benefit of using TDD while building out this project?**<br />
It definitely is helpful in defining the functionality of specific methods within a class - without this, there can easily be mission creep or even confusion over the goal of the method - and it also ensures the method is doing exactly what you want it to.  Return type and values both matter here a great deal, and can quickly get you into trouble if you're not being careful.  TDD also sometimes helped me 'chunk' my code so that I could focus on one thing at a time in better isolation.  However, I will admit that in many cases classes and methods depend on each other, and I struggled more with effective isolating / chunking in those situations.  I'm not sure if there's a good fix for it, or just a reality and gradual 'art form' of building good RSpec tests.



## Second Solo

### Project Overview

#### List out the tools you used:
1.
2.
3.
...

#### Write a 1-2 sentence synopsis of what this project does:

### Reflection Questions: 
**1. Describe the steps you took to dig in to this code base. What was your process? If you don’t feel you had a process, define one that you might like to try next time.**<br />
**2. What was the benefit of using TDD while building out this project?**<br />
**3. What was a resource that you used during this project and how did you use this to move your project forward?**<br />

## Paired Paired

### Project Overview

#### List out the tools you used:
1.
2.
3.
...

#### Write a 1-2 sentence synopsis of what this project does:

### Reflection Questions: 
**1. What was your pairing style like? How did you manage your Github work flow? What are your thoughts on that workflow?**<br />
**2. What skill do you feel you have a better handle on after working on this project? What skill has this project lead you to realize you need more practice on?**<br />
**3. What strategies help you best work with others? What would you like others to know about how you work best?**<br />

## Group Project

### Project Overview

#### List out the tools you used:
1.
2.
3.
...

#### Write a 1-2 sentence synopsis of what this project does:

### Reflection Questions: 
**1. Group: What conflicts came up and how did you resolve them?  This could look like different opinions on how to code a method, what to name a class, when to do stand ups, or communication breakdowns.**<br />
**2. Pick 1 technical concept you used for this project (look back at our lessons and the learning goals of the project to pick this). Explain what this concept is, how it works, and give an example of where you used this in your code.**<br />
**3. Describe your team’s code review process. How did you ensure your end product worked and was of high quality?**<br />
