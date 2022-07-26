---
title: Source Coding
tag: 🌿 
category: Information Theory, Definition
---

[Source coding entails encoding information such that fewer bits are used than the original representation.]([Kahn](https://www.khanacademy.org/computing/computer-science/informationtheory/info-theory/v/source-encoding-language-of-coins-4-9)) The aim is to eliminate redundancy and send information in fewer bits.

Source coding is also related to [[Data Compression|data compression]].

Example:

Dice exercise

Let's say we have two die and we want to send the outcome of rolling the die using.

The first question is which outcome will be most common with each roll?

There are 6 possible outcomes for one dice.

How many total combinations are possible from rolling two dice?

There are 2 dice, which means there are 36 possible outcomes.

With the 36 possible combinations, which outcome (number) is most common?

To roll a 2, there is only one combination possible.

To roll a 4, there are 3 different combinations.

To roll a 6, 5 combinations.

To roll a 7, there are 6 combinations.

To roll 8, there are 5 combinations.

Since 7 is the most likely outcome, that is the message that will be transmitted most often.

It therefore makes sense to map 7 using the shortest signal (one bit).

Since 5 and 6, are both the second most common, 5 could be mapped using the second shortest signal (two bits) and 6 could be the the third shortest (three bits), or vice versa.

This way the most common number (7) can be sent in the least amount of time.
