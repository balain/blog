---
title: "Turning Statistics Into Knowledge: Seminar Review and Notes"
date: "2009-07-25"
categories: 
  - "data-visualization"
  - "programming"
  - "software"
  - "tools"
  - "website"
tags: 
  - "census-bureau"
  - "database"
  - "flash"
  - "gwt"
  - "ibm"
  - "mit"
  - "oecd"
  - "processing"
  - "r"
  - "sdmx"
  - "visualization"
  - "world-bank"
---

I had the pleasure of attending the [Seminar on Innovative Approaches to Turn Statistics into Knowledge](http://www.oecd.org/progress/ict/statknowledge), hosted by [the US Census Bureau,](http://www.census.gov/) [the World Bank](http://www.worldbank.org/), and [the OECD](http://www.oecd.org/). While [Robert Kosara](http://eagereyes.org/user/robert_kosara), from [UNC Charlotte](http://cs.uncc.edu/~rkosara/), has [a fairly thorough review (but not focusing on the technical aspects) of the seminar](http://eagereyes.org/blog/2009/oecd-seminar-turning-statistics-into-knowledge.html), and I would agree with most of his points (except for [the presentation by David Spiegelhalter and Mike Pearson](http://www.oecd.org/dataoecd/1/50/42417361.pdf?contentId=42417362); their presentation was geared toward (and succeeded in) linking data with decision making), I didn't read much about the technical side of things, so I thought I'd cover those areas here.

Here's the low-down:

- _Flash_: Clearly, the poster child of the whole seminar was Adobe's Flash. It was the visual tool's lingua franca of most of the sites and visualization tools out there, with a few notable exceptions (most exciting of which was Ben Fry's _[Processing](http://processing.org)_; but more about that below...). Some of the implementations were rather simplistic uses of Flash, but others (such as the NYT's use of Flash, shown off by Amanda Cox) were clearly professional and very well polished.
- _XML_: Some talk about XML surfaced, but the only substantive discussion focused on the SDMX initiative -- [The ECB SDMX Visualisation Framework: The Birth of an Open Source Project](http://www.oecd.org/dataoecd/36/52/42493055.pdf?contentId=42493056) by Xavier Sosnovsky and Christine Sommo (European Central Bank; Federal Reserve Bank of New York). Their discussion was also one of the most technical presentations, along with Julia Ogris's interesting presentation (see the next bullet). They are using ActionScript 3.0 and SDMX v2. Amazingly enough, they post their code on Google Code as [flex-cb](http://code.google.com/p/flex-cb/). After failing to gather traction in their home department, they secured permission to harness the power of open source and post it for world-wide distribution at Google. Good for them!!
- _Google_: Other than Sosnovsky/Sommo, Julia Ogris is also using Google, but in a different way. She described her project at Space-Time Research as being built on [Google Web Toolkit](http://code.google.com/webtoolkit/), [REST](http://en.wikipedia.org/wiki/Representational_State_Transfer), and [Ajax](http://en.wikipedia.org/wiki/Ajax_%28programming%29) on top of a "simple and stateless servlet layer." Looks very interesting, though I would have loved to hear more about the technical details. She was clearly thrilled with the technical side of things, but still had the presence of mind to make clever and insightful comments like "you can be stylish and charming" (i.e. you can look good and be useful at the same time) and "things that look the same should act the same" -- sounds like good Tufte-like advice to me.
- _Java_: There were some tools using Java, but most of them were websites, not applets.
- _Databases_: While there was no discussion (that I can recall) identifying specific database vendors or types, there were clearly databases all throughout the presentations. (Again, Fry's presentation was an exception: he prefers to work with textual databases, rather than structured, RDBMSes, echoing sentiments he conveys in his _Visualizing Data_ book (O'Reilly). I can understand his point, but don't agree -- structured RDBMSes (or, increasingly, ORDBMSes) are a must-have for large, related datasets.) Most of the discussions regarding databases where focused on their user interface (typically web-based, such as [the Life Table database](http://lifetable.de) or the DevInfo database, or the recently-released [Data.gov](http://data.gov)), rather than their back-room incarnations. That's fine... trade secrets, and all that. I understand... :)
- _Wiki_: The most entertaining presentation of the seminar was Peter Meyer's presentation on Statipedia ([test site](http://osptest.net/mediawiki/)). Clearly energetic and enthusiastic about his topic, Mr. Meyer was an eloquent and straight-shooting spokesman. A lot of challenges, but he's confident that the wiki, when properly managed, is a solid solution for data distribution and assessment.
- _R_: Di Cook had an interesting talk on visualization that benefitted from collaboration with [Hadley Wickham](http://had.co.nz/) (of [ggobi](http://www.ggobi.org/) fame). Nice work, and highly visual, but didn't even scratch the surface of R (though she clearly loves the power of the language).
- _Processing_: Unfortunately, Ben Fry's presentation was a disappointment. Largely a rehash of his book, he walked through is (admittedly very cool) zip code program (but that's also covered in the first few pages of his book) and talked about some of his genome visualizations, which are covered on his website. Unfortunately, he didn't get into the language itself or why it should be the tool in your toolbox. Very slick stuff, but little substance or guidance.

I hope this was useful.
