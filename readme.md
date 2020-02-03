# Introduction to Webpack

The goal for this repo is to introduce anyone working with front-end technologies to the benefits of Webpack. 

Webpack is a module bundler, and it's purpose is to take a complex and diverse set of development assets, and bundle them into manageable chunks for consumption (in this case, by a web browser).

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

### FAQ

#### Why are we using Bootstrap and jQuery?

The popularity of these frameworks indicates that at one point or another, most of us had some level of familiarity with them. By taking advantage of libraries people already know (or at the very least ahve heard of) there's hopefully more focus and attention given to the topic of this training: Webpack.