source 'https://rubygems.org'
gem 'rails', git: 'https://github.com/rails/rails', branch: '4-2-stable'
gem 'pg'
gem 'activerecord-native_db_types_override' 
group :development do
  gem 'web-console'
  gem 'spring'
  gem "better_errors"
  gem "binding_of_caller"
  gem 'meta_request'
  gem 'quiet_assets'
  gem 'rails-erd'
  gem 'rubocop', require: false
end
group :test do
  gem 'sqlite3'
  gem 'factory_girl_rails', require: false
  gem 'simplecov', :require => false
  gem "brakeman", :require => false
  gem 'webmock', '~> 2.1'
  gem 'maxitest'
end
group :test, :development do
  gem 'awesome_print'
  gem 'minitest-spec-rails'
  gem 'minitest-reporters'
  gem 'minitest-given'
  gem 'mimic', '~> 0.4.3'
  gem 'fakes3'
  gem 'lolcat'
end
group :qualif, :production do
  gem 'puma', '~> 3.6.0'
  gem 'puma_worker_killer'
end
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end
gem 'responders'
gem 'sprockets'
gem 'activeresource'
gem 'therubyracer', '~> 0.12', require: 'v8', platforms: :ruby
gem 'rack-mini-profiler'
gem 'select2-rails', '~> 3.5.0'
gem 'jquery-rails'
gem "jquery-migrate-rails"
gem 'jquery-ui-rails'
gem 'jquery-ui-themes'
gem "touchpunch-rails", git: 'https://github.com/geothird/touchpunch-rails', ref: '8d5325d'
gem 'jquery-easing-rails'
gem 'uri-js-rails'
gem 'flot-rails'
gem 'turbolinks', '~> 2.5.3'
gem 'devise'
gem 'devise-i18n'
gem 'cancancan'
gem 'simple_roles'
gem 'rails-i18n'
gem 'simple_form', git: 'https://github.com/plataformatec/simple_form'
gem 'country_select', '~> 1.2.0'
gem 'paperclip'
gem 'aws-sdk-rails'
gem 'aws-sdk', '2.7.6' 
gem 'nested_form'
gem 'will_paginate'
gem 'elasticsearch-model'
gem 'elasticsearch-rails'
gem "elasticsearch-persistence", require: 'elasticsearch/persistence/model'
gem "geocoder"
gem 'c_geohash', require: 'geohash'
gem 'wicked'
gem 'comma'
gem 'murmurhash3'
gem 'curb'
gem 'rest-client'
gem 'prawn'
gem 'prawn-table'
gem 'prawnto'
gem 'cassandra-driver'
gem 'logstasher'
gem 'whenever', require: false
gem 'eu_central_bank', "~> 0.5.0"
gem "migration_comments"
gem "paper_trail"
gem "macaddr"
gem "uuid"
gem "public_suffix"
gem 'ruby-druid', git: 'https://github.com/teacups/ruby-druid', branch: 'search_query', require: 'druid', platforms: :ruby
gem 'chrono_model', git: 'https://github.com/ifad/chronomodel', ref: '5f9e88c'
gem "setler", git: 'https://github.com/teacups/setler', branch: "rails4"
gem 'license_finder', platforms: :ruby
gem 'enumerize'
gem 'sidekiq'
gem "sinatra", require: false
gem 'sidekiq-status'
gem "sidekiq-cron"
gem 'redis-rails' 
gem 'selectize-rails'
gem 'masonry-rails'
gem 'hashids'
gem 'posix-spawn'
gem 'jquery_file_download-rails'
gem 'integer-obfuscator'
gem "rxjs-rails"
gem 'axlsx', '~> 2.1.0.pre'
gem 'acts_as_xlsx', git: 'https://github.com/teacups/acts_as_xlsx', branch: :handle_chained_method_call_in_column_returns_nil
gem 'axlsx_rails'
gem 'charlock_holmes'
gem 'roo'
gem 'roo-xls'
gem 'deeplink'
gem "jwt"
gem 'listen'
gem 'statistics2'
gem 'google-api-client', '~> 0.9'
gem 'paypal-sdk-rest'
gem 'paypal-sdk-buttonmanager'
gem 'grape'
gem 'grape-swagger'
gem 'grape-swagger-rails'
gem 'grape-swagger-entity'
gem 'grape-swagger-representable'
gem 'grape-entity'
gem 'grape-cancan'
gem 'grape-active_model_serializers'
gem 'grape-kaminari'
gem 'kaminari', '1.0.0'
gem 'kaminari-sinatra'
gem 'kaminari-grape'
gem 'knock'
gem 'hashie-forbidden_attributes' 
gem 'hashie', '~> 3.4.6'
gem 'activesupport-json_encoder'
source 'https://rails-assets.org' do
  gem 'rails-assets-jquery', '~> 2.2.4'
  gem 'rails-assets-datatables'
  gem 'rails-assets-datatables-responsive'
  gem 'rails-assets-datatables-fixedheader'
  gem 'rails-assets-datatables-buttons'
  gem 'rails-assets-datatables-scroller'
  gem 'rails-assets-jquery.floatThead'
  gem 'rails-assets-growl'
end
local_gemfile = File.dirname(__FILE__) + "/Gemfile.local.rb"
if File.file?(local_gemfile)
  self.instance_eval(Bundler.read_file(local_gemfile))
end
