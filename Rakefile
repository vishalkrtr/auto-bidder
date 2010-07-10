require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "auto-bidder"
    gem.summary = "gem for automatically placing bids on auction sites"
    gem.description = "gem for automatically placing bids on auction sites"
    gem.email = "hoverlover@gmail.com"
    gem.homepage = "http://github.com/hoverlover/auto-bidder"
    gem.authors = ["Chad Boyd"]
    gem.files = FileList['lib/**/*.rb', 'bin/*']
    gem.add_dependency('safariwatir', '>= 0.3.7')
    gem.executables << "auto-bidder"
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end