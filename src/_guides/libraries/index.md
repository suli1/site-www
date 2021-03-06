---
layout: default
title: "Overview: Libraries"
description: "Learn about Dart's core libraries and APIs."
permalink: /guides/libraries
short-title: "Libraries"
toc: false
---

Dart programs rely on _libraries_.
Several common libraries are provided for you.
For example, `dart:core` provides a small but critical set of built-in functionality,
such as numbers, collections, and strings. Another essential library is
`dart:async`, which supports asynchronous programming with classes
like Future and Stream.
You can get additional libraries by importing them from _packages_.

Learn more about using, creating, and sharing Dart libraries and packages
at the following links.

<div class="card-grid">
  <div class="card">
    <h3><a href="/guides/libraries/library-tour">Tour of Dart Libraries</a></h3>
    <p>An introduction to the major features in Dart's core libraries.</p>
  </div>

  <div class="card">
    <h3><a href="/guides/libraries/useful-libraries">Commonly Used Libraries</a></h3>
    <p>Useful libraries that you should know about.</p>
  </div>

  <div class="card">
    <h3><a href="/guides/libraries/create-library-packages">Create Library Packages</a></h3>
    <p>How to create your own libraries.</p>
  </div>
</div>

## Other resources

API reference documentation
: * [api.dartlang.org:]({{site.dart_api}}/{{site.data.pkg-vers.SDK.channel}})
    API docs for dart:* libraries.
  * [docs.flutter.io:](http://docs.flutter.io/)
    API docs for Flutter libraries.
  * [pub.dartlang.org:]({{site.pub}})
    Published packages and their API docs.

Additional documentation for core libraries
: * [Futures and Error Handling](/guides/libraries/futures-error-handling):
    How to handle errors when writing asynchronous code.
  * [Articles about libraries](/articles/libraries):
    API topics ranging from zones to streams to converters.

Help on using and implementing packages
: * [Install Shared Packages](/tutorials/libraries/shared-pkgs):
    A beginner's guide to installing packages and using their libraries in your
    code.
  * [What Not to Commit](/guides/libraries/private-files):
    Which files, generated by your development tools, should not be committed
    to a code repo.
  * [pub](/tools/pub):
    A tool for managing Dart packages.
