# README

This README would normally document whatever steps are necessary to get the
application up and running.

1. Change directory to Desktop and git clone

2. Installing Rails. On macOS open Terminal.app, use the gem install command provided by RubyGems:

            $ gem install rails

3. Type in command:

            $ bundle install
            
4. Next, you need to migrate rails by typing this command :
            
            $ bin/rails db:migate RAILS_ENV=development 
            
5. Next, you can populate data using seed.rb by typing this command:

            $ rails db:seed
            
By default, seed.rb only generates 10 stores. You can change this number by edit the number in ~/Webapp/db/seeds.rb
            NUMBER_OF. times do

6. Finally, you can now fire up the server on your local host (http://localhost:3000)

            $ bin/rails server 
    
    
# Webapp
