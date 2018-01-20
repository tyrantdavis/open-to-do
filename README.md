# Open-To-Do API

Build an externally usable API for a basic to-do list app. This API will allow users to modify user
accounts and to-do items from the command line. 

## Application Features:
* uses Rails serializers to convert Rails objects into JSON
* api_controller defines an authenticated method that requires a user to provide a username and a password in the Curl command.


## Setup 

#### Languages and Frameworks: 
* Ruby version 2.3.3
* Rails 4.2.7

#### Default Development Tools and Gems include:

* Devise  for user authentication
* Figaro for secure configuration

#### Configuration:
Figaro creates a _config/application.yml_ file, which sets up and stores  **_environment variables_**, and adds it into your _.gitignore_ file. The _config/application.example.yml_ file demonstrates the appropriate way to store _environment variables_.

_Made with my mentor at [Bloc](http://bloc.io)_

