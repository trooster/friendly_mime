# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
require './lib/friendly_mime.rb'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "friendly_mime"
  gem.homepage = "http://github.com/lukaszsliwa/friendly_mime"
  gem.license = "MIT"
  gem.summary = %Q{Friendly::MIME gem provides possibility to show friendly description}
  gem.description = %Q{Friendly::MIME gem provides possibility to show friendly description of a document by the given MIME type.}
  gem.email = "lukasz.sliwa@apptamers.com"
  gem.authors = ["Łukasz Śliwa"]
  gem.version = Friendly::MIME::VERSION
  # dependencies defined in Gemfile
end
