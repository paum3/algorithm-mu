# Algorithmic music

Algorithms are actually calculation rules for solving problems.
What is solved in music? Classically, Graphical User Interfaces (DAWs) are used to make improvements to audio material, apply effects, and handle the arrangement of audio material or MIDI commands.

However, algorithms can also be used for creative work (even if the concepts and algorithms are not intended for that purpose). Examples are:
- Generative Grammars (Chomsky)
- Markov models
- Chaos and self-similarity
- Cellular automata
- Neuronal networks  

## Live algorithms vs. live coding
Algorithmic music can be divided into the two extreme "live algorithms" and "live coding".

Live algorithms are algorithms that are triggered once and are not changed again. But parameters could be changed by sensors, my/your GPS position or the weather on Java.

In the most extreme variant, you write algorithms "from scratch" in live-coding. You start in front of an empty editor window and then write an algorithm. The text is the musical interface and is written with the help of a keyboard (or anything else you can write text with -> attempts with a piano have already been made). Live-coding is used to create visuals, dance choreographies, teaching (e.g. robotics) or even in music.

## TidalCycles

Language for creating sequences using patterns. Is a Haskell DSL.
The workshop documentation for the rest of the talk is available under:
https://github.com/thgrund/algorithm-mu/blob/master/tidal/workshop.tidal

## Workshops - Algorithmic Music with Functional Programming 
Workshop documents about algorithmic music with functional programming. Concepts of functional programming based on Haskell will be introduced and the possibilities of composition and music creation with code will be demonstrated.

### Order of presentations

1. Overview about algorithmic music (15 min)
2. TidalCycles (105min) -> Maybe two presentations? One for Tidal only and one for the Haskell insights?
4. Euterpea (120min)
3. CSound (120min)
5. More?!

### Overview algorithmic music

1. Algorithmic music
3. Live-Coding (TidalCycles)
2. Live-Algorithmic (Euterpea, Csound)

### TidalCycles
1. Introduction
2. Demo - Writing code
3. Haskell insights (TidalCycles as DSL)
   1. Pattern Type (FRP like context)
   1. Type Signature 
   3. Type System
   1. Higher-Order Functions
   2. Polymorphy
   2. Pattern type as instance of Functor, Applicative and Monad
4. Mini-Concert

### Euterpea
*Under Construction*

### CSound-Expression
*Under Construction*

1. Another Haskell-DSL
2. Sound-Design (additive synthesis)
3. MIDI input
4. Csound gui
5. Scores (sequential/parallel composition)
6. Stochastic automaton and markov process

