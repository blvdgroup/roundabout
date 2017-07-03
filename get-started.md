---
layout: page
title: "Get Started"
---

## Download

[Click here](https://github.com/blvdgroup/roundabout/archive/master.zip) to download the latest (zipped) copy of Roundabout.

You can also clone the repository on GitHub.

```bash
$ git clone https://github.com/blvdgroup/roundabout.git
```

## Developing & running locally

Requirements:
* Ruby (v2.4.0+)
* Bundler - `gem install bundler`
* [Jekyll](http://jekyllrb.com/) - `gem install jekyll`
* [Node.js](https://nodejs.org/en/) (latest LTS is recommended) - Optional, for additional developer tools

Extract it, `cd` to the root directory of the extracted theme, and then install all the bundled Rubygems.

```bash
$ bundle install
# Or use the `bundle` shorthand
$ bundle
```

After the plugins are installed, we can now run a local server from within our computer.

```bash
$ bundle exec jekyll serve
```

Now you can work on your own Jekyll website! Open `localhost:4000` in your browser to view it locally. Any saved changes will be rebuilt by Jekyll, so refresh your browser when you do.

## Deploying

### GitHub Pages

Deploying to GitHub Pages is really simple,

Once it's properly configured just push your commits to your repository, set
