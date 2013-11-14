[← Back to Index](../index.md)

# Project: Ruby Setup

Have a mentor help you with setting up your machine for Ruby. Here's what they'll guide you through:

1. **Install the latest version of Xcode**

    Xcode is downloadable from the Apple App store. Search for "xcode" and click install.

2. **Install [Ruby Version Manager (RVM)][], along with Ruby.** *"RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems."*

        \curl -L https://get.rvm.io | bash -s stable --ruby

3. **Install [Homebrew][]**

        ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

4. **Install [Bundler][]**

        gem install bundler

[Ruby Version Manager (RVM)]: https://rvm.io/
[Homebrew]: http://brew.sh/
[Bundler]:http://bundler.io/