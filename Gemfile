source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll'
gem 'jekyll-assets'
gem 'rake'
gem 'github-pages', versions['github-pages']
gem 'sass'
gem 'uglifier'
