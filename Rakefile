

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


    task :migrate => :environment do

          task :environment do
          require_relative './config/environment'
      Student.create_table
  end

end


  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end
