# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "webrick"

#gem "jekyll", "~> 3.9.0"

#gem "minima", "~> 2.5"

#gem "github-pages", "~> 214", group: :jekyll_plugins

group :test do
  gem "html-proofer", "~> 3.18"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
#gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64-linux, :mswin]
