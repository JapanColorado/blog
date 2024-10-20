---
layout: post
title: "A new series: Paper Summaries!"
author: "Russell White"
categories: paper-summaries
tags: [learning,papers]
image: paper-summaries-intro.jpg
---

This is the start of a new series of scientific paper summaries that I'll be posting! My plan is to read a research paper and write up a summary for it here. The goals of this series is twofold:

1) Condense research papers into easily-readable summaries, for you, the reader!
2) Clarify my understanding of the paper and force me to really interact with the paper's ideas <-- My primary objective

I'm calling this series(appropriately) Paper Summaries!

To start off, I'll be summarizing a paper that outlines how to read research papers effectively. This is S. Keshav's [*How to Read a Paper*](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf), which consists of a three-pass approach to reading scientific papers. Keshav also discusses how to carry out a literature survey using this appraoch.

Because what follows is a summary, full credit for any good ideas go to the original author and any blame to me.

## [*How to Read a Paper*](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf) - Summary

Rather than just reading from beginning to end, an efficient method of reading research papers is the *three-pass approach*. It consists of three separate readings of a paper:

### Pass #1

* Read the following:
  * Title
  * Abstract
  * Introduction
  * Headings & sub-heading
  * Conclusion
* Glance over the references and note which ones you've already read
* Answer the *5 C’s* after this.
  1. *Category* - What type of paper is this? A measurement paper? An analysis of an existing system? A description of a research prototype?
  2. *Context* - Which other papers is it related to? Which theoretical bases were used to analyze the problem?
  3. *Correctness* - Do the assumptions appear to be valid?
  4. *Contributions* - What are the paper’s main contributions? Why should you care about this paper?
  5. *Clarity* - Is the paper well written?

If the paper doesn’t interest you, the authors make invalid assumptions, you don't know enough about the field to understand it, or the paper otherwise fails your standards, then you can stop after this stage.

### Pass #2

* Read the entire paper with care, but ignore details like proofs.
  * Jot down ideas, notes, and connections in the margin(or in Zotero).
* Look at figures and diagrams extra closely, with special attention given to graphs.
  * Are there error bars?
  * Are axes properly labeled?
* As you read, mark unread references as potential further reading.
* (*My idea:*) After this, write a summary of what you’ve read, preferably in public.

This pass should take around an hour, and by the end you should be able to grasp and summarize the main point of the paper to someone else.

If the paper is important to your research field or you’re particularly interested, go on to the third pass.

### Pass #3

* Read the entire paper with *extreme* attention to detail.
* Your goal is to essentially reimplement the paper:
  * Make the same starting assumptions as the paper
  * Identify and challenge every assumption in each and every statement made.
* Think about how you would present the ideas they are presenting.

This pass should take around ~4-5 hours for a beginner(my intuition: might actually be 5-10), and around 1 hour for an experienced reader.

After this final pass, you should be able to reconstruct the structure of the entire paper from memory and identify the inflection points[^1] of the paper.

You should also be able to point out any implicit assumptions, missing citations to relevant work, and potential issues with experimental or analytical techniques.

### Doing a Literature Survey

1. Use an academic search engine like Google Scholar to find 3-5 *recent papers* in your chosen field.
   * If you find a recent survey paper, CONGRATS! You're done! Read that and feel grateful for your good luck.
2. Complete one pass on each paper.
3. Read related work sections.
4. Find frequent shared citations and author names across paper bibliographies.
   * Download these key papers that you found.
5. Go to websites of the authors you found and see where they've published papers.
   * Your goal is to find the top conferences.
   * Download the highest-quality papers from their procedings.
6. Complete 2 passes on the conference papers and key papers that you found earlier.
   * If a paper pops up frequently in their citations that you didn't find earlier, find it and read it.
7. Iterate until you're done!

## My closing thoughts

I felt that writing this summary was a helpful exercise. I was forced to reread the paper over and over again, as well as rearticulate what it was trying to say in my own words. I think this is a series I will be continuing!

I don't know whether there are any papers that I'll ever do a third pass on. I think Keshav underestimates the amount of time a third pass will take, especially if it comes to reimplementing a technical paper. I don't think that's necessarily what he constitutes as a third pass, maybe that would be more on the level of a fourth pass.

Maybe a fourth pass is either using a paper for a personal project, or actually reimplementing the paper in the case of technical papers like OpenAI's RLHF & backflips paper.

Anyways, look forward to new paper summaries!

[^1]: Strong/weak arguments, assumptions, critical arguments, etc.
