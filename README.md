# Logtail Ruby

Collect logs directly from Ruby on Rails, Sinatra, and plain Ruby projects.
**Supported language versions:**
Ruby 2.7.0 or newer

You can learn more about using Logtail in Ruby projects in our [official docs](https://logtail-main.readme.io/docs/installing-logtail-2).

# Installation and setup

You can install Logtail to your Ruby projects using the Ruby Bundler.

### Ruby Bundler

If you have Ruby bundler already installed you can skip this step. Run the following command to install the ruby bundler:

```bash
sudo apt install ruby-bundler
```

## Ruby

To install Logtail to your Ruby project, run the following command:

```bash
bundle add logtail
```

This will install Logtail gem and create `Gemfile` and `Gemfile.lock` that are used to track the code dependencies.

Alternatively, add `gem "logtail"` to your `Gemfile` manually and then run `bundle install`.


# Example project

To help you get started and integrate Logtail in your Ruby projects, we have prepared an example Ruby project. 

## How to run the example project

First, download or clone the repository into the select directory. Make sure you are in the projects directory and run the following command:

```bash
bundle install
```

This will install all dependencies listed in the `Gemfile.lock` file.

Then run the example project by executing the following command:

```bash
ruby main.rb <source-token>
```

Don’t forget to replace the <source-token> with your actual source token.

You should see the following output:

```
Output:
All done! You can check your logs now.
```

This will create a total of 5 different logs, each corresponding to a different log level. You can review these logs in Logtail.
