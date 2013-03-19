$LOAD_PATH.unshift File.expand_path("../lib", __FILE__)
require "bundler/version"

task :default => [:build, :install]

task :build do
  system("gem build foreman-proxy-bmc.gemspec")
end

task :install do
  system("gem install *.gem")
end
