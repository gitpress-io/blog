---
title: Using RSS and Atom Feed
date: 2019-03-10
---

built-in RSS and Atom feeds have been added for all users and collections. 

When you publish articles on your page or a collection, its RSS feed automatically updates, creating the new content as an .xml file. Any external feed services that subscribe to the feeds will pull this new content. 

## The feed Urls

GitPress feeds pull most recent 50 items as artciles and them will look like one of these:

```
https://gitpress.io/@{{USERNAME}}/feed
https://gitpress.io/@{{USERNAME}}/feed/atom.xml
https://gitpress.io/@{{USERNAME}}/feed/rss2.xml
https://gitpress.io/c/{{COLLECION_SLUG}}/feed
https://gitpress.io/c/{{COLLECION_SLUG}}/feed/atom.xml
https://gitpress.io/c/{{COLLECION_SLUG}}/feed/rss2.xml
```

For example, if your username is "johnmilton"，your feed urls are 

```
https://gitpress.io/@johnmilton/feed
https://gitpress.io/@johnmilton/feed/atom.xml
https://gitpress.io/@johnmilton/feed/rss2.xml
```

