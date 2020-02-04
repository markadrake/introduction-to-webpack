# Introduction to Webpack

The goal for this repo is to introduce anyone working with front-end technologies to the benefits of Webpack. 

Webpack is a module bundler, and its purpose is to take a complex and diverse set of development assets, and bundle them into manageable chunks for consumption (in this case, by a web browser).

[You can read more about Webpack here](https://webpack.js.org/concepts/), and [specific reasons to use a module bundler like Webpack here](https://webpack.js.org/concepts/why-webpack/).

## Goal

Build **a static website**, with dependencies on **jQuery** and **Bootstrap**, bundled by **Webpack**.

Through this process we'll make many achievements along the way:

- You'll setup a Node.js project.
- You'll install local versions of your dependencies and learn to reference them from a modular code base.
- You'll use Webpack to build your project with absolutely no configuration at all.
- You'll use Webpack Dev Server to speed up your development practices.
- You'll configure Webpack for what we call a production build. Static files output from the Webpack build process will be concatenated, transpiled, minified, chunked, and mapped.

## Our Tech Stack

Some of the technology, frameworks, and libraries we will be utilizing along the way:

- Git
- Node.js
- Webpack (v4+)
- jQuery (v3+)
- Bootstrap (v4+)

_Specific versions of the above technologies are mostly trivial. If a version number has been listed, it's recommended you try to stick to that major version._

_Bootstrap has a dependency on jQuery. Please make sure that you install compatible versions later on in the tutorial._

## FAQ

### Where do I start?

Read through the Table of Contents for an introduction and synopsis of each tutorial.

Tutorials are more like exercises. You'll find that each tutorial has its own branch, and you'll be expected to switch to the branch and follow along - sometimes installing, writing codes, or running tests. 

Each tutorial builds upon the work you did previously. If you get stuck along the way, feel free to checkout the next branch to see the solution.

### Prerequisites

The training moving forward suspects you know how to do a small number of things, but will try to be explicit as possible when giving directions that may trip up new developers:

- You have access to a computer and [operating system that supports Node.js](https://nodejs.org/en/download/).
- You have access to a major browser client, such as [Google Chrome](https://www.google.com/chrome/), [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), or [Microsoft Edge](https://www.microsoft.com/en-us/edge).
- You have written HTML, styled it with CSS, and controlled or expanded OOTB functionality with JavaScript.
- You have experience working with a Git repository and know the basics: pull, commit, switch branches, etc. The training will reference the command line interface for Git, but it's perfectly acceptable for you to use a GUI interface.

### Why are we using Bootstrap and jQuery?

The popularity of these frameworks indicates that at one point or another, most of us had some level of familiarity with them. By taking advantage of libraries people already know (or at the very least have heard of) there's hopefully more focus and attention given to the topic of this training: Webpack.

### Can I use [X] framework or library instead?

Yes, you can. 

But no, you shouldn't. What you learn and do here will leave you with the foundation for working on your own framework, library, applications, and sites after working through the tutorials.