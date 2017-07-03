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

Deploying to GitHub Pages is really simple. First open your `_config.yml` file and update these config variables based on your hosting environment.

```yml
url: http://blvd.space
baseurl: "/roundabout"
```

The `url` config contains the **host** of your website, whereas the `baseurl` config contains the **base directory** of your generated site. The rule of thumb to these configurations is as follows:

* Set `url` the root domain of your host, **without** the trailing slash. For GitHub Pages with no custom domains, this should be `https://<username>.github.io`.
* If the generated page is a *user page*, then leave the `baseurl` config blank (e.g. `baseurl: ""`).
* If it's a *project page*, set it to the **name** of your project, **without** the trailing slash once again (e.g. `baseurl: "/roundabout"`).

Once it's properly configured just push your commits to your repository, set the GitHub pages settings on your repository to target to the branch where your files is hosted in, and you have yourself a working GitHub page!

Learn more about GitHub Pages deployment on the [Jekyll docs](https://jekyllrb.com/docs/github-pages/){:target="_blank"}.
