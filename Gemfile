source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima"
gem "jekyll-theme-chirpy"
# To upgrade, run `bundle update github-pages`.
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-avatar"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-octicons"
  gem "jekyll-github-metadata"
  gem "jekyll-seo-tag"
end

gem "kramdown-math-katex"
gem "faraday", "< 1.0"
gem "minitest", "~> 5.14"
gem "webrick", "~> 1.7"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
