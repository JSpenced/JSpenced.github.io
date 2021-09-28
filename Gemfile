source "https://rubygems.org"

# Theme
gem "jekyll-remote-theme"
gem "minimal-mistakes-jekyll"
gem "jekyll-include-cache"
gem "jekyll-paginate"
gem "nokogiri", "~> 1.12.5"

# github-pages plugins
gem "github-pages", group: :jekyll_plugins

# other plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
