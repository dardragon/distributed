Distributed Systems 
===================

In the directory ***ass5*** is the **question 3** of the *assignment 5*.

It works with Ruby on Rails:
  - Ruby version:  2.0.0-p0
  - Rails version: 4.0.0

[ruby website](http://rubyonrails.org/download)
---

Install
===

    git clone https://github.com/chamini2/distributed.git a
    cd a/ass5
    bundle install
    rake db:migrate; rake db:seed; rake spree_sample:load
    
A lot of output is going to come out.

When asked:  
  - Email:    *enter*
  - Password: *enter*

---
    
    rails server

Then go in your browser to http://0.0.0.0:3000/
