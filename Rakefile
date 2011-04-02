# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.
require 'rake'

namespace :bushido do
  desc "Prepare an app to run on the Bushido hosting platform, only called during the initial installation. Called just before booting the app."
  task :install do
    `ruby indexer.rb`
  end

  desc "Prepare an app to run on the Bushido hosting platform, called on every update. Called just before booting the app."
  task :update do
    `ruby indexer.rb`
  end
end
  
