# Ruby Koans

Preparing myself to do some web application development on Ruby on
Rails, I realized I have to also learn a bit of Ruby. Having some
background in programming helped me quickly understand the basics and
mindset (preferred paradigm) of Ruby.

Ruby Koans is a very good guide that walks you through Ruby, and can
server as a very good starting point in learning Ruby, while
intermediate programmers can also have a deeper insight into the
language itself.

Most of the Koan tutorial is self-explanatory, with the exception that
three projects (in `*_project.rb`) require implementation of certain
object (class, or method). Well, *everything is Objects in Ruby!*. 

I recommend, in those projects, you to use `byebug` gem to debug your
script. It is very simple to use:

```Bash
# install it if you didn't have it
gem install byebug 
```

```Ruby
# at the beginning of the file
require 'byebug'

# then, to drop into the interactive Ruby irb
# insert anywhere in your code the following line
byebug
```
