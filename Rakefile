# encoding: utf-8

require 'rubygems'
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "rails-console-pry"
  gem.homepage = "http://github.com/doitian/rails-console-pry"
  gem.license = "MIT"
  gem.summary = %Q{inject pry into rails console}
  gem.description = %Q{run rails console using rails without adding it to Gemfile}
  gem.email = "me@iany.me"
  gem.authors = ["Ian Yang"]
  gem.add_runtime_dependency "pry", ">= 0"
  gem.add_runtime_dependency "pry-rails", ">= 0"
  gem.executables = ['rails-console-pry']
end
Jeweler::RubygemsDotOrgTasks.new

task :default => 'gemspec'
