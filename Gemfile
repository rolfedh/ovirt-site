source "https://rubygems.org"
ruby RUBY_VERSION

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "jekyll"
# Jekyll missing dependency:
# LoadError: cannot load such file -- json
#  /srv/builder/.gem/ruby/2.4.0/gems/jekyll-3.6.0/lib/jekyll/filters.rb:4:in `require'
gem "json"

group :jekyll_plugins do
  gem "jekyll-sass-converter"
  gem "kramdown"
  gem "liquid"
  gem "jemoji"
  gem "jekyll-redirect-from"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-coffeescript"
  gem "jekyll-seo-tag"
  gem 'jekyll-haml', :git => 'https://github.com/OSAS/jekyll-haml.git', :branch => 'haml_jekyll_context'
  gem "listen"
  gem "bootstrap-sass"
end

# The CoffeeScript gem depends on execjs which requires a JavaScript runtime.
# This does the trick without nodejs.
gem "therubyracer"

# for events
gem 'icalendar', '~> 1.5'
gem 'chronic'

# for dot access to Hash members in HAML pages
gem 'hash_dot', '~> 2.4.2'

