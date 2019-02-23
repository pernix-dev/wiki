# [RSpec](https://github.com/rspec/rspec-rails)

#### 1. Add the gems
Add the following gems to the `Gemfile`
```ruby
#...
group :test do
  # ...
  gem "rspec-rails"
  gem "rspec_junit_formatter"
  #...
end
#...
```

#### 2. Install the gems
```shell
$ bundle install
```


#### 3. Generate required files
```shell
$ rails g rspec:install # g is the same as 'generate'
```

#### 4. Running specs
```shell
$ rspec
```

