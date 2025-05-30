---
title: Version control system
summary: Git review, pros and cons
date: 2025-02-27

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'

authors:
  - admin
  -  J. Panina

tags:
  - Academic
  - Git
  - Markdown
---

{{< toc mobile_only=true is_open=true >}}

## Version control systems

A version control system is software that facilitates work with changing information. A version control system allows you to store several versions of the same document, if necessary, return to earlier versions, determine who made a particular change and when. Such systems are widely used in software development for storing source codes. However, they can also be used in other areas where work is carried out with a large number of continuously changing electronic documents
A VCS allows you to return the entire project to its previous state, compare changes from a certain time, see who last changed the module that failed, who created the problem, and more.

[//]: # ([![The template is mobile first with a responsive design to ensure that your site looks stunning on every device.]&#40;https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/starters/academic/preview.png&#41;]&#40;https://hugoblox.com&#41;)

## Git. Advantages and Disadvantages

Git is one of the most popular version control systems in the world of software development. It was developed by Linus Torvalds in 2005 and is distinguished by its speed, flexibility, and distributed architecture. [1]
The main features of Git include the ability to create local repositories on the developer's computer, quick branching and merging of changes, effective project management of any size, and good support for working with branching and merging. In addition, Git has extensive capabilities for customizing the workflow and integrating with various hosting services, such as GitHub and Bitbucket. (fig. @fig:002).
The main difference between Git and any other version control system is the way Git views its data. Basically, most other systems store information as a list of changes for files. These systems treat the stored data as a set of files and changes made to each of these files over time.

## Advantages of Git

1. A reliable system for comparing revisions and checking the correctness of data.
2. A flexible system for branching projects and merging branches with each other.
3. The presence of a local repository containing complete information about all changes allows you to maintain full local version control and upload only fully verified changes to the main repository.
4. High performance and speed.
5. A convenient and intuitive set of commands.
6. Multiple graphical shells.
7. The ability to create checkpoints where data is saved not using delta compression, but completely. Due to this, the speed of data recovery is reduced, since the closest checkpoint is taken as a basis, therefore, recovery is carried out from it.
8. Widespread use, easy accessibility and high-quality documentation.
9. The flexibility of the system allows you to conveniently configure it and even create specialized user interfaces based on Git.
10. Universal network access using http, ftp, rsync, ssh and other protocols

## Disadvantages of Git

1. Unix-oriented. At the moment, there is no official full-fledged implementation of Git compatible with other operating systems, such as Windows, Mac OS and the like.
2. Possible (but extremely low) matches of the hash code of revisions with different content.
3. Only changes to the entire project are tracked, not individual files, which can be inconvenient when working with large projects containing many unrelated files.
4. When initially (first) creating a repository and synchronizing it with other developers, it will take quite a long time to download the data, especially if the project is large, since it will be necessary to copy the entire repository to the local computer
## Summary

Git, due to its speed, flexibility and distributed architecture, is well suited for developing various projects and has extensive customization and integration capabilities.



