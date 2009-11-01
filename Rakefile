require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "cpsn"
    gem.summary = %Q{Query PSN friend status from the CLI}
    gem.description = %Q{Query PSN friend status from the CLI}
    gem.email = "jbowes@repl.ca"
    gem.homepage = "http://github.com/jbowes/cpsn"
    gem.authors = ["James Bowes"]
    gem.add_dependency "mechanize"
    gem.add_dependency "hpricot"
    gem.add_dependency "json"
    # there's nothing in lib, so ignore it to quelch warnings during install
    gem.require_paths = ["bin"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

task :default => nil
