desc 'grab the version'
task :version do
  version = File.read('metadata.rb')[/^version\s*'(\d.\d.\d)'/,1]
  print version
end
