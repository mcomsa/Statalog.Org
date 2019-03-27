---
layout: blog
title: Adding to the Statalog Blog
---

# Adding a Blog Post

New posts are always welcome. This website is managed as a [github repo][repo] using jekyll and deployed via github pages. You can submit posts in 2 ways:

## Using Google Docs (less geeky)

1. Write up your post in a google doc
   * use markdown or html formatting if you can
2. [Get in touch][contact] (email may be best) and we'll get it up online

## Direct to the repo (more geeky)

Using "Fork and pull" on the [github repo][repo]:

[repo]: https://github.com/statalog/statalog.github.com
[contact]: /contact/

1. Blog posts go in `blog/_post/` folder. As per jekyll convention they should be
   named `yyyy-mm-dd-{slug-for-post}.md`

   If your post is html rather than markdown just change extension from `.md` to `.html`.

2. Add content. The structure should be:

        ---
        author: {Your Name}
        username: [optional] {your-user-name-if-you-have-one}
        title: {Title Like This - this is used both in page and html title}
        projects: [optional] {project slug, project slug...} (use if your post references Open Knowledge Labs projects)
        ---

        content in html or markdown goes here ....

   You need to quote any fields that contain a colon (:). For example,

        ---
        author: {Your Name}
        title: 'CatchyName: Doing this thing with that thing'
        ---

3. Add and commit the file then submit the pull request (if you are not pushing direct to the main repo)
