# README

    brew install chromedriver
    bundle install
    bundle exec rails db:setup db:migrate
    rails test:system

    Error:
    FooTest#test_visiting_root:
    NoMethodError: undefined method `needs_server?' for nil:NilClass
        test/system/foo_test.rb:5:in `block in <class:FooTest>'

    Error:
    FooTest#test_visiting_root:
    NoMethodError: undefined method `needs_server?' for nil:NilClass
