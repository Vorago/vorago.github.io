source 'https://rubygems.org'

# This will ensure that when you run bundle install,
# you have the correct version of the github-pages gem.
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
