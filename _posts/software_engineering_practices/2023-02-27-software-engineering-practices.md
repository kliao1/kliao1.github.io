---
title: "Software Engineering Tips"
categories:
  - Software Engineering Practices
---

# Developing a good engineering mindset
I found this article on [your first 60 days at an engineering job](https://code.dblock.org/2015/04/23/your-first-60-days-at-an-engineering-job.html) 
quite useful in planning what to do for well, your first 60 days at an engineering
job.

This book on the [unwritten laws of engineering](https://ia801702.us.archive.org/25/items/the-unwritten-laws-of-engineering/The%20Unwritten%20Laws%20of%20Engineering.pdf)
is quite interesting too. It's worth a read for every engineer at the start of 
their career though I'm convinced it's a good book to read again every now and 
again.

[This]( https://www.simplethread.com/20-things-ive-learned-in-my-20-years-as-a-software-engineer/)
article on the 20 things the author learned in his 20 years as a software engineer
is quite enlightening.

Amazing advice from a senior backend engineer:`
>Seek out and in other people and foster in yourself - deep confidence 
(understanding things properly), being good at what you do and understanding 
your limitations. Be humble. Nothing is insurmountable. You're never done learning.


# Code quality
- Even if your code works, it's worth thinking of simpler ways of doing it (without
  sacrificing performance of course) - even better if you can think of ways that
  are more straightforward that everyone knows \*cough* design patterns. This way,
  it's been "tested" against time and it's easier for others to review as well
  since they are likely to be familiar with your chosen solution.
  
# Pull Requests
- Try and break your feature before requesting a review. In this spirit, try and 
  write test cases that not only test for success but test for failures as well i.e.,
  what kind of inputs are not acceptable.
- Leave a comment explaining if you're not sure about something so that the 
  reviewers know what to look for or what not to look for during their review. 
- Goes without saying but leave links to code that you've used and explain your
  approach to the problem. The more details you include, the easier it is for
  your reviewers to understand your PR.

# For Backend Developers
- Be careful of what goes into the database. See [this](https://www.toptal.com/database/database-design-bad-practices)
  for reasons.
- Try profiling more to gain more of an intuition of code speed.  
- This goes without saying, but test your migration scripts as well before 
  executing them.
  
  