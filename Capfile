require "capistrano/setup"

require "capistrano/deploy"

require "capistrano/bundler"
require "capistrano/rvm"
require "capistrano/rails/assets"
require "capistrano/rails/migrations"
require "capistrano/puma"

require "capistrano/scm/git"
install_plugin Capistrano::SCM::Git

Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }