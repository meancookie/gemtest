require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('test', '0.1.0') do |p|
  p.description    = "This is a test gem"
  p.url            = "https://github.com/meancookie/gemtest"
  p.author         = "Charles Zhuang"
  p.email          = "mail.charles.zhuang@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }