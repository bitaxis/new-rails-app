# new-rails-app

A handy script to create new Rails application skeletons.

## Requirements

This script assumes you have the following installed already:

* RVM
* One or more Rubies
* Bundler

## Usage

Create a fork of this repository.  Then run this command to create your Rails application:

```
new-rails-app/bin/create my-great-application
```

You might want to create a symbolic link to the bin/create script, like so:

```
ln -s new-rails-app/bin/create ~/bin/new-rails-app
```

## Credits

Much thanks go out to the following:

* Wayne Seguin & Michael Papis for writing/maintaining RVM.  It rocks!
* Bahman Movaqar for his [article](http://www.bahmanm.com/blogs/command-line-options-how-to-parse-in-bash-using-getopt) on
  using Bash's getopt.

