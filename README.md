# rails-todos-api #

### RESTful JSON API With Ruby on Rails 5 ###

#### Application Requires/Configuration:
* Ruby 2.4.1
* Rails 5.1.4
* Web server for development/production: puma
* Database: sqlite3
* Authorization: jwt

#### Setup & Run:
* Update to latest rails `$ gem update rails`
* Install the gems `$ bundle install`
* `$ gem install`
* `$ gem update`
* `$ rake db:migrate`
or * `$ bin/rails db:migrate RAILS_ENV=development`
* `$ rake db:seed`
* `$ rails db:test:prepares`
* `$ bundle exec rspec`
* `$ bundle exec rspec spec/auth -fd`
* View routes `$ rails routes`
* Run server `$ rails s`

#### Test:
# GET /todos
* http://localhost:3000/todos

# POST /todos
* http://localhost:3000/todos?title=TestTitle1&created_by=1

# PUT /todos/:id
* http://localhost:3000/todos/?title=ItemsTest1
* http://localhost:3000/todos/1?title=TestTitle2

# DELETE /todos/:id
* http://localhost:3000/todos/1

# Authentication/Login/Signup
* http://localhost:3000/signup?email=admin&password=password123&name=admin&password_confirmation=password123
* http://localhost:3000/auth/login?email=admin&password=password123

# POST /todos/items
* http://localhost:3000/todos/1/items?name=ItemsTest1
* http://localhost:3000/todos/1/items/1?done=false

# API version
* Accept - application/vnd.todos.v1+json
* Accept - application/vnd.todos.v2+json

#### Resources:
* https://github.com/RailsApps/
* http://rubyonrails.org/
* https://www.railstutorial.org/book
* https://jwt.io/
* https://scotch.io/