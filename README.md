# Salico Development Blog

For MTE481 coursework.

## How do a serve the site locally?

Clone the repo and then cd into it. Then run:
```
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

## How do I create a new post?
Make a new file under `_posts/`, such as `_posts/2024-09-15-myfirstpost.md`. Add the following header in the file:
```
---
layout: post
title: <Insert title here>
---
INSERT YOUR CONTENT HERE
```
Then, simply write your content in [markdown](https://www.markdownguide.org/basic-syntax/). This will be rendered into HTML automatically.

Once you're done, create a pull request. Once merged, it will be deployed automatically, takes about a minute.

## Credits
Forked from [Beautiful Jekyll template](https://github.com/daattali/beautiful-jekyll).
