# web-preservation

## Goal
- Preserve webpages, including important resources on them, so that years later, one could perform any analysis on this webpage even if the webpage itself disappears.

## What's new
- How is it different from search engines such as Google?
    - We store not only existing pages, but also pages in the past (probably missing).
    - More than HTMLs are stored, including images/layouts/videos. Images/layout won't be interesting to search engines because their users give text query. But those resources may be missing in the future, while they important.
- How is it different from [WayBack Machine](https://archive.org/web/) that also stores the past webpages?
    - We only store important image resources (that are related and helpful to the article contents) on a given webpage (determined by our algorithm).
    - We reduce storage overhead, by eliminating redundancy.

## Challenges


## Current Progress
- Handled lazy-loading images (testing needed)
