##To Do List

This will create an app to make different lists of tasks.

##Setup
Assuming you have ruby installed. In the terminal:

`gem install bundle`

`bundle`

`ruby app.rb`

In psql create a databases titled to_do and to_do_test

the tables in the databases are titled "tasks" and "lists"

The tasks table included: description (varchar), due_date (timestamp), and list_id (int), and its own id

the lists table included its own id, and names (varchar)

Go to http://localhost:4567 in your browser

##Tests
Testing the ruby methods can be done via rspec.

`gem install rspec`

`rspec`

##Motivation

To practice creating a ruby class that interacts with the web via POST.

##License

MIT License, copyright 2015. Created by Kathryn Carr and Jackie Fletcher.
