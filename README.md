![My image](http://mrgrillet.com/wp-content/uploads/2018/03/projectmanager.png)

# Concept

This is a very simple project management app. 

It allows users to signup as an Admin. Create an organisation, add projects to that organisation and then invite team members via email to join the organisation. Admins can then add / remove Team Members from projects. 

## Learnings

* Adding Strip with a custom form
* Allowing users to upgrade their plans
* Uploading files

# Technology

* HTML5
* CSS3
* JavaScript
* Ruby On Rails
* Stripe for payments
* Devise
* Heroku
* Database: PostgreSQL
* Gems:
  * Mailia (for multi-tenancy)
  * Bootstrap
  * AWS SDK
  * Bootstrap Date Picker

# Features

* Responsive
* Multi-tenancy (Subdomains for Orgnaisations)
* Ability to take payments
* Add new project
  * Project title
  * Completion date
  * Description
  * Add and remove team members
  * Add files to projects
* Users can sign up
  * Email authentication
  * New Admin User can sign up and create an organisation
  * Admin can invite team members to join organisation
  * Admin can add team members to projects
* Plans
  * Free: 1 project, multiple users
  * Paid: multiple projects, multiple users
  * Ability to upgrade and downgrade plans

View the project here:

[https://armoury-projectmanager.herokuapp.com/](https://armoury-projectmanager.herokuapp.com/)

