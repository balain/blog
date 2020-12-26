---
title: "OT/NT Refs: Development log, entry #5"
date: "2011-07-08"
categories: 
  - "christianity"
  - "data-visualization"
  - "design"
  - "graphic-design"
  - "programming"
  - "tools"
  - "website"
tags: 
  - "paper-js"
---

## [![otnt-rev8](images/otnt-rev8-300x145.png "otnt-rev8")](https://blog.balinsbooks.com/wp-content/uploads/2011/07/otnt-rev8.png)Completed

- Added layers (Quotations, Allusions, and Possible Allusions are all on separate layers, independently controllable (see below), as are the book arcs);
- Added panning (click-and-drag to move);
- Added keyboard event handler (to toggle visibility of layers ("q"/"a"/"p" for 3 link layers, "b" for book arcs, "c" to recenter view\*, and "r" to reset view to initial state\*);
- Added zoom ("+" and "-" to zoom in and out, respectively)

## ToDo

_In priority order:_

- Add book labels
- Fix intermediate point calculation
- Post code to Github
- Add basic interactivity \[zooming & panning\]
- Add advanced interactivity \[to show links for a specific book (a la http://www.nytimes.com/interactive/2007/12/15/us/politics/DEBATE.html)\]
- Add columns for each chapter (why?)
- Add mouse scroll wheel zoom handler
- Add the allusion links and possible \[allusion\] links
- Set up correct Z-order (handled by order of function calls)
