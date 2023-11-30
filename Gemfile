source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "github-pages", "~> 228", group: :jekyll_plugins
gem "jekyll", '~> 3.9.3'

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"
gem "faraday-retry"
gem 'webrick', '~> 1.8.1'

# Plugins recommended by GitHub Pages
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15.1"
  gem "jekyll-avatar", '0.7.0'
  gem "jekyll-coffeescript", '1.1.1'
  gem "jekyll-commonmark-ghpages", '0.4.0'
  gem "jekyll-default-layout", '0.1.4'
  gem "jekyll-gist", '1.5.0'
  gem "jekyll-github-metadata", '2.13.0'
  gem "jekyll-include-cache", '0.2.1'
  gem "jekyll-mentions", '1.6.0'
  gem "jekyll-optional-front-matter", '0.3.2'
  gem "jekyll-paginate", '1.1.0'
  gem "jekyll-readme-index", '0.3.0'
  gem "jekyll-redirect-from", '0.16.0'
  gem "jekyll-relative-links", '0.6.1'
  gem "jekyll-remote-theme", '0.4.3'
  gem "jekyll-sass-converter", '1.5.2'
  gem "jekyll-seo-tag", '2.8.0'
  gem "jekyll-sitemap", '1.4.0'
  gem "jekyll-titles-from-headings", '0.5.3'
  gem "jemoji", '0.12.0'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

