# new-rails-app

A handy script to create new Rails application skeletons.

## Requirements

This script assumes you have the following installed:

* [getopt(1)](http://frodo.looijaard.name/project/getopt) 1.1.6 or greater
* [RVM](http://rvm.io) for Ruby and gemset management
* One or more Rubies

## Usage

Fork or clone this repository.  Then run this command to create your Rails application:

```
$ new-rails-app/bin/create my-great-application
```

You might want to create a symbolic link to the bin/create script, like so:

```
$ ln -s new-rails-app/bin/create ~/bin/new-rails-app
```

### Getopt(1)

This script uses getopt(1), which is superior to getopt(3) in its ability to handle long parameters and more.
If you are on Mac OS X El Capitan and are unable to install getopt(1), try using the embedded binary, like so:

```
$ export GETOPT1=/path-to-new-rails-app/bin/getopt
$ /path-to-new-rails-app/bin/create ...
```

Of course, you're welcome to find alternate copies of getopt(1) and supply the path to it.

## Credits

Much thanks go out to the following folks:

* Wayne Seguin & Michael Papis for writing/maintaining [RVM](http://rvm.io).  It rocks!
* Bahman Movaqar for his [article](http://www.bahmanm.com/blogs/command-line-options-how-to-parse-in-bash-using-getopt) on
  using Bash's getopt.

