# pg - a simple cli tool for Pagure

This is a simple command line tool that I use for interacting with Pagure.

I have written it to do the things I need it to. It is currently
not really configurable. It can do simple things like:

* list projects
* show project details
* list issues
* display an issue
* list pull requests
* display a pull request
* checkout a pull request locally
* merge a pull request locally

The issue and pr subcommands attempt to auto-detect the Pagure repo from
the current checkout. Otherwise it can be specified with an option.

This is toy software and I expect to completely refactor it at some point.
