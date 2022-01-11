---
layout: post
title:  "Learning MRI (with lectures too)"
author: peder
categories: [ education ]
image: assets/images/MRI-Introduction.png
featured: true
---
I just completed teaching the course UCSF Biomedical Imaging 201: "Principles of MRI" for the 11th time, and figured it would be a great opportunity to share some of my experiences and materials.  If you just want the answers (TLDR), you can check out my lectures and some of the course materials

[Principles of MRI Recorded Lectures](https://www.youtube.com/playlist?list=PLjBt5Iq93BT9eXMsgevVTXKVv4BgVLB1X)

[Resources for learning the Principles of MRI JupyterBook](https://larsonlab.github.io/MRI-education-resources/Introduction.html)


## A course for engineers and non-engineers

The target audience of this course are students in the [UCSF Masters of Science in Biomedical Imaging program](https://radiology.ucsf.edu/education/graduate-programs/msbi-program) that includes a broad range of backgrounds and aims to teach the fundamental principles of biomedical imaging modalities as well as how imaging is used in clinical applications.

It does not require prerequisites in college-level engineering or programming.  The students come from varied backgrounds, which are mostly STEM fields, but only a fraction of them have background in engineering principles (e.g. signal processing, Fourier Transforms, scientific computing) and physics principles (particularly electricity and magnetism) that are often prerequisites for engineering-based MRI curriculum.  This is the primary challenge I have faced teaching this course.

Fortunately, there are additional resources for these students, including a Math/Physics/Programming Bootcamp that starts just before the Fall Quarter, a MRI lab course that runs concurrently, and overlap in engineering principles with other courses such as Image Processing.

## Textbook Debate

Over the 11 years of teaching this course I have struggled with the choice of textbook, which I think is due to both teaching to a non-engineering but my desire to provide rigor on the physics and engineering principles.

I started with [**Principles of MRI** by Dwight Nishimura](https://www.lulu.com/shop/dwight-nishimura/principles-of-magnetic-resonance-imaging/paperback/product-6355103.html?page=1&pageSize=4), the textbook written by my PhD advisor and what I learned MRI from.  It is a great text - concise, consistent, clear, and rigorous - but my non-engineering students struggled.  It is written for electrical engineering or similar background, and the assumptions of signal processing and even advanced math familiarity left some of my students behind.  I still recommend this book as optional text, and several more engineering minded students have given feedback that they loved this text (as do I!).  I also borrow some homework questions from this book.

The next book I tried was [**MRI: From Picture to Proton** by McRobbie, Moore, Prince, and Graves](https://doi.org/10.1017/9781107706958), which targets a broader audience.  It includes great imaging examples, covers an excellent breadth of topics, and has a great sense of(British) humour.  However, I like to include much of the math behind MRI, and I struggle to teach it with this book - equations are only included as sidebar sections, and their use is a little sparse and inconsistent for my preference.  I also still recommend this book as optional text, and continue to use some of the very useful illustrations in my lectures.

Currently, I now use [**MRI: The Basics** by Hashemi, Lisanti, and Bradley](https://shop.lww.com/MRI--The-Basics/p/9781496384355), which does a good job teaching the non-physicist/engineer (e.g. MRI technologists, radiologists).  For my goals with my students, this book finds a happy medium between intuitive explanations while delving into some of the math, physics, and signal processing.  I follow the material and organization of this text, and guide students through it with my own lecture slides.

I also supplement this text with some consise notes and accompanying simulations, found in [Resources for learning the Principles of MRI JupyterBook](https://larsonlab.github.io/MRI-education-resources/Introduction.html).  I created this initially to have a full MRI signal equation and RF pulse profile reference that were not in **MRI: The Basics**, and I drew heavily from Nishimura's **Principles of MRI**.  I also had fun adding a bunch of illustrative simulations, which I give to students to play with in homework so they can easily do their own numerical simulations. 

## Recorded Lectures

After the start of the COVID-19 pandemic, I switched to a flipped classroom type format.  For this I pre-record some material for each topic that students are expected to watch before the class session and take an accompanying quiz.  In class, I do some review of the pre-recorded material, trying to extract key or challenging concepts, and then focus on going through derivations or sample questions.  One strategy that has worked very well is to go over the quiz at the beginning of class becuase I get a good sense of how easy/hard the material is to comprehend and then can tailor the rest of the class time accordingly.

I was a little hesitant to release these publicly.  I was concerned about my students - would their experience (or preception of their experience) be lessened by this?  I've come to terms with this by believing there is so much I can offer through the in-class sessions, opportunity to practice in homework and exams, and the on-scanner projects.
I was also self-conscious about myself speaking and the quality of the lectures, but this feeling is now trumping by the value I see in providing this to everyone.

Ultimately I hope these will be valuable to people getting into or refreshing their MRI knowledge.  I also plan to periodically update, as I add or refine material in teaching.

[Principles of MRI Recorded Lectures](https://www.youtube.com/playlist?list=PLjBt5Iq93BT9eXMsgevVTXKVv4BgVLB1X)

![MRI Introduction Slide](../assets/images/MRI-Introduction.png)

## Recommended Resources for Learning Beyond the Basic Principles

There are great resources available to go beyond the principles of MRI material.  Many of the above textbooks have more material too.

* [Stanford Radiology 229: MRI Signals and Sequences](http://web.stanford.edu/class/rad229/) , which goes into more detail on advanced sequences and contrast mechanisms

* [Stanford Electrical Engineering 369C: Medical Image Reconstruction](https://web.stanford.edu/class/ee369c/index.html) , which goes into more detail on signal and image reconstruction methods

* [Stanford Electrical Engineering 469B: RF Pulse Design for MRI](https://web.stanford.edu/class/ee369c/index.html) , which goes into more detail on RF pulse design

* [Handbook of MRI Pulses Sequences by Bernstein, King, Zhou](https://doi.org/10.1016/B978-0-12-092861-3.X5000-6). Essential textbook for advanced MRI work.

<!-- 
{% include youtube.html id='1Ku6-uXw7Ag' %}

**VIDEO** https://youtu.be/1Ku6-uXw7Ag -->
