# rails-todos-api #

### RESTful JSON API With Ruby on Rails 5 ###

* Update to latest rails `$ gem update rails`

* Install the gems `$ bundle install`

* DB migration `$ rails db:migrate`

* Run spec tests `$ bundle exec rspec`

* View the routes `$ rails routes`

* Run server `$ rails s`

### Test ###
# GET /todos
* http://localhost:3000/todos

# POST /todos
* http://localhost:3000/todos title=TestTitle1 created_by=1

# PUT /todos/:id
* http://localhost:3000/todos/1 title=TestTitle2

# DELETE /todos/:id
* http://localhost:3000/todos/1

# Authentication/Login
* http://localhost:3000/auth/login email=admin password=password123

# POST /todos/items
* http://localhost:3000/todos/1/items?name=ItemsTest1
* http://localhost:3000/todos/1/items/1?done=false

# API version
* Accept - application/vnd.todos.v1+json
* Accept - application/vnd.todos.v2+json
