# Sophie's Blog

## How to make a new post

1. Create a new file and name it like `YYYY-MM-DD-post-title.md`
2. Add the YAML header information:
```
---
layout: post 
title:  "Full Title of the Post"
---
```
3. Add the text to your file in markdown format
4. To add images, save them to the `assets` folder, then add `![alt-text](/assets/image-name.jpg)` to the blog post.
5. To see the post on your computer, open Terminal and go to the blog directory
6. Run `bundle exec jekyll serve`
7. Once you are happy with the blog post, add it to git:
  - `git add filenames` or `git add .`
  - `git commit -m "Message about the post"`
  - `git push origin`
  - you can check what is going on with git using `git status`
8. Wait a couple of minutes and the blog will be updated. Reload your page to check it out!