---
title: Powerful Dynamic Lookups
---

### Project summary
Come up with a dynamic screen and set of components to use for looking up and returning data
### Project goals
1.) This had to be capable of handling large amounts of data.  This ruled out all of the options out there with limited flexibility in that area. 

2.) Dynamic columns, and highly modular and re-usable code.

I checked out selectize, select 2, etc.  My biggest problem with them being there is no actual lookup button.  I would not want to query the database for results when the user types in many cases, as nice as that feature may be at times.  I spent a great deal of time hacking these components up to accomplisih these goals, but ended up going a different route.

*End result was a combination of a component called ui-grid, and basic bootstrap form controls.  I was able to homeroll from there.
Check out a very minimal but highly functional example in [plunkr](https://plnkr.co/edit/WJssKB)
