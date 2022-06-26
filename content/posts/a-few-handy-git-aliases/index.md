---
title: "A few handy git aliases"
date: 2022-06-26T12:44:37Z
draft: true
hidemeta: false
comments: false
hideSummary: false
# showToc: false
# TocOpen: true
# UseHugoToc: true

cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---

Git aliases are shortcuts that you create to shorten and customize git commands. A git alias is equivalent to a [bash alias](https://linuxize.com/post/how-to-create-bash-aliases/) with the difference that it works only prefixed with `git`, as a user-defined git argument.

Before moving on, I think is important to mention where do git configurations (aliases included) are saved.

Git stores its configurations (aliases inlcuded) in multiple files with the name: gitconfig.

The **user level configurations** are effective to *all* repository you, the user, work in.

Check
 The user also because they get stored into you repo git configuration (`.git/config`) or, more commonly, at a user level (`~/.gitconfig`).


For example, instead of always typing in the long 

```bash
git show --format=fuller
```

to inspect commit information, 


TOC

A few handy git aliases

- shortening the post commod operation

git status --> st
git commit --> ci
git checkout --> co
git push ---> ps

Visualize the git graph

git lol


uncommit --> reset HEAD^
unci --> uncommit


-----

other useful....



-----
in case of fire




Credits:

- https://idiv-biodiversity.github.io/git-knowledge-base/aliases.html#in-case-of-fire
- https://gist.github.com/outro56/31e588e5622dcf7931de0aee49baa7b2
- https://github.com/mitsuhiko/dotfiles/blob/master/git/gitconfig