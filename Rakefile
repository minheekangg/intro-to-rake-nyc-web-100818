task :environment do
require_relative './config/environment'
end

namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  task :hola do
    puts "hola de Rake!"
  end
end

namespace :db do

  task :migrate do
    task :migrate => :environment do
    Student.create_table
  end
end

  # task :seed do
  #
  # end
end
