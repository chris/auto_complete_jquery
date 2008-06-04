require 'rake' 
require 'rake/rdoctask' 
   
desc 'Generate documentation for auto_complete plugin.' 
Rake::RDocTask.new(:rdoc) do |rdoc| 
  rdoc.rdoc_dir = 'rdoc' 
  rdoc.title    = 'Auto Complete jQuery' 
  rdoc.options << '--line-numbers' << '--inline-source' 
  rdoc.rdoc_files.include('README') 
  rdoc.rdoc_files.include('lib/**/*.rb') 
end
