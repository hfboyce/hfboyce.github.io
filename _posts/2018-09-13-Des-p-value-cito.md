---
layout: post
title: Des-p value-cito
---

### P-ardon Me?

Despacito in Spanish means “slowly” which is exactly how this article is attempting to explain this statistics term. 

We are all aware of this small little letter’s place in the English Alphabet (the 16th position) but where exactly does it belong in statistics? 

### The Analogy

Imagine you are walking down the aisle in the supermarket. You are trying to decide if you need to pick up toilet paper. How much do you have left at home? You get to the shelf you check the price. If it’s too expensive you decide to forgo this necessity (maybe you don’t even need it).  The higher the price of the toilet paper the less probable you going to decide you need the toilet paper. The lower the price, the more chance there is of deciding you need it and purchasing it. 

In this example, **price** is an analogy for a **p-value**. 


### American History – P:  The Ground Work

For any scientific experiment, there is a specific method that needs to be followed in order to ensure an unbiased and reliable conclusion. 

It starts with a question: 

**_“Do I need toilet paper?”_**

This is called a *Hypothesis*. 

In scientific testing there are only ever 2 outcomes to a question:  

1. Everything stays the same.
2. Something interesting happens. 

Both these outcomes have proper names so let me introduce you: 

Meet the *Null Hypothesis* (or “the null”) – this is the outcome where everything remains unchanged. 

     In the example – You don't need toilet paper. 

And this is the *Alternate Hypothesis* – this is the opposite of the null,  something has happened or something we think will happen. 

     In the example - You need toilet paper.

When we prove the alternate hypothesis is correct and “true”, we say we are *"rejecting the null hypothesis*. 

In the example –  You purchase the toilet.


### Terms and Conditionals 

Wait, what does this have to do with the p-value?  

To makes matters simple - the p value is a conditional probability and in true probability form, cannot be larger than 1. 

I am going to explain conditional probability through a quick example.

    Let’s say you want to buy paper towels for the kitchen. 
    The probability of going out and buying paper is going to have a different value than if you are already at the supermarket.
    For instance, on the weekend I am not as keen on leaving my house simply to get paper towel, however the chance of me buying paper towels given that I am already at the store is much higher. 

in this case:

$P(buying paper towels| I’m already at the supermarket) >= P(buying paper towels)$ 

*( `|`  can be replaced with the words “conditional that”)* 

###### The p value is therefore a conditional probability, conditional on the assumption that our null hypothesis is true. 


### Tell me what it is already! 

So now we know it is conditional on our null, but what is it calculating exactly? 

Good question – It is the probability of getting results stronger or equal than the current ones we have, given that our null hypothesis (the event where nothing happens) is true. 

This can be shown by :

$P(obtaining stronger or equal results than current ones |Null hypothesis is True) = p value $

Or less formally: 

$P(obtaining results pointing to more happening |nothing happens ) = p value $

In plain English this is like saying "The probability of getting results that differ from our current ones given that everything should stay the same." 


### To "p" or not to "p"? 

How do I use it?

* The lower the p value - the more evidence we have against the null hypothesis and therefore can reject it.
This means our test is more reliable and has a stronger argument to support our alternate hypothesis. 

* The higher the p- value – the less concrete our alternate hypothesis is and the ability to make a significant conclusion to our question goes down. 


### P-icking up the P-eices 

Going back to our old example, and assuming the maximum price for toilet paper is $100.00 (similar to the maximum possible probability being 100%)

If the price of toilet paper is $78.65 are we more likely going to buy it or forgo it (and just go to our parents homes and take it)?

-	In this case, we will likely not purchase the toilet paper and we are unable to say something interesting happened due to the price being too high.

This is like saying - we cannot reject our null hypothesis, since the p value was too large. 

What if instead the toilet paper was $3.99?

-	Here there is more chance that we will buy the toilet paper and as a result something interesting happens. 

In this case we are saying we are more likely to reject our null hypothesis given a smaller p- value. 


### From A to P

Generally with tests and experiments there is a critical number that is given as a guideline to where we feel confident the results are true.  A number that divides where we should and should not reject our null - We call this alpha! 

If our p value is less than the number given (alpha) – we can successfully say with confidence that something interesting happened! 

If our p value is greater than this number –  no conclusions can be made to our question. 


### Easy-P-easy!

So, from now on if somebody asks you if you are having fun learning about Data Science, you can answer them saying the p value to that question is low!





References: 

Dorey, F. (2010). In Brief: The P Value: What it is and What Does it Tell you? Clinical Orthopaedic and Related Research. 468(8): 2297–2298. doi:  10.1007/s11999-010-1402-9

Hung, T.Q (2016,March 21). Key to statistical result interpretation: P-value in plain English. Retrieved from https://www.students4bestevidence.net/p-value-in-plain-english-2/