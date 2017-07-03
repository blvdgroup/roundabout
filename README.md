# Roundabout

> Minimalist, customizable Jekyll theme.

[**TODO:** Extended description.]

## Developing & running locally

Requirements:
* Ruby (v2.4.0+)
* Bundler - `gem install bundler`
* [Jekyll](http://jekyllrb.com/) - `gem install jekyll`
* [Node.js](https://nodejs.org/en/) (latest LTS is recommended) - Optional, for additional developer tools

To get started, download the latest zipped build of the Roundabout [here](https://github.com/blvdgroup/roundabout/archive/master.zip).

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

### Optional development tools

This theme also provides additional development tools with [Node.js](https://nodejs.org/en/).

**TODO:** Consider using gulp? Some of these commands are a little finicky. [This old gruntfile](https://github.com/resir014/resir014.github.io/blob/master/Gruntfile.js) that I did for my current website is a good place to start.

Run the following command to install them.

```bash
$ npm install
```

To optimise image files before pushing to the repo, run this command.

```bash
$ npm run optimise
```

**TODO:** This is on hold until [imagemin/imagemin-cli#11](https://github.com/imagemin/imagemin-cli/pull/11) is implemented. Also see above TODO.

## License

Source code is licensed under [MIT](LICENSE).