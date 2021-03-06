Keyword:
========

    revision


Brief Description
=================

The revision of this page as reported by an underlying Version Control System.

This is a free format string.


Specification URL
=================

[github.com/krallin/meta-revision][0]


Long Description
================

The `revision` meta element may be used to indicate on your web pages the
version of the page or that of the application that generated it, as reported
by an underlying Version Control System.

Examples:

  + When using `git`, you can use the commit hash.
  + When using `svn`, you can use the revision ID
  + When using `mercurial`, you can use the changeset ID


Guidelines:

  + When serving a page generated from a Web Application (e.g. a Rails, or 
    Django application), use the revision number of your application.
  + When serving a page generated from a site generator, use the revision
    number of your project

Do not use the revision number of:

  + Your web framework
  + Your site generator


Examples
========

  + [http://dev.w3.org/html5/webvtt/][1]
  + Please submit a pull request to list your site here!


  [0]: https://github.com/krallin/meta-revision
  [1]: http://dev.w3.org/html5/webvtt/
