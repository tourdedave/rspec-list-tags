# RSpec List Tags

A demonstration of how to list the tags used in your RSpec tests.

## Usage Examples

```sh
tag_lister.rb
```

```sh
tag_lister.rb 'alphabetical'
```

```sh
tag_lister.rb 'usage'
```

It defaults to sorting by usage.

## Example Report

```sh
......

***************
* TAGS IN USE *
***************

wip:true (used 2 times)
  One passes (./spec/one_spec.rb:2)
  One fails (./spec/one_spec.rb:3)
smoke:true (used 2 times)
  Three passes (./spec/three_spec.rb:2)
  Three fails (./spec/three_spec.rb:3)
story:BIZ-1234 (used 1 times)
  Two passes (./spec/two_spec.rb:2)
story:BIZ-1235 (used 1 times)
  Two fails (./spec/two_spec.rb:3)

4 tags in use: sorted in usage order


Finished in 0.00106 seconds (files took 0.09029 seconds to load)
6 examples, 0 failures
```
