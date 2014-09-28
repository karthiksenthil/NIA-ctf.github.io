# A sample Gemfile
source "https://rubygems.org"
require 'open-uri'
require 'json'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']
