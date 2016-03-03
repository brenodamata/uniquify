require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('uniquify', '0.1.1') do |p|
	p.description 	 = "Generate unique token with ActiveRecord."
	p.url 					 = "http://github.com/brenodamata/uniquify"
	p.author 				 = "Breno da Mata"
	p.email 				 = "bjrdamata@gmail.com"
	p.ignore_pattern = ["tmp/*", "script/*"]
	p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }