# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

group :development do
  gem 'rake'
  gem 'sass'
  gem 'jekyll'
end

source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'jekyll-paginate'
