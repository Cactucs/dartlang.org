---
layout: default
title: "Pub Package and Asset Manager"
---

# {{ page.title }}

{% include toc.html %}

You can use the `pub` tool to manage Dart packages and assets.
Pub also includes commands for creating, developing, and deploying Dart
applications.
When you [download](/tools/download.html) either Dart Editor or
the Dart SDK, one of the tools that you get is `pub`.

You can access the `pub` commands either through Dart Editor or
the command line, so use whatever approach is most convenient.

## Managing packages

Dart applications rely on packages. If your Dart app uses one or
more library packages, then your app itself must be an
application package.

### How to

* [Getting Started with Pub](get-started.html)
* [Installing and Configuring Pub](installing.html)
* [Publishing a Package](publishing.html)

### Concepts

* [Pub Dependencies](dependencies.html)
* [Pub Package Layout Conventions](package-layout.html)
* [Pub Assets and Transformers](assets-and-transformers.html)
* [Pub Versioning Philosophy](versioning.html)

### Reference

* [Pubspec Format](pubspec.html)
* [FAQ](faq.html)
* [Glossary](glossary.html)

## Pub commands

The `pub` tool provides a number of commands for a variety of purposes.
One command installs packages, another starts up an HTTP server for testing,
another prepares your app for deployment, and another 
publishes your package to [pub.dartlang.org](http://pub.dartlang.org).

For an overview of these commands, see [Pub Commands](cmd/index.html).

The following reference pages cover each command in detail:

* [`pub build`](cmd/pub-build.html)
* [`pub cache`](cmd/pub-cache.html)
* [`pub get`](cmd/pub-get.html)
* [`pub publish`](cmd/pub-lish.html)
* [`pub serve`](cmd/pub-serve.html)
* [`pub upgrade`](cmd/pub-upgrade.html)
* [`pub uploader`](cmd/pub-uploader.html)

## Writing transformers

When `pub` serves or builds an app, it can run one or more
transformers&mdash;for example, one transformer converts Dart
files into a single JavaScript file.

Transformers operate on assets, where an asset is
a resource, such as a Dart file, a CSS file, or an
image, that is intended to be part of a deployed package.

Writing a transformer is an advanced topic that we don't yet document.
For now, you might find the following resource useful:

* [Barback - Can We Build It? Yes, We Can!](https://docs.google.com/a/google.com/document/d/1juHkCRg-1YH6LvwhGPHgF2ihX-UQtR1fv-8aknO7t_4/edit?pli=1#)
