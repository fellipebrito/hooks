Hooks
=====

Validates your code before push

  - Analyse your code based on the community Ruby style guide using [rubocop]
  - Run [RSpec] to make sure your test suite approves your code
  - Sum the code coverage merging across test suites using [simplecov]

Installation
----

It comes with a rake task that create alias files in the correct places. In order to install it please make sure you add this files inside **vendor/hook**, then from this folder run *rake install*

[RSpec]:http://rspec.info/
[rubocop]:https://github.com/colszowka/simplecov
[simplecov]:https://github.com/bbatsov/rubocop
