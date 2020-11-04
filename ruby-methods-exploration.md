# Explore Ruby's Methods

###  Objectives

- Use the ruby docs to find methods
- Use and explain ruby methods



This morning you will explore all the following methods. Your job is to look in the Ruby documentation to read about the method, come up with an explanation of what it is, and show an example of it in use.

The entire breakout room will submit a single version of the documentation and examples.  

#### Getting Started

- One person in the breakout room is to fork and clone this repo
- Every other person will fork and clone that repo
- Every person must make commits and request a pull request (except for the owner of the repo)
- The owner will approve the pull requests
- Every person will then pull the changes so they are up to date


#### Deliverables

- A single pull request from the group with the documentation for each method and a working example(s)

[String](http://ruby-doc.org/core-2.3.0/String.html)

- `rstrip` /`rstrip!`
- `reverse` /`reverse!`
- `gsub` / `gsub!`
- `capitalize` `capitalize!` / `upcase` / `upcase!`
- `downcase`/ `downcase!` / `swapcase` / `swapcase!`
- `chomp` / `chomp!`
- `to_f` / `to_i`
- `to_str`/ `to_sym` / `to_a`

Example string: `"we researched ruby methods"`

[Array](http://ruby-doc.org/core-2.3.0/Array.html)

- `compact` / `compact!`
- `delete_at` /`delete_if`
- `fetch`
- `flatten` / `flatten!`
- `sample`
- `zip`
- `<<`
- `first` / `last`
- `step` (note, you'll be doing the `.step` on a range of numbers, but it can then be used with an array)
- `join`
- `reduce`

Example array:

```ruby
students = ["An", "Todd", "Mark", "Jim", "Cathleen", "Ky", "Biren", "Geraldine", "Hanna", "Dylan", "Sheila", "Charles", "Soniya", "Jerrica", "Ellen", "Lenin", "Adam", "Stanley", "Matthew", "Anthony", "Joe", "Emily", "Amanda"]
```

[Hash](http://ruby-doc.org/core-2.3.0/Hash.html)

-  `has_key?`
-  `keys`
-  `merge` / `merge!`
-  `flatten`
-  `invert`

Example hash:

```ruby
cohort = {name: "Hopper", instructors: 4, "never_gonna_give_you_up" => "favorite song", most_played_song: "Freebird", instructors: ["Matt", "Thom", "Karolin", "Kristyn"], 100 => 200}
```

[Integer](http://ruby-doc.org/core-2.3.0/Integer.html)

-  `odd?` / `even?`
-  `floor` / `next`
-  `times`

Example integers:

```ruby
1
28
12_345_678
```

[Method](http://www.skorks.com/2009/08/method-arguments-in-ruby/)

- Default values in parameters

### Enumerables

[The Enumerable module provides a set of methods to traverse, search, sort and manipulate collections](http://ruby.bastardsbook.com/chapters/enumerables/)

- for in
- each do
- each with index
- map
- `select` / `select!`
