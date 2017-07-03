# Roundabout

> Minimalist, customizable Jekyll theme.

[Download the latest (zipped) copy here.](https://github.com/blvdgroup/roundabout/archive/master.zip)

[**TODO:** Extended description.]

## Developing & running locally

Requirements:
* Ruby (v2.4.0+)
* Bundler - `gem install bundler`
* [Jekyll](http://jekyllrb.com/) - `gem install jekyll`
* [Node.js](https://nodejs.org/en/) (latest LTS is recommended) - Optional, for additional developer tools

To use this theme for your Jekyll website, first download the latest zipped build of the Roundabout [here](https://github.com/blvdgroup/roundabout/archive/master.zip).

You can also clone the repository on GitHub.

```bash
$ git clone https://github.com/blvdgroup/roundabout.git
```

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

### Optional development tools

This theme also provides additional development tools with [Node.js](https://nodejs.org/en/).

Run the following command to install them.

```bash
$ npm install
```

Our commit logs are [Commitizen-friendly](https://commitizen.github.io/cz-cli/). We use Commitizen with the `cz-blvd` extension as part of our commit naming conventions. To use it we can simply use the Commitizen CLI.

```bash
# Install the Commitizen CLI
$ npm install -g commitizen
# Install our dependencies if you haven't already (`cz-blvd` will be downloaded now.)
$ npm install
# To commit using the Commitizen conventions, you can choose either of these two commands:
$ git cz
$ npm run commit
```

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

## Contributing

Issues and Pull Requests are welcome! Please read our [Contributing Guidelines](https://github.com/blvdgroup/guidelines) & [Code of Conduct](https://github.com/blvdgroup/guidelines/blob/master/CONDUCT.md) beforehand.

As a general rule of thumb:

1. [Fork it.](https://github.com/blvdgroup/roundabout/fork)
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Create a new Pull Request.

## License

Source code is licensed under [MIT](LICENSE).
