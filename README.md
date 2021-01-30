![Logo](HIP_banner.png "Hack In Place!")


> Today we're going to learn **git**! We're going to pratice cloning, adding, commiting, merging, and resolving merge conflicts! At the end of this lab you'll have a personal webpage that you can access at https://andrewdchen.github.io/HIP-A2CN/docs/ !

# Getting Started: 

1. Forking the repository. 
- See top right of page at this link: https://github.com/andrewdchen/HIP-A2CN
2. Cloning the repository.
```bash
git clone <url for your fork>
```
3. Making your markdown file. 
```bash
cd HIP-A2CN/docs  
touch *username*.md
```
Alternatively, you can make the markdown file via file explorer/finder.
> What is markdown? Markdown is a lightweight markup language for creating formatted text using a plain-text editor.[[1]](#1). This cheatsheet might be helpful for step 3: [Github Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

4. Editing your markdown file.
- Use your favorite texteditor e.g. TextEdit, Vim, Sublime to add your personalized content!

5. Adding and Committing your changes.
```bash
git add *username*.md
git commit -m "*username* initial commit"
```
**Additional practice:**

`git status` is a useful command for seeing what has changed relative to your latest commit or your HEAD pointer.
- Try `git status` before and after you `git add`. What does the message say? Can you undo `git add`? 
- Try `git status` after you `git commit`, what does the message say? Can you undo `git commit`?

6. Pushing your changes.
```bash
git push origin master
```
**Additional practice:** What does origin mean? What does master mean?

7. Create a pull request.
- More instructions here: [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)

8. Merge the upstream changes. 
```bash
git status
```
- `git status` also gives you instructions on what files have conflicts, and how to resolve the conflict.
- Use your favorite text editor to resolve the merge conflict.

## References
<a id="1">[1]</a> 
https://en.wikipedia.org/wiki/Markdown
