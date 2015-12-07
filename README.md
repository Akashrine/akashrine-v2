# MINIMAL

## What is this?

MINIMAL is a starting point for prototyping responsive HTML5 SASS projects.
Uses gulp to create a dev environment for rapidly prototyping sites. We stole the foundation of this project from [Adam Morse](https://github.com/mrmrs) his [MNML](https://github.com/mrmrs/mnml) project.

## Features

* sass compilation
* lightweight postcss use
* css minification
* css linting
* autoprefixer (automatically adds appropriate vendor prefixes)
* css-mqpacker (packs the same css media query rules into one media query rule)
* browser reload on filesave
* local server for serving a static site

## Getting started

### Instructions

* Create a new repo for your project on Github
* In terminal run each line as a separate command
```bash
    git clone git@github.com:sudhq/minimal.git yourNewRepoName
    cd yourNewRepoName
    rm -rf .git
    git init
    git remote add origin git@github.com:yourUserName/yourNewRepoName.git
```

* git remote -v will allow you to check that you have changed the remote origin correctly. The output should look like:
```bash
    origin git@github.com:yourUserName/yourNewRepoName.git (fetch)
    origin git@github.com:yourUserName/yourNewRepoName.git (push)
```

## Dev environment
To set up a convenient dev environment run this at the root of mnml

```bash
npm install && npm start
```

Gulp is a javascript task runner. It compiles sass, lints the compiled css, and
sets up a browser-sync server so you can save your fingers from pressing ⌘+TAB + ⌘+r
every time you save a file.

* Once you add & commit files you are ready to publish run:
```bash
git push origin master
```

# Author

[Roy Lodder](http://roylodder.com "Roy Lodder - Designer Developer")

# License

The MIT License (MIT)

Copyright (c) 2015 Upside Down

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

