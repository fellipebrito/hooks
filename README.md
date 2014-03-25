Hooks
=====

Validates your code before push

  - Analyse your code based on the community Ruby style guide using [rubocop]
  - Run [RSpec] to make sure your test suite approves your code
  - Sum the code coverage merging across test suites using [simplecov]

Requirements
---

In order to use git push hooks you need to update your git to 1.8+, if you don't know how to that, here is a [git update guide].

Installation
----

It comes with a rake task that create alias files in the correct places. In order to install it please make sure you add this files inside **vendor/hooks**, then from this folder run *rake install*

[RSpec]:http://rspec.info/
[rubocop]:https://github.com/colszowka/simplecov
[simplecov]:https://github.com/bbatsov/rubocop
[git update guide]:https://www.digitalocean.com/community/articles/how-to-install-git-on-ubuntu-12-04
