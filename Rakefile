#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

require 'rake/dsl_definition'
require 'rake/alt_system'
require 'rake'

Myapp::Application.load_tasks

module ::Myapp
  class Application
    include Rake::DSL
    include Rake::AltSystem
  end
end

