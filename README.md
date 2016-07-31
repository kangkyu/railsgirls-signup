# Rails Girls Signup

$ `rails new your_app_name --database=postgresql`

* Ruby version: '2.3.0'

* Rails version: '5.0.0'

* Database: Postgres

* Deployment instructions  
$ `git clone git@github.com:jendiamond/railsgirls_signup.git`  
$ `bundle`  
$ `rake db:create`  
$ `rake db:migrate`

* To run the test suite: `bundle exec rspec`

---
---

### How it was made...

$ `rvm list rubies`

$ `rvm rubies`

=* ruby-2.1.4 [ x86_64 ]
   ruby-2.2.1 [ x86_64 ]
   ruby-2.2.2 [ x86_64 ]
   ruby-2.3.0 [ x86_64 ]

# => - current
# =* - current && default
#  * - default

---

If Ruby 2.3.0 appears on that list and it is not current than run:

$ `rvm use 2.3.0`

---

If you don't have it in your list:

$ `rvm install ruby 2.3.0`

Then run:

$ `gem install bundler`

---

$ `gem install rails`

---

$ `rails new railsgirls-signup --database=postgresql`

---

+ git init
+ git workflow
+ add remote repo
+ push to remote repo

---