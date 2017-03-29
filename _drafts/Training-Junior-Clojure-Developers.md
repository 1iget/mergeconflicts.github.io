# Training New Clojure developers via Code Review

# Introduction

Clojure, once an esoteric, unfamiliar, fringe language, is beginning to enjoy wide usage in industry. While a great win for the language, we now have a new problem: the task of bringing many seasoned programmers up to speed on both a new language, Clojure, and a new programming paradigm, functional.

So, the general pattern for bringing a new Clojure developer up to speed consists roughly of: attending an intensive seminar and reading books on nights and weekends.

While there is quality training content out there, such as Brave Clojure and LispCasts, as well as the intensive trainings offered by providers such as Cognitect, these are all training activities that must take place outside of working hours. Moreover, when it's time to actually dig into the work, the developer is usually still not fully prepared for the realities of real development work, and he/she is left to fumble around until he/she eventually learns the best practices.

The good news is that there is a solution.

Code review is the best way of providing ongoing, continuous education to these new developers as they get their sea legs in a new programming paradigm.

Why? Code review easily becomes an institutional habit, provides personalized feedback to developers, and improves the overall culture of code quality on the team.

*Clarification: for the purposes of this article, I'm going to focus entirely on the "Gatekeeper code review," AKA the "Branch and PR" model. There are several different other forms of code review, but I find this one to be the easiest to integrate into a development process and the best for creating a clear habit loop.*

# Body

## Habit Loop

In learning a new skill, it's essential for deliberate practice to become a habit. Code review is one of the most direct ways of making "continuous education" into an institutional habit.

All developers perform code review daily or weekly. It's often done by multiple reviewers on the team.

### Supervision

We've heard stories of programmers who program in a functional style when observed, but fall back into imperative habits when "adult supervision" is gone.

The power of the habit loop.

### Training

Other than that, I have to argue that code review is one of the best ways that a junior developer can learn what's wrong. By submitting his work to a discerning set of eyes, he can learn the various nuances and idioms of the language.

It's very hard to absorb these in a vacuum. The best way we've seen is to practice them, day-in and day-out. Repeated exposure, in the context of their daily work, is exactly what it takes to ingrain these habits and make them long-lasting.

## Personalized feedback

While LispCasts, Clojure Koans, and Brave Clojure are all great resources for learning, they all cover a standardized curriculum, and there's no guarantee of what the learner has and hasn't retained.

What's great about code review is that the feedback is entirely personalized to code of the author. 

Imagine if you could have 

So far, we've primarily focused on junior talent, but it's important to note that senior talent can also benefit from external code review.

Michael Phelps and Tiger Woods both have coaches. In the same way, it's critical to get outside criticism to take one's work truly to the next level.

## Code Quality

This goes without saying, but a huge benefit to embracing code review is the overall improvement to code quality and defect rate.

# Conclusion

## Taste

Clojure is a wonderful language, but it does require good taste in order to make the most of it. Other languages I suppose also share this quality, but since Clojure is such a high-leverage language, and by default, is not strongly typed, so it does require a certain level of disciploine by the development team in order to maintain a high level of code quality and readability. 

I wouldn't call it a modern Perl, far from it, but Rich Hickey has publicly stated that it's a language that is designed to be used by a small, elite team. 
