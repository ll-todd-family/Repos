source "https://rubygems.org"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-git_metadata"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-mentions"
  gem "github-pages"
end
