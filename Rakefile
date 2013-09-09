require "rubygems"
require "bundler/gem_tasks"

desc "Generate etc.rb"
task :default do
  Dir.chdir File.expand_path("../lib/rubysl/etc", __FILE__) do
    exec Gem.ruby, "extconf.rb"
  end
end
