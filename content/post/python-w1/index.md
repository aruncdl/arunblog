---
title: 'Self-Learn Python | Week 1'
subtitle: 'What do I want to learn?'
summary: Identify goals. Get your hands dirty.  
authors:
- admin
tags:
- Learning
- Coding
categories:
- Python
date: "2020-08-31T00:00:00Z"
lastmod: "2020-08-31T00:00:00Z"
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 3
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

[As promised](https://arunsudarsan.in/post/a-personal-challenge/), I started learning Python this weekend. It wasn't the most productive two days ever, because [Onam is here!](https://arunsudarsan.in/post/i-miss-home/). However, I did set out to do the following. 

1. Identify what I want to learn
2. Start off with a small project

#### What do I want to learn?

This is important whenever you are starting out to learn something. Without having at least a broad idea or contour of what we want to learn, we'll quickly become overwhelmed by the amount of resources available, and the various methods to learn them. I had to be sure of what I want to learn. To be clear, this list can change later, based on new knowledge or circumstances. The important thing is to not overburden ourselves at the beginning. So, after some thought, I decided I want to learn the following. 

1. Econometric analysis: I've always used STATA for econometric analysis. As mentioned previously, it's an insanely expensive piece of software, closed-source, and definitely not a viable long term solution for me personally. 
2. Data visualisation: Excel, Tableau etc. were tools that I've used earlier. Again, they are expensive, closed-source, and non-customisable. 
3. Web Scraping: My work at [CivicDataLab](https://civicdatalab.in/) is powered by publicly available data. [Gaurav](https://twitter.com/gggodhwani) and [Shreya](https://twitter.com/shreya_0809) are masters at mining data from the web. However, I'd like to pick up that skill.

#### How should I learn?

In my previous attempts at learning Python, I started off with _Chapter 1 of Volume 1 of Book 1_. That approach failed me (or rather I failed that approach). We don't learn the alphabets before we start talking, do we? I wanted to get my hands dirty by trying something I've never done before. I decided that I'll start by trying to scrape data from a website. A bit of Googling, and multiple different tutorials later, I was able to come up with the following. 

#### My first web scraper

<script src="https://gist.github.com/aruncdl/953fcdb4450ab78a43bde075fc3e8383.js"></script>

Arguably, this is one of the easiest, and most definitely a useless web-scraper. This merely gets me a list of all _bandhus_ at my company, CivicDataLab, that we can easily get by just going to the website directly. However, it was also instructive in how to do basic scraping from static html sites. 

![GIF](cdlbandhu.GIF)

There are a few issues that I'm grappling with

1. I have not documented the code well. Need to add comments to explain the code better. 
2. I couldn't figure out how to get all the following details (apart from the name) - Bio, Email ID, and other social media IDs. 
3. Finally, I still haven't figured out how to export it into a .txt or .csv file. 

#### Targets for next week

This was the only successful scraper that I could code after my first on-and-off python lesson. My target for the next weekend are as follows

1. Add comments to explain code better
2. Get all details of all Bandhus at CDL
3. Export it into a CSV file

These are baby steps. I'm not in a hurry as well. I want to take it slow and steady. 

#### Resources used for this lesson

The following online tutorials were used by me. I can't vouch for their quality. However, they did help me make my first ever web scraper. 

[Edureka](https://www.edureka.co/blog/web-scraping-with-python/)

[Real Python 1](https://realpython.com/python-web-scraping-practical-introduction/), [Real Python 2](https://realpython.com/beautiful-soup-web-scraper-python/)

[Open Source](https://opensource.com/article/20/5/web-scraping-python)



