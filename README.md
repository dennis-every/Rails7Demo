# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version 3.1.2

* Rails 7.0.3 w/ importmap

* Commands

rails new Rails7Demo --javascript=importmap

cd Rails7Demo

rails g controller home index

rails g scaffold Post title content:text

rails action_text:install

./bin/importmap pin local-time

./bin/importmap pin local-time --download

rails g resource comment post:references content:text

rails g mailer comments submitted
