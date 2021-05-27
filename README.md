# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# fin-trac

# Create Stock model with Attributes

Task: Design and add stock model
- Attributes name, ticker_symbol and price
- Automate looking up Stock(currently only possible through rails console)
- Automate API key insertion (instead of having to key it in everytime in
  look up a stock)
- This will expose  us to secure credentials in Rails apps:
  credentials.yml.enc (encrypted file)
  master.key(key to decrypt credentials file)
