# Install

    $ sudo yum install libxslt-dev libxml2-dev libsqlite3-dev #CentOS
    $ sudo yum install nodejs npm --enablerepo=epel
    $ bundle install
    $ bundle exec rake db:create
    $ bundle exec rake db:migrate

# Commands

    $ bundle exec guard

    $ bundle exec spork

    $ bundle exec rails s

# Add Engine

    $ rails plugin new my_engine --mountable
    $ cd my_engine
    $ vi my_engine.gemspec
    $ bundle install
    $ rails g rspec:install
    $ rake spec