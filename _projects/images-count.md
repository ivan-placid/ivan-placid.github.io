---
layout: page
title: "File system research"
---

### Problem
Another surprising task from Novatour. This time I was asked to build a report for image existence in special folder structure (product images ofc) asap. 
### Solution
While preparing tea, I was in doubt what to choose, grep/cat pipeline or my favorite tool -- python. Suddenly I realised that old Unix utility [tree](https://en.wikipedia.org/wiki/Tree_(Unix)) can solve the problem almost entirely. Due to the lack of time I decide to use that mature solution. After a bit polishing tree output in Sublime Text desired csv was ready. Voilà! If you dont want to mess with feature-rich text editors, you can use [this](https://gist.github.com/bdsexton/f013197c22016244f32a) bash snippet.