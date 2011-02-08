require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('jutil', '0.0.1') do |p|
  p.description    = "A gem that illustrates how to build a gem"
  p.url            = "http://github.com/jesserod/jutil"
  p.author         = "Jesse Rodriguez"
  p.email          = "jutil@kilobase.net"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }  
