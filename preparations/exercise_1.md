```ruby

$ mkdir my_folder
$ cd my_folder
my_folder $ touch one.rb two.rb
subl one.rb # Opening the file with the Sublimetext editor. Sublime text editor window pops up and inside the Sublimetext editor we write:
puts "this is file one"
# Hit Ctrl+s to save changes to the one.rb file
# Exit the one.rb file 
subl two.rb # Opening the two.rb file. Sublime text editor window pops up and inside the Sublimetext editor we write:
puts "this is file two"
# Hit Ctrl+s to save changes to the two.rb file. Exit the two.rb file. From inside the my_folder directory in the command line: 
my_folder $ ruby one.rb # Runs the one.rb file
this is file one # This gets output in the command line.
my_folder $ ruby two.rb # Runs the two.rb file
this is file two # This gets output in the command line.

```
