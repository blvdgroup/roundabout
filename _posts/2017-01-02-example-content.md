---
layout: post
title: Example content
subtitle: "This is an example blog post that shows several types of HTML content supported in this theme."
# header_image_url: https://placehold.it/1140x350
---

# Heading 1

<p class="lead">Lead paragraph - Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempore eos minus eaque natus magnam, placeat. Ea iusto obcaecati modi aliquid, mollitia earum, ratione temporibus iste totam fugiat.</p>

Quibusdam excepturi vero, voluptatibus cumque mollitia quisquam dolorum unde, maiores quam necessitatibus quos. Pariatur nulla sequi qui aut fuga deserunt reiciendis, laboriosam, labore temporibus eligendi optio assumenda voluptates, vero nemo.

Cum sociis natoque penatibus et magnis <a href="#">dis parturient montes</a>, nascetur ridiculus mus. *Aenean eu leo quam.* Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Cras mattis consectetur purus sit amet fermentum.

> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

Etiam porta **sem malesuada magna** mollis euismod. Cras mattis consectetur purus sit amet fermentum. Aenean lacinia bibendum nulla sed consectetur.

## Heading 2

Dolorum nemo ducimus esse animi sunt, ratione? Fuga eaque voluptatibus, odit asperiores dolorum, accusamus voluptas repellendus reprehenderit magni quidem cumque tempore impedit, iure explicabo illum commodi. Quo deleniti, voluptatibus iste.

### Heading 3

Labore fuga architecto accusantium natus hic omnis rem consequatur magnam est eaque et ullam quas voluptates quidem temporibus blanditiis iusto, possimus optio doloremque, exercitationem alias. Itaque non mollitia modi enim.

#### Heading 4

Nisi et odio ex architecto, saepe voluptate consequuntur autem voluptatem error a magni assumenda at iusto! Nostrum totam dolorem, nesciunt ipsum quaerat explicabo ut praesentium dolor eaque, voluptates tempore recusandae.

##### Heading 5

Sint repellat accusamus error assumenda libero quae provident earum et, consectetur reiciendis odit eum iusto quos officia amet ipsam, sunt. Voluptatibus maxime asperiores, expedita itaque ut animi quod accusantium eius.

###### Heading 6

Repellat, veritatis consectetur repudiandae vel ratione assumenda voluptate quam enim velit fugit, quae nobis laboriosam quod ullam inventore aliquid architecto molestiae fuga ipsum iure. At voluptatibus minima, dolores recusandae provident.

## Misc style

### Inline HTML elements

HTML defines a long list of available inline tags, a complete list of which can be found on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

- **To bold text**, use `<strong>`.
- *To italicize text*, use `<em>`.
- Abbreviations, like <abbr title="HyperText Markup Langage">HTML</abbr> should use `<abbr>`, with an optional `title` attribute for the full phrase.
- Citations, like <cite>&mdash; Mark otto</cite>, should use `<cite>`.
- <del>Deleted</del> text should use `<del>` and <ins>inserted</ins> text should use `<ins>`.
- Superscript <sup>text</sup> uses `<sup>` and subscript <sub>text</sub> uses `<sub>`.

Most of these elements are styled by browsers with few modifications on our part.

### Blockquote

> Error veritatis in magnam saepe officia quis. Rem laborum, blanditiis.

<blockquote>
  <p>I mean, they say you die twice. One time when you stop breathing and a second time, a bit later on, when somebody says your name for the last time.</p>
  <cite>&mdash; Banksy</cite>
</blockquote>

### Video embeds

Video embeds should be wrapped inside a `<div class="video-wrapper">...</div>` element. This will ensure that the video scales properly according to container size.

<div class="video-wrapper">
  <iframe width="1280" height="720" src="https://www.youtube.com/embed/g1GEY9k34AI" frameborder="0" allowfullscreen></iframe>
</div>

### Twitter embeds

Twitter embeds will automatically be aligned to the center of the current container.

<blockquote class="twitter-tweet" data-lang="en"><p lang="und" dir="ltr"><a href="https://t.co/kE6fCM8y1K">pic.twitter.com/kE6fCM8y1K</a></p>&mdash; sunny out of context (@iasipmeme) <a href="https://twitter.com/iasipmeme/status/870304937648979968">June 1, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

### Footnotes

Footnotes are supported as part of the Markdown syntax. Here's one in action. Clicking this number[^fn-sample_footnote] will lead you to a footnote. The syntax looks like:

```
Clicking this number[^fn-sample_footnote]
```

Each footnote needs the `^fn-` prefix and a unique ID to be referenced for the footnoted content. The syntax for that list looks something like this:

```
[^fn-sample_footnote]: Handy! Now click the return link to go back.
```

You can place the footnoted content wherever you like. Markdown parsers should properly place it at the bottom of the post.

### Code

Example of code content using Rouge as the default Jekyll syntax highlighter. Longer lines will automatically scroll horizontally when needed.

```js
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
```

Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa.

### Gists via GitHub Pages

Vestibulum id ligula porta felis euismod semper. Nullam quis risus eget urna mollis ornare vel eu leo. Donec sed odio dui.

{% gist 13f94b734a4ddb132735 gist.md %}

Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec sed odio dui. Vestibulum id ligula porta felis euismod semper.

### Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

* Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
* Donec id elit non mi porta gravida at eget metus.
* Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

<dl>
  <dt>HyperText Markup Language (HTML)</dt>
  <dd>The language used to describe and define the content of a Web page</dd>

  <dt>Cascading Style Sheets (CSS)</dt>
  <dd>Used to describe the appearance of Web content</dd>

  <dt>JavaScript (JS)</dt>
  <dd>The programming language used to build advanced Web sites and applications</dd>
</dl>

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

### Images

Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![placeholder](https://unsplash.it/800/400/?random "Large example image")
![placeholder](https://unsplash.it/400/200/?random "Medium example image")
![placeholder](https://unsplash.it/200/200/?random "Small example image")

(Placeholder images provided by [Unsplash.it](https://unsplash.it/))

### Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

-----

Want to see something else added? <a href="https://github.com/poole/poole/issues/new">Open an issue.</a>

[^fn-sample_footnote]: Handy! Now click the return link to go back.
