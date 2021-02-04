---
layout: post
title: Workflow: Notion-Atom-GitHub-Fleek-IPFS-devid.eth.link
subtitle: How I publish content to this Decentralised site
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [Fleek]
show-avatar: false
last-updated: 04-02-2021
publish: true
---

# Workflow for publishing posts

I'm not a software developer, not by a long way. These days, tools available to software development are very accessible to those of us for whom publishing an article like this is a technical wonder.

This is not full automation, but with a few clicks, this flow allows me to go from taking notes on my phone, to controlled publishing on *my own site* on the *Decentralised Web*. And GitHub sits in the middle, so I have a platform to manage content at a code level. Having build a site on WordPress with the endless plug-ins, I'd rather do it this way.

## The Workflow

This is how it all fits together:

< put diagram in here >

[//] <> <img src="/assets/img/lpt-post/lpt_img_1.jpeg" width="500" height="300" alt="" class="center"/>

### The building blocks

What do these building blocks do, and how do we move content from first to last?

[Notion](https://www.notion.so/) is a note taking app that supports markdown. Markdown is a super easy text markup language that's perfect for simple editing like this, without getting wrapped up in commercially available documentation applications with lots of superfluous WYSIWYG metadata. And it helps you with that *focus*.

With Notion, it's easy for me to capture notes on the fly, sit anywhere and commit thoughts to phone app, then compile something more meaningful and structured when online. It's also very easy to share specific pages for review and editing.  

And we can export in markdown. Good, because our website posts are markdown files. I don't want to be file converting further down the chain. So we export to the laptop, and onto the next step.

[Atom](https://atom.io/) is described on their site as a 'hackable text editor for the 21st Century'. I'm not planning on writing in the 22nd Century, so it's a good tool for three things:

1. Adding my YAML Header, more below, and managing the image files used in the posts.fl

2. Re-reading the post in a different format. This helps as a double check for errors.  

3. Managing the other files, which are not posts, that make up the website.

YAML Header: it's few lines that go at the top of the post file which instruct the website how to manage the page within the Jekyll build. This site is build on Jekyll, one of the options within GitHub for creating websites. Thanks to [Beautiful Jekyll](https://beautifuljekyll.com/) for the template code for this site. And it's within this that the 'other files' exist which need the occasional tweak.

<img src="/assets/img/post_publish/YAML_Example.png" width="500" height="300" alt="This post's YAML header" class="center"/>

[GitHub](https://github.com)

Time to break out a Terminal Window. When we exported the markdown file from Notion, it's saved within the website file structure. This is a 'clone' of the site repository on GitHub. So, when I'm ready with edits, I can push these edits to a new repository using some [git commands](https://training.github.com/downloads/github-git-cheat-sheet/), and then head to GitHub.

Where I can preview changes and publish to the main site repository. We are ready to hit the web.

I've got GitHub set up to publish through their website facility and this site can also be viewed [here](https://msmctech.github.io/), but where's the fun in that. Bring on Web3.

[Fleek](https://fleek.co/), according to their website:

> Fleek makes it easy to build websites and apps on the new open web: permissionless, trustless, censorship resistant, and free of centralized gatekeepers.

Well, it does. Sign in, go to the hosting area, link your GitHub repository to their deployment tool, that's it. There are a few options if you like, but really, 5 minutes max from GitHub to on the Decentralised Web. I think that's quite amazing.

<img src="/assets/img/post_publish/fleek_co_1.png" width="500" height="300" alt="Ready on Fleek" class="center"/>

We can also use their Preview Deploy tool. And we can set our [ENS](https://ens.domains/) address, if that's your thing. For this site it's [devid.eth](devid.eth.link).  

Sit back and enjoy.

Here's a picture:

<img src="/assets/img/lpt-post/lpt_img_1.jpeg" width="500" height="300" alt="" class="center"/>
