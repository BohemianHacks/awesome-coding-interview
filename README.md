# Coding Interview Guide

> I started this simple list of topics to learn in order to become a software engineer, but it grew over time. After completing every goal on this list, I became a software development engineer at Amazon! You may not need to learn as much as I did. But here is what you need to know to become a competent engineer.
>
>I studied 8-12 hours a day on my own for several months. Here is my story: Why I studied full time for 8 months for a Google interview.
>
> **Please note:** You don't need to study as hard as I did. I wasted a lot of time on unnecessary things. More information on this below. I will help you save precious time and get you there.
> The topics in this list will give you enough knowledge to face technical interviews at almost every software company, including the tech giants: Amazon, Facebook, Google, and Microsoft.
>
> **Good luck!**

## What is this?

![Coding at the Whiteboard ——— From the HBO series, "Silicon Valley"](https://d3j2pkmjtin6ou.cloudfront.net/coding-at-the-whiteboard-silicon-valley.png)

This is my multi-month study plan for becoming a software engineer at a large company.

**Requirements:**
* Some programming experience (variables, loops, methods/functions, etc.)
* Patience
* Time

Note that this is a study plan for **Software Engineering**, not Front-End Engineering or Full-Stack Development.
There are many detailed roadmaps and course materials for these career paths that can be found elsewhere (see https://roadmap.sh/ for more information).

There is a lot to learn in a computer science major at university, but only about 75% of it is enough to prepare for an interview, which is what I will cover here.
If you want to do a complete self-study computer science project, you can refer to Kamran Ahmed's computer science roadmap: https://roadmap.sh/computer-science

---

## Table of Contents

### Study Plan

- [What is this? ](#This is)
- [Why do I need it? ](#Why to use it)
- [How to use it](#How to use it)
- [Don't think you're not smart enough](#Don't think you're not smart enough)
- [Related video resources](#Related video resources)
- [Choose a programming language](#Choose a programming language)
- [Data structure and algorithm books](#Data structure and algorithm books)
- [Interview preparation books](#Interview preparation books)
- [Don't make my mistakes](#Don't make my mistakes)
- [What's not included](#What's not included)
- [Daily plan](#Daily plan)
- [Programming problem practice](#Programming problem practice)
- [Programming problem](#Programming problem)

### Topics to learn

- [Algorithm complexity / Big-O / Asymptotic analysis](#Algorithm complexity--big-o--Asymptotic analysis)
- [Data structure](#Data structure)
- [Arrays](#Arraysarrays)
- [Linked list Lists](#linked-lists)
- [Stack](#stack)
- [Queue](#queue)
- [Hash table](#hash-table)
- [More knowledge](#more knowledge)
- [Binary search](#binary-search)
- [Bitwise operations](#bitwise-operations)
- [Trees](#trees)
- [Tree-introduction](#tree-introduction)
- [Binary search trees: BSTs](#binary-search-treesbsts)
- [Heap / Priority Queue / Binary Heap](#heap--priority-queue--binary-heap)
- Balanced search tree (general concept, no details)
- Traversal: pre-order, in-order, post-order, BFS, DFS
- [Sorting](#sorting)
- Selection sort
- Insertion sort
- Heap sort
- Quick sort
- Merge sort
- [Graphs](#graphs)
- Directed graph
- Undirected graph
- Adjacency matrix
- Adjacency list
- Traversal: Breadth first search (BFS), Depth first search (DFS)
- [More knowledge](#more knowledge)
- [Recursion](#recursion)
- [Dynamic programming](#dynamic-programming)
- [Design pattern](#design pattern)
- [Combination & Probability](#combinatorics-n-choose-k-out-of-probability probability)
- [NP, NP-complete and approximate algorithms](#np-np-complete and approximate algorithms)
- [Cache](#cache)
- [Processes and threads](#processes and threads)
- [Testing](#testing)
- [Scheduling](#scheduling)
- [String search and manipulation](#string search and manipulation)
- [Dictionary tree (Tries)](#dictionary tree tries)
- [Floating point numbers](#floating point numbers)
- [Unicode](#unicode)
- [Byte order](#byte order endianness)
- [Network](#network videos)
- [Final review](#final review)

###Get a job offer

- [Update your resume](#update your resume)
- [Find a job](#find a job)
- [Interview process and general interview preparation](#interview process and general interview preparation)
- [When the Interview Comes](#When the Interview Comes)
- [Questions to Ask the Interviewer](#Questions to Ask the Interviewer)
- [When You Get Your Dream Job](#When You Get Your Dream Job)

**---------------- All of the following is optional ----------------**

### Optional Additional Topics and Resources

- [Additional Books](#Additional Books)
- [System Design, Scalability, and Data Processing](#System Design, Scalability, and Data Processing)
- [Additional Learning](#Additional Learning)
- [Compilers](#Compilers)
- [Emacs and vi(m)](#emacs-and-vim)
- [Unix Command Line Tools](#unix-command line tools)
- [Information Theory](#Information Theory-Videos)
- [Parity Bits & Hamming Codes (Videos)](#Parity Bits--Hamming Codes-Videos)
- [System Entropy](#System Entropy Entropy)
- [Cryptology](#Cryptology)
- [Compression](#Compression)
- [Computer security](#Computer security)
- [Garbage collection](#Garbage collection)
- [Parallel programming](#Parallel programming)
- [Message passing, serialization and queueing systems](#Message passing serialization and queueing systems)
- [A* search algorithm](#a* search algorithm)
- [Fast Fourier transform](#Fast Fourier transform)
- [Bloom filter](#Bloom filter)
- [HyperLogLog](#hyperloglog)
- [Locality sensitive hashing](#Locality sensitive hashing)
- [van Emde Boas tree](#van-emde-boas-tree)
- [Enhanced data structures](#Enhanced data structures)
- [Balanced search tree](#Balanced search tree balanced-search-trees)
- AVL tree
- Splay tree
- Red-black tree
- 2-3 search tree
- 2-3-4 tree (also called 2-4 tree)
- N-ary (K-ary, M-ary) tree
- B-tree
- [k-D tree](#k-d tree)
- [skip list](#skip list)
- [network flow](#network flow)
- [disjoint sets & union search](#disjoint sets--union search)
- [fast processing mathematics](#fast processing mathematics)
- [treap](#treap-treap)
- [linear programming](#linear-programming video)
- [geometry: convex hull](#geometry-convex-hull video)
- [discrete mathematics](#discrete mathematics)
- [extra content on some topics](#extra content on some topics)
- [video series](#video series)
- [computer science course](#computer science course)
- [paper](#paper)

---

## Why use it?

If you want to work as a software engineer at a big company, these are the things you must know.

If you missed your degree in computer science, like I did, this will help you catch up and save four years.

When I started this project, I knew nothing about stacks and heaps,
nor about big O notation or anything about trees, nor how to traverse a graph.
If I had to write a sorting algorithm, trust me it would have been terrible.
Every data structure I had ever used was built into the language, and I had no idea how they worked under the hood.
I had never managed memory unless a running process had an "out of memory" error and needed to find a way around it.
I have used a few multidimensional arrays and thousands of associative arrays in my life, but never created a data structure from scratch.

This was a long project that took me months. If you are already familiar with most of the stuff, you will probably save a lot of time.

## How to use it

Everything below is just an overview. So you need to approach it from top to bottom.

During the learning process, I used GitHub's special Markdown syntax to check the progress of the plan, including using task lists with task progress.
- [More details about Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## Don't think you are not smart enough

- Most successful software engineers are very smart, but they have an insecurity that they think they are not smart enough.
- The following videos can help you overcome this insecurity:
- [The Myth of the Genius Programmer](https://www.youtube.com/watch?v=0SARbwvhupQ)
- [Don't Fight Alone: ​​Facing the Invisible Monsters in Technology](https://www.youtube.com/watch?v=1i8ylq4j_EY)

## Related Video Resources

Some videos can only be viewed by registering and logging in to Coursera or Edx courses.
These videos are called MOOCs. Sometimes you have to wait for months for some courses to be available, during which time you can't watch the videos of these courses.

I would appreciate your help in converting the video links of the MOOCs to public, continuously accessible video sources,
such as YouTube videos, to replace those online course videos.

In addition, some university lecture videos are also my favorites.

## Choose a programming language

You need to choose a programming language for your programming interview
