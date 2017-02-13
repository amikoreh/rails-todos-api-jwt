# rails-todos-api #

### RESTful JSON API With Ruby on Rails 5 ###
Update to latest rails `$ gem update rails`
Install the gems `$ bundle install`
DB migration `$ rails db:migrate`
Run spec tests `$ bundle exec rspec`
View the routes `$ rails routes`
Run server `$ rails s`

### Test ###
# GET /todos
$ http :3000/todos
# POST /todos
$ http POST :3000/todos title=Mozart created_by=1
# PUT /todos/:id
$ http PUT :3000/todos/1 title=Beethoven
# DELETE /todos/:id
$ http DELETE :3000/todos/1