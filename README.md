# Selena Larson Personal Website

This site uses [jekyll](http://jekyllrb.com)

## Setup

* Make sure jekyll is installed - `sudo gem install jekyll`
* Make a new site - `jekyll new mynewsite`
* Get bundler - `gem install bundler`
* Make Gemfile with - `gem 'github-pages'`
* Bundle the gems in the Gemfile - `bundle --path vendor`

## Running Locally

In terminal, type "cd" and a space. Then drag the website folder to Terminal.

Start guard `bundle exec guard`

Start jekyll `jekyll serve --watch`

Visit http://0.0.0.0:4000

## Using Git

1. Check status `git status`

2. Staging files to commit `git add my_awesome_file.poop`

3. Committing files `git commit -m "My commit message"`

4. Push your changes to remote repository `git push`

5. Make money

## notes

- can't run both at the same time so use the port option `jekyll serve --watch -P 4001`