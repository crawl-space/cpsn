require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "cpsn"
    gem.summary = %Q{Query PSN friend status from the CLI}
    gem.description = %Q{
        Query PSN friend status from the CLI. Shows useful information like the
        game being played, and what mode or map your friend is playing
        (if available).
    }
    gem.email = "jbowes@repl.ca"
    gem.homepage = "http://github.com/jbowes/cpsn"
    gem.authors = ["James Bowes"]
    gem.add_dependency "mechanize", ">= 0.9.3"
    gem.add_dependency "json", ">= 1.1.7"
    gem.add_dependency "highline"
    # there's nothing in lib, so ignore it to quelch warnings during install
    gem.require_paths = ["bin"]
    gem.extra_rdoc_files = ""
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

task :default => :build
