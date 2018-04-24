# .gitignore

## What is it?
The .gitignore file is used to ignore files that we never want to save onto our remote repo.

## Examples
1. Let's say your working in C and you create object files that you don't want to save the object files, since they are not useful to other machines. You would put `*.o` in your .gitignore file.
2. If you are working in a Mac, everytime you enter a directory Finder will create a `.DS_Store` file. I personally don't want that in my git repo, so I add `.DS_Store` to my .gitignore file.

## Templates
There is a great [repo](https://github.com/github/gitignore) on github that has .gitignore files for whatever your working on.
