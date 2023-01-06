# frozen_string_literal: true

source "https://rubygems.org"

if !ENV["RAILS_VERSION"] || ENV["RAILS_VERSION"] == "main"
  gem "activerecord", git: "https://github.com/rails/rails", branch: "main"
else
  gem "activerecord", ENV["RAILS_VERSION"]
end

gem "trilogy", github: "https://github.com/github/trilogy/pull/15", glob: "contrib/ruby/*.gemspec"

gemspec
