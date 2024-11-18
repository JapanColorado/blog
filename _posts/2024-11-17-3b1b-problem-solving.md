---
layout: post
title: "Grant Sanderson's Problem Solving Tips"
author: "Russell White"
categories: journal
tags: [notes]
image: mountains.jpg
---

The following is a list of problem solving tips that I've taken from Grant Sanderson(aka 3Blue1Brown)'s [Tips to be a better problem solver](https://www.youtube.com/watch?v=QvuQH4_05LI). All attribution, of course, goes to Grant, and I'm incredibly grateful for his amazing videos.

## Tips to be a better problem solver

### 1. Use the defining features of the setup

Look at each object/variable and each object/variable's definition within the setup of the problem. Oftentimes, the solution becomes obvious once you actually understand what the problem is declaring and asking.

### 2. Give things meaningful names

Which is easier to understand?

```python
s = 0
x = [32, 45, 17]
for i in x:
    s += i
```

Or:

```python
total = 0
num_list = [32, 45, 17]
for num in num_list:
    total += num
```

In mathematics as in programming, although some would prefer the first example with generic names, writing the second and using memorable, sticky names that are descriptive of the objects you are naming is going to make it easier to solve problems and understand your old solutions when you return to them.

### 3. Leverage symmetry

Many times, problems come down to recognizing that two seemingly-disparate things are actually the same deep down. Looking for symmetry makes it easier to recognize when this is the case.

### 4. Try describing one object two different ways

For example, $e^{ix}$ could also be thought of as:

$$\exp({ix})=1+ix-\frac{x^2}{2}-\frac{ix^3}{3} \ldots$$

Or as:

$$\cos(x)+i\sin(x)$$

### 5. Draw a picture (Have numbers? Make them coords!)

Simple sketches often give meaning to arbitrary-feeling numbers. If you can make those numbers into coordinates within your sketch, even better!

### 6. Ask a simpler version of the problem

If you're solving a problem and it just feels *too hard*, try simplifying the problem until you can get some kind of a foothold. Maybe loosen the constraints, or look at a subproblem. Also, it's perfectly fine to find *a* solution before trying to find the *optimal* solution.

### 7. Read a lot and think about problems a lot

Often solving problems comes down to just recognizing patterns from other fields or subfields. One of the best ways to be a better problem solver is to learn more about the domain you're working with and solve more problems from that domain.

### 8. Always gut check your answer

Are the units correct? Do the probabilities all add up to one? Does it make sense for an object to be moving that fast or a voltage to be that massive given the constraints of the problem?

Often these little gut checks will save your ass more than any extra ingenuity or intelligence would.

### 9. Learn at least a little programming

Programming is extraordinarily useful for checking your answer in a wide range of problems. For example, you can often just brute force finding an answer when it comes to a probability problem; just simulate the event a million times!

Additionally, programming forces you to think about the problem in a different way. The added constraints of making something computational makes you create new connections between your ideas.

---

That's it for my summary of the problem solving tips! I would highly recommend watching the original video; it contains worked out examples that exemplify the tips that are laid out, and Grant is always a joy to watch.
