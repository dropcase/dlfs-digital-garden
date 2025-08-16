---
{"title":"Break. Fix. Repeat.","description":"I'll learn it someday, really","date":"2021-08-20","tags":["testing","webdev"],"dg-publish":true,"created":"2021-08-20T11:38:42","updated":"2025-08-09T22:39:51-04:00","permalink":"/output/write/2021/break-fix-repeat/","dgPassFrontmatter":true,"noteIcon":"3"}
---


## It Happened. Again.

Once of the ways I feel like I learn best is by fixing things. Whether it's code or writing or a process or a wonky light switch, starting from __working__ doesn't help as much as getting it to working.

That doesn't always mean that it's the way I should do it. Take for instance, this site. I've gone through a lot of iterations (see [[About\|About]]) in the past 18+ years and gone through quite a few issues - and learned a ton from them.

This latest setup is my second [[reference/2025/Static Site Generator\|SSG]] connected to Git`*`b ([[reference/2025/GitHub\|GitHub]] or GitLab), first time out using [[reference/2025/Eleventy\|Eleventy]], and very newly testing out Fomantic-UI (a fork of the seemingly-forgotten Semantic-UI) to help me with my poor frontend design skills.

## The Breakening

If you read through [[output/write/2018/Digging Out of an Issue\|Digging Out of an Issue]] you'll see where I dropped the ball with release version management. I hoped I had learned my lesson and would avoid issues like that in the future.

This time, I thought I had things ready to roll. I updated and tested locally, no problems and the `eleventy --serve` worked great. Files generated and the pages loaded, so I pushed the changes and let Netlify do its thing. Wait a few minutes, hit refresh, and... shit. Please, not again. I pinned versions, tested it - why did it fail?
