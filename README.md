# URL Shortener App

Combines Rails BE with ReactJS FE

analogue to https://bitly.com.
The main idea is - users will be able to save a long link and use a shortened version instead.
Basically visiting the shortened link will redirect you to the original one.
Apart from the main functionality the link owner will be able to collect the statistics about how many visits that link had.
The short link will not be accessible after 1 month from the last visit etc


Project setup
1. Clone the repo with `git clone https://github.com/sergiy17/url-shortener-app.git`
2. Install dependencies `cd url-shortener-app && script/setup`

This script will clone the ReactJS FE part from https://github.com/sergiy17/url-shortener-react.git
and Rails BE part from https://github.com/sergiy17/url-shortener-rails.git

Then it will create db, install dependencies for both BE, FE and run servers.

After setup both servers will be accessible on these ports:

Rails backend: http://localhost:3000

React frontend: http://localhost:3006
