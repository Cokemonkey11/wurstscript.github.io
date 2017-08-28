---
title: Wurst for the Jass Curious
sections:
- What is JASS
- How does wurst relate to JASS
- Who might want to learn JASS/wurst
- Learn Wurst, or Learn JASS
- Wc3 Scripting for Beginners
---

{: .answer}
### *&nbsp;*{: .fa .fa-exclamation-circle} This introductory discussion is for users with limited or no JASS or programming experience.

------

In this beginner-friendy discussion we introduce a number of goals that a modder will strive for when writing scripts for a wc3 map.
Approaching these goals can't be done in order from first to last, but the topics should gradually make more sense as the readers experience grows.

Try to keep the following very abstract ideas in mind as you follow along.

* The code should *help* the modder implement the game correctly (no bugs), efficiently (short time taken), and easily (the solution shouldn't be a surprise).
* The code should allow the modder to achieve their goal without performing repetitive tasks themselves, and should allow the modder to describe how things happen differently under varying circumstances.
* The code should make the easy things trivial and the unreasonable things possible.
* The code should look familiar to "ordinary" programmers, so that writing good code is possible even for non-wc3 modders.
* The code should make it easy to share with others for purposes of learning, auditing, and re-using.

## What is JASS

* Imperative language
* API for accessing Wc3
* Exposes "triggers" (handlers for "subscribing" to game state)

## How does wurst relate to JASS

* When you save the map, wurst gets transformed into JASS
* Wurst lets you write less and do more
* Wurst intentionally "looks and feels like" other more ubiquitous programming languages

## Who might want to learn JASS/wurst

* Anyone who considers writing code at all
* Anyone who wants to make wc3 custom games

## Learn Wurst, or Learn JASS

* Much better to learn wurst first - avoids spending time on lots of things that shouldn't be used like `location`
* Wurst more prescriptive - actually that's more beginner-friendly
* For much the same reason that JASS users don't care how `CreateUnit()` works on the inside, wurst users don't have to know how `print()` works at the JASS level.
* Less magic - never learn why `gg_trg_` is a thing.

## Wc3 Scripting for Beginners

* Packages, init, variables/types
* Leaks: units, strings, ints
* stl, vec2, loops, groups
