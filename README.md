# Gem::RemoteFetcher::FetchError reproduce repo

1. Clone this repository
2. `$ bundle`
3. Shall see following error

  ```
  Gem::RemoteFetcher::FetchError: bad response Not Found 404 (https://rubygems.global.ssl.fastly.net/gems/web-console-3.1.0.gem)
  An error occurred while installing web-console (3.1.0), and Bundler cannot continue.
  Make sure that `gem install web-console -v '3.1.0'` succeeds before bundling.
  ```
