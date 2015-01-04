Options:
  
  -m, [--template=TEMPLATE]                              # Path to some application template (can be a filesystem path or URL)
      [--skip-gemfile], [--no-skip-gemfile]              # Don't create a Gemfile
  -B, [--skip-bundle], [--no-skip-bundle]                # Don't run bundle install
  
  -J, [--skip-javascript], [--no-skip-javascript]        # Skip JavaScript files
      [--dev], [--no-dev]                                # Setup the application with Gemfile pointing to your Rails checkout
      [--edge], [--no-edge]                              # Setup the application with Gemfile pointing to Rails repository
  -T, [--skip-test-unit], [--no-skip-test-unit]          # Skip Test::Unit files
      [--rc=RC]                                          # Path to file containing extra configuration options for rails command
      [--no-rc], [--no-no-rc]                            # Skip loading of extra configuration options from .railsrc file

Noelles-MacBook-Air:code nprustad$ rails new new_options -T, -B, -m, -J
      create  
      create  README.rdoc
      create  Rakefile
      create  config.ru
      create  .gitignore
      create  Gemfile
      create  app
      create  app/assets/javascripts/application.js
      create  app/assets/stylesheets/application.css
      create  app/controllers/application_controller.rb
      create  app/helpers/application_helper.rb
      create  app/views/layouts/application.html.erb
      create  app/assets/images/.keep
      create  app/mailers/.keep
      create  app/models/.keep
      create  app/controllers/concerns/.keep
      create  app/models/concerns/.keep
      create  bin
      create  bin/bundle
      create  bin/rails
      create  bin/rake
      create  config
      create  config/routes.rb
      create  config/application.rb
      create  config/environment.rb
      create  config/secrets.yml
      create  config/environments
      create  config/environments/development.rb
      create  config/environments/production.rb
      create  config/environments/test.rb
      create  config/initializers
      create  config/initializers/assets.rb
      create  config/initializers/backtrace_silencers.rb
      create  config/initializers/cookies_serializer.rb
      create  config/initializers/filter_parameter_logging.rb
      create  config/initializers/inflections.rb
      create  config/initializers/mime_types.rb
      create  config/initializers/session_store.rb
      create  config/initializers/wrap_parameters.rb
      create  config/locales
      create  config/locales/en.yml
      create  config/boot.rb
      create  config/database.yml
      create  db
      create  db/seeds.rb
      create  lib
      create  lib/tasks
      create  lib/tasks/.keep
      create  lib/assets
      create  lib/assets/.keep
      create  log
      create  log/.keep
      create  public
      create  public/404.html
      create  public/422.html
      create  public/500.html
      create  public/favicon.ico
      create  public/robots.txt
      create  test/fixtures
      create  test/fixtures/.keep
      create  test/controllers
      create  test/controllers/.keep
      create  test/mailers
      create  test/mailers/.keep
      create  test/models
      create  test/models/.keep
      create  test/helpers
      create  test/helpers/.keep
      create  test/integration
      create  test/integration/.keep
      create  test/test_helper.rb
      create  tmp/cache
      create  tmp/cache/assets
      create  vendor/assets/stylesheets
      create  vendor/assets/stylesheets/.keep
      remove  app/assets/javascripts
         run  bundle install
Fetching gem metadata from https://rubygems.org/..........
Resolving dependencies...
Using rake 10.4.2
Using i18n 0.7.0
Using json 1.8.1
Using minitest 5.5.0
Using thread_safe 0.3.4
Using tzinfo 1.2.2
Using activesupport 4.1.6
Using builder 3.2.2
Using erubis 2.7.0
Using actionview 4.1.6
Using rack 1.5.2
Using rack-test 0.6.2
Using actionpack 4.1.6
Using mime-types 2.4.3
Using mail 2.6.3
Using actionmailer 4.1.6
Using activemodel 4.1.6
Using arel 5.0.1.20140414130214
Using activerecord 4.1.6
Using bundler 1.7.3
Using execjs 2.2.2
Using hike 1.2.3
Using multi_json 1.10.1
Using jbuilder 2.2.6
Using thor 0.19.1
Using railties 4.1.6
Using tilt 1.4.1
Using sprockets 2.12.3
Using sprockets-rails 2.2.2
Using rails 4.1.6
Using rdoc 4.2.0
Using sass 3.2.19
Using sass-rails 4.0.5
Using sdoc 0.4.1
Using spring 1.2.0
Using sqlite3 1.3.10
Using uglifier 2.6.0
Your bundle is complete!
Use `bundle show [gemname]` to see where a bundled gem is installed.
         run  bundle exec spring binstub --all
* bin/rake: spring inserted
* bin/rails: spring inserted

Noelles-MacBook-Air:code nprustad$ cd new_options
Noelles-MacBook-Air:new_options nprustad$ mv README.rdoc README.md







== README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.
