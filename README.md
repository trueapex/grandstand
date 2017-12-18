# Grandstand
A Drupal 8 eCommerce theme.

## Tools
* RVM (https://rvm.io/)
* Ruby https://www.ruby-lang.org/en/

## Setup
### Install RVM
Follow instructions at https://rvm.io/rvm/install for installing RVM.

### Install Ruby
List Ruby versions already installed in your system.
```
$ rvm list
```

List known Ruby versions
```
$ rvm list known
```

Install latest ruby version or a specific version
```
$ rvm install 2.4.3
```

### Setup Gemset
Go to your theme directory.
```
$ cd /path/to/[your-theme]
```

Set the name of your Gemset (i.e. grandstand).
```
$ vim .ruby-gemset
```

Set the Ruby version your going to use (i.e. 2.4.3).
```
$ vim .ruby-version
```

Move up one level from your current directory then back again. This will automatically set the Gemset.
```
$ cd ..
$ cd [your-theme]
```

### Install Gems
Install Bundler
```
$ gem install bundler
```

Install Gems
```
$ bundle install
```

## Developing
Compiling SCSS.
```
$ compass compile
```

Or, what SCSS.
```
$ compass watch
```

## Contributors
* Romualdo Dasig (https://github.com/dasigr)
