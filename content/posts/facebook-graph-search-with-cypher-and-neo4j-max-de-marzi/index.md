---
title: "Facebook Graph Search with Cypher and Neo4j | Max De Marzi"
date: "2013-01-31"
categories: 
  - "language"
  - "programming"
  - "tools"
tags: 
  - "facebook"
  - "neo4j"
  - "nlp"
  - "ruby"
---

> [Facebook Graph Search](http://www.neotechnology.com/2013/01/facebook-announces-its-third-pillar-graph-search/) has given the Graph Database community a simpler way to explain what it is we do and why it matters. I wanted to drive the point home by building a proof of concept of how you could do this with [Neo4j](http://www.neotechnology.com/). However, I don’t have six months or much experience with [NLP](http://en.wikipedia.org/wiki/Natural_language_processing) (natural language processing). What I do have is [Cypher](http://docs.neo4j.org/chunked/milestone/cypher-query-lang.html). Cypher is Neo4j’s graph language and it makes it easy to express what we are looking for in the graph. I needed a way to take “natural language” and create Cypher from it. This was going to be a problem.

via [Facebook Graph Search with Cypher and Neo4j | Max De Marzi](http://maxdemarzi.com/2013/01/28/facebook-graph-search-with-cypher-and-neo4j/).

The article is an interesting introduction to [treetop](http://treetop.rubyforge.org/) (a "language for describing languages" used in [Semr](http://semr.rubyforge.org/), a "framework to \[support\] natural language processing") and how Mr. De Marzi uses it to create a simple Facebook Graph-like search using Neo4j. Very slick.
