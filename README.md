# MusicRater

A small web application for rating music, built as a school project. Entries are stored in a database on the server and served through a Ruby backend.

## Built with

- Ruby with the Sinatra web framework
- HTML view templates
- A database for storing entries and ratings
- Rack (`config.ru`) and Bundler (`Gemfile`)

## Running it

1. Install the dependencies:
```
   bundle install
```
2. Start the app:
```
   bundle exec rackup
```
3. Open the local address shown in the terminal (usually http://localhost:9292) in your browser.

## Project structure

- `app.rb`: routes and application logic
- `views/`: HTML templates
- `db/`: database files
