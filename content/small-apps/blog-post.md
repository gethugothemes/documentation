---
title: 'Blog Post'
date: '2019-07-28T04:29:54-03:00'
weight: 6
draft: false
---
Hugo provides a `new` command to create a post, as a example for creating a new post is `hugo new blog/new-post.en.md` , it will create a post.

Configure Post
--------------

You can configure your blog post from the front-matter. Front-matter starts with `---` and end with also `---` . In this front matter you can give `author = author name` , `description = meta description`, `image = images/blog/post-thumb.jpg`, `bgImage = image.jpg`( background image is for page header), `categories` and `tags`. \*\*One thing is remember that you must need to declare the `type = post`. \*\*

When you created a new post, the `draft` default value is true, and when the draft is true your post will not show, you need to change it for showing this post. like `draft = false`. Only then your post will show in blog page.

After closing front matter give your post content, remember that every file that has an `.md` extension, are supports markdown.