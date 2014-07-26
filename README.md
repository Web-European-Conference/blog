# Web European Conference Blog

This blog is built using [Jekyll](http://jekyllrb.com/).

## Testing

[HTML::Proofer](https://github.com/gjtorikian/html-proofer) is set up to validate all links within the project.  You can run this locally to ensure that your changes are valid:

```shell
bundle install
bundle exec rake test
```

## Add new post
```ruby
rake post title="Hello World"
```

## Add new page
Create pages easily via rake task:

```
$ rake page name="about.md"
```

Create a nested page:

```
$ rake page name="pages/about.md"
```

Create a page with a "pretty" path:

```
$ rake page name="pages/about"
```

this will create the file: ./pages/about/index.html

Both pages and posts will be created with the right formatted filename and YAML Front Matter

## Jekyll post headers

There are several variables you can specify in the header of the post

```
---
layout: post
date: 2014-07-28
title: "Announcing second Web European Conference"
description: "Announcing the 2nd Web European Conference, next Spring, in Italy"
imagePath: /assets/2014/07/first_post_poster_image.jpg
comments: true
categories:
- News
tags:
- conference
- sponsor
- c4p
- c4v
---
```

- imagePath is optional. In case you specify it a poster image will showed in top of the post and the same image will used for the [Twitter Card](https://dev.twitter.com/docs/cards) and [Facebook OpenGraph](http://ogp.me/)
