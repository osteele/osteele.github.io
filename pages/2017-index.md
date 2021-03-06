---
layout: default
title: Oliver Steele | Code
permalink: /2017-index.md
---

Coding, like writing, is a means of self-expression and a process for
approaching parity.

Good code is beautiful. But not all code needs to be good.

I currently work mostly in Ruby, Python, and JavaScript / CoffeeScript;
previously in C, C++, Common Lisp, Java, SmallTalk, assembly, and Dylan; and
some smaller projects in Haskell, Objective C, and bash. For server work I've
used mostly Rails, Django, Sinatra, and Express; MySQL, Postgres, and Redis;
Apache and nginx; and AWS (and previously DreamHost, SliceHost, and colos).

- [Historical projects page](https://osteele.com/sources)
- [GitHub profile page](https://github.com/osteele)
- [GitHub repositories](https://github.com/osteele?tab=repositories)

## Recent

### Command-Line

- [gojekyll](http://github.com/osteele/gojekyll) is a Go clone of the
  [Jekyll](https://jekyllrb.com) static site generator. I wrote this in order to
  learn Go, and for a faster (20x) site development edit/view cycle.
- [forkmantle](https://github.com/osteele/forkmantle) displays GitHub forks and
  their stats (star counts and recency). I use it to identify successors to
  abandoned repos.
- [multiclone](https://github.com/osteele/multiclone) quickly clone forks of a
  GitHub repo, or copies of a GitHub Classroom assignment. Creates a
  [myrepos](https://myrepos.branchable.com/) file that can be used to perform
  bulk actions on the cloned repos, such as `git pull`ing them all.
- [git-keychain-secrets](https://github.com/osteele/git-keychain-secrets) stores
  some parts of a repo file in the macOS Keychain; keeps the rest un-encrypted.
  It's intended for use with git filters.

### Web Apps

- [Banyan](https://banyan.osteele.com) ([source](https://github.com/osteele/banyan)) visualizes Dropbox file and folder sizes.
- [Volatility](https://volatility.oh-well-thats.life/) ([source](https://github.com/osteele/volatility)) was my hello world for Elm.

### Jupyter Plugins

- [callgraph](https://github.com/osteele/callgraph) decorates Python functions
  to create dynamic call graphs.
- [ipython-secrets](https://github.com/osteele/ipython-secrets) simplifies the
  use of secrets in a Jupyter notebook.

### Jupyter Notebooks

- [Advent of Code 2017 solutions](https://github.com/osteele/notebooks/blob/master/Advent%20of%20Code%202017.ipynb)
- [Advent of Book solutions](https://github.com/osteele/notebooks/blob/master/Advent%20of%20Book%202017.ipynb)

### Python Packages

- [minimal-keys](https://github.com/osteele/minimal-keys) computes the unique
  minimal keys from a collection of strings or sequences. For example, The
  minimal keys from `["assignments/alice/hw1.txt", "assignments/bob/hw1.txt"]`
  are `["alice", "bob"]`, because the input strings share the common prefix
  `"assignments/"` and the common suffix `".txt"`.

### Classroom Tools

- [Assignment Dashboard](https://github.com/olin-computing/assignment-dashboard)
  is a web dashboard for viewing the forks of a Jupyter classroom assignment
  repo.

### Go Libraries

- [Liquid](http://github.com/osteele/liquid) is a Go clone of the Liquid
  template engine. I wrote this in order to write Gojekyll, after a couple of
  false starts with JSON-RPC and Liquid template servers.
- [Tuesday](https://github.com/osteele/tuesday) is a Go implementation of Ruby's
  `strftime`.

## Older

### Music

- [Fingerboard](http://osteele.github.io/fingerboard/) visualizes scale patterns for fretted instruments.
- [Fretboard](http://osteele.github.io/fretboard/) Interactive chord diagrams.
- The [DEC Logic Module Simulator](http://osteele.github.io/ffmachine/) simulates a _particular_ configuration of DEC Logic Modules; for purposes to be revealed.

### Grunt Plugins

- [grunt-autowatch](https://github.com/osteele/grunt-autowatch) — a Grunt task to supply default `task` and `files` to empty `watch` targets.
- [grunt-update](https://github.com/osteele/grunt-update) — a Grunt task to run only those tasks whose source files have changed
- [grunt-contextualize](https://github.com/osteele/grunt-contextualize) — a Grunt task to override configuration properties based on the current context, in order to re-use a single set of plugin targets for multiple contexts

## Misc Tools and Libraries

- [pyfsa](https://github.com/osteele/pyfsa) — Python FSA constructor, determinizer, and minimizer.
- [html2dbk](https://github.com/osteele/html2dbk) — HTML to Docbook converter — my largest XSLT project
- [dotfiles](https://github.com/osteele/dotfiles) — [Why would I want my dotfiles on GitHub?](http://dotfiles.github.io)

## Possibly Working

I haven't used these since 2008 (or earlier). Possibly they still work.

- [QtTileDual](https://github.com/osteele/QtTileDual) — Draw a graph and its duals. I wrote this to learn Qt.
- [javascript_fu](https://github.com/osteele/javascript_fu) — a Rails plugin to add more support for javascript files.
- [jcon](https://github.com/osteele/jcon) — Conformance checking of JSON values against ECMAScript 4.0 types

## Deprecated / Un-maintained

These are mostly from 2008 and earlier — before
[Underscore](http://underscorejs.org), [CoffeeScript](http://coffeescript.org),
and Babel.

### JavaScript Libraries

- [functional-javascript](https://github.com/osteele/functional-javascript) — library for functional programming in JavaScript
- [sequentially](https://github.com/osteele/sequentially) — a library of temporal and frequency adverbs for JavaScript.
- [fluently](https://github.com/osteele/fluently) — Fluent programming (chained method calls) for JavaScript
- [mop-js](https://github.com/osteele/mop-js) — JavaScript utilities for Metaobject Programming
- [collections-js](https://github.com/osteele/collections-js) Framework-independent JavaScript collection methods.
- [jquery-profile](https://github.com/osteele/jquery-profile) — Profile calls to jQuery selectors
- [protodoc](https://github.com/osteele/protodoc) —JavaScript documentation generator and pydoc equivalent.
- [jsspec](https://github.com/osteele/jsspec) — A clone of Alan Kang's [JSSpec](http://code.google.com/p/jsspec/)

### Python Modules

- [python-utils](https://github.com/osteele/python-utils) — glue for using
  Python with GraphViz, XML, and XSD. These days there's more feature-rich
  libraries for this. Also, a module import grapher.

### Ruby and Rails Gems and Plugins

- [gem_recent-updates](https://github.com/osteele/gem_recent-updates) — A gem
  command plugin that displays the tops of the history files of recently updated
  gems.
- [db_content](https://github.com/osteele/db_content) — Rails plugin to add sql
  dump and restore tasks

### JavaScript and Ruby Applications

- [storyboard](https://github.com/osteele/storyboard) — An ruby-processing
  extension for scripting storyboarded explanatory visualizations. I never
  finished this.
- [cfdg-js](https://github.com/osteele/cfdg-js) — A JavaScript implementation of
  Chris Coyne's Context Free Design Grammar.

### OpenLaszlo-related

- [openlaszlo_plugin](https://github.com/osteele/openlaszlo_plugin)
- [ropenlaszlo](https://github.com/osteele/ropenlaszlo)
- [openlaszlo-rails-example](https://github.com/osteele/openlaszlo-rails-example)
- [expialidocious](https://github.com/osteele/expialidocious) — Timeline tag
  browser for delicious, in OpenLaszlo
- [lzosutils](https://github.com/osteele/lzosutils) — OpenLaszlo utilities:
  flash bridge, ajax, etc.
- [openlaszlo-json](https://github.com/osteele/openlaszlo-json) — JSON library
  for OpenLaszlo
- [lztestkit](https://github.com/osteele/lztestkit) — BDD for OpenLaszlo.

### Other

- [cl-spec](https://github.com/osteele/cl-spec) BDD for Common Lisp
- [wideurl.com](https://github.com/osteele/wideurl.com) — joke site from a long
  time ago
