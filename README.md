# Ruby On Rails Application

## Description

This is an example of creating ruby on rails application.

### Development Setup

In the terminal, run: <br>
`rails s`
<br>

### Test Setup

https://github.com/rspec/rspec-rails <br>
https://github.com/thoughtbot/factory_bot_rails

`rails generate rspec:install `

Removing default fixtures from Adding this to spec/rails_helper.rb <br>
` config.fixture_path = "#{::Rails.root}/spec/fixtures"`

Adding this to spec/rails_helper.rb <br>
` config.include FactoryBot::Syntax::Methods`

Run Test <br>
In the terminal, run: <br>
`rspec`
