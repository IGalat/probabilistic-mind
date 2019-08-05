# Probabilistic mind
### Gain a level in Bayes!

---

This game was inspired by [a similar-themed game](http://acritch.com/credence-game/), functionality of which was far insufficient.

Its primary goal is to evaluate one's calibration of credence - how sure you are of something - and help improve it.

It offers a series of questions with answers, and you choose how sure you are of each one. Then you can view how well your credence correlates with actual answers, and correct correspondingly.


### How does it help?
Let's say that you plan on doing something and there's a small probability of something going wrong. Then you either have an urge to dissmiss that possibility, or, if it's a very bad scenario, your attention focuses on it too much and it seems like a _much_ bigger problem than it acually is.

If, however, you know that it is a 3% probability, you can actually evaluate how impactful it is.

E.g. let's say failure will cost you 10 times worth of success - then it's a 30% deduction from your total evaluation, take this into account and carry on.

What if the chance is 10%? Then 10% * 10 = 1 weight of failure, whereas 90% * 1 = 0.9 weight of success. It's not (on average) worth doing at all, whatever it is!

Relative worths of various outcomes we know instinctively and weigh them well. With probabilities, it's much, _much_ worse. Not only 2% and 20% feel kinda similar unless you've trained, we tend to assign systematically faulty probabilities. Seeing on exactly which intervals you're over- and underconfident will help you negate that.

Hence, this game.

# Functional goals
* Evaluate the existing level of confidence
* Improve confidence calibration
* Introduce no additional bias to the player - questions must be thought out carefully

### Secondary functional goals
These are optional and will not be optimized for if it interferes with primary goals.

* Train memory via [various](https://en.wikipedia.org/wiki/SuperMemo) [algorithms](https://en.wikipedia.org/wiki/Spaced_repetition)
* Help you show off in an aspect that matters! Publish your results on facebook, twitter, instagram, vine, pinterest, igmur, reddit, linkedin, blogpost! But don't limit yourself - print it and put in a frame next to your awards and certificates!

# Technical goals
* Cross-platform app, accessible via https link, and possibly as android/desltop app later
* Full offline functionality for the player
* Fast enough - no lag during q&a (main part of the app)
* User-contributed questions, because just devs can never fill large enough bank

### Secondary technical goals
* Themes
* Localization - may be tough and not very implementable
