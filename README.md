# http4kbox-heroku - http4k app deployed to Heroku 

### Based on [more extensive example with multiple modes by David Denton](https://github.com/daviddenton/http4kbox)

This is a simple Dropbox clone built with [**http4k**](https://http4k.org) which uses S3 as a backing store, 
implemented in ~70 lines of code (when imports are excluded) deployed to Heroku. 

The core app uses the following [**http4k**](https://http4k.org) modules and features:

- `http4k-core` <-- main HTTP library
- `http4k-cloudnative` <-- for 12-factor configuration via environmental properties
- `http4k-aws` <-- replaces the Java AWS SDK
- `http4k-template-handlebars` <-- for templating
- `http4k-multipart` <-- multipart form uploads
- `http4k-testing-hamkrest` <-- for test assertions


## In action:

<img src="https://raw.githubusercontent.com/albertlatacz/http4kbox-heroku/main/screenshot.png"/>

