require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('wine_com', '0.1.0') do |p|
  p.description    = "Provides an interface to the wine.com API."
  p.url            = "https://github.com/geeosh/wine_com"
  p.author         = "Christopher Meiklejohn"
  p.email          = "cmeik@me.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }

