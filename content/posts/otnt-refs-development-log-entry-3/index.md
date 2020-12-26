---
title: "OT/NT Refs: Development log, entry #3"
date: "2011-07-05"
categories: 
  - "christianity"
  - "data-visualization"
  - "graphic-design"
  - "software"
  - "tools"
  - "website"
tags: 
  - "paper-js"
---

## [![otnt-rev5](images/otnt-rev5-150x150.png "otnt-rev5")](https://blog.balinsbooks.com/wp-content/uploads/2011/07/otnt-rev5.png)Completed

- Added all the direct quotation links
- Fixed the link lines (now they point to the correct location (based on the chapter of the reference) on the arc, not the first point)
- Added some color (a little different than in my first post, but same groupings) to the links;
- Shrank the arc depth;
- Expanded the size of the whole graphic.

## **To Do**

Same as in in [my first dev log entry](https://blog.balinsbooks.com/2011/07/03/otnt-refs-development-log-entry-1/ "OT/NT Refs: Development log, entry #1") plus:

- Fix the intermediate point calculation for the arcs (see how they bunch up unnaturally and too often go on the wrong side of the center point when they should stay on the same side of the center point);
- Add the allusion links (dashed? dotted?) and possible links (thinner line?)
- Set up the correct Z-order for the links

## Performance

**Size:** 66 books + 306 links/lines.

It takes about 3 seconds to load/draw on Safari and around 4 seconds on Firefox. It won't run on Chrome ("XMLHttpRequest cannot load file:.... Cross origin requests are only supported for HTTP.").
