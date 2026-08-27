source "https://rubygems.org"

# NOTE: this Gemfile is for local preview (bundle exec jekyll serve) only.
# GitHub Pages' "Deploy from a branch" build does not read this file --
# it always builds with its own fixed server-side Jekyll environment.
# We use a modern Jekyll here (instead of the github-pages gem) because
# the github-pages gem pins an old Jekyll/Liquid that calls Ruby's
# tainted? method, which was removed in Ruby 3.2+.
gem "jekyll", "~> 4.3"
gem "jekyll-remote-theme"
gem "jekyll-include-cache"
gem "jekyll-feed"
gem "jekyll-paginate"
gem "jekyll-sitemap"

# Ruby 3.4 removed these from the default bundled gems, but Jekyll/its
# dependencies still need them.
gem "csv"
gem "webrick"
gem "bigdecimal"
gem "base64"
gem "logger"
