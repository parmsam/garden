# The Solveit Method

I was part of the first SolveIt cohort last year, and I'm writing this TIL to share how its learning approach fundamentally differs from other AI coding tools.

## The Core Idea

The SolveIt method centers on incremental development: write 1-2 lines of code, see the results immediately, then package working steps into functions.[^1] This is the opposite of generating massive code artifacts all at once.

## Why Most AI Tools Hit a Wall

We've all experienced it. Ask an AI for help, get hundreds of lines of code, run into errors, ask for fixes, and somehow end up worse off than when you started. You're debugging code you don't understand, with no path forward. It might work once, but then it breaks again. This "doom loop" is frustrating and unproductive.

## A Different Approach

The SolveIt method recognizes that LLMs have specific properties that cause these problems, and instead of fighting them, works with them strategically. The key is changing expectations about what "helpful" means. This means not expecting complete solutions upfront, but guided steps that build understanding.

For a detailed breakdown of the three LLM properties that cause the "doom loop" and specific techniques to address each one, Rens Dimmendaal's post is excellent.[^2]

The framwork has four main components:
- Understand the Problem
- Devise a Plan
- Carry Out the Plan
- Look Back and Reflect

See this gist from Jeremy Howard for more insights on the SolveIt method.[^3]

## The Real Value

When tackling hard problems, working in small steps lets you learn and adapt your approach as you go. You're not just getting code. Instead, you're understanding the problem space and refining your questions along the way.

This contrasts with the trend toward AI tools that generate large, complex artifacts with minimal human involvement or learning.[^1]

I think the genuine value of AI tools will come from those that help us learn and grow our skills, not just automate tasks. The SolveIt method is a great example of this philosophy in action.

---

[^1]: Howard, J. (2024). "How To Solve It With Code." https://solve.it.com/
[^2]: Dimmendaal, R. (2024). "SolveIt Course: Key Take-Aways." http://rensdimmendaal.com/posts/solveit-course-key-take-aways
[^3]: Howard, J. (2024). "SolveIt Method Gist." https://gist.github.com/jph00/d60301884c56fe063101a7cc6193b3af