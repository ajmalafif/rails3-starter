## Rails 3.2 `development` useful gems
[sextant](https://github.com/schneems/sextant)
[Rails ERD](http://rails-erd.rubyforge.org/install.html)
[Better Errors](https://github.com/charliesome/better_errors)
[action_cost](https://github.com/plerohellec/action_cost)

## Dev tools for Rails
[rails_panel](https://github.com/dejan/rails_panel)
[Pow.cx](http://pow.cx/)

### All-in-one

```ruby
group :development do
  gem 'sextant'
  gem "rails-erd"
  gem "better_errors"
  gem 'meta_request'
end
```

### Sextant

```ruby
group :development do
  gem 'sextant'
end
```

### Rails ERD

```ruby
group :development do
  gem "rails-erd"
end
```

### Better Errors

```ruby
group :development do
  gem "better_errors"
end
```

### Rails Panel

```ruby
group :development do
  gem 'meta_request'
end
```

Then run `bundle install`.