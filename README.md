# Deploy Your Own REST API in 30 Mins Using Atlas and Heroku

This tutorial demonstrates how to use the MEAN stack to rapidly create a RESTful API server and web application.

http://sitepoint.com/deploy-rest-api-in-30-mins-mlabs-heroku

## Requirements

* [Node.js](http://nodejs.org/)
* [Heroku Account](https://signup.heroku.com/)
* [Heroku Toolbelt](https://toolbelt.heroku.com/)
* [atlas account](https://www.mongodb.com/download-center/)
* [MongoDB In The Cloud With Atlas](https://youtu.be/KKyag6t98g8)

## Installation

1. Clone repo
2. Run `heroku create`
3. Run `npm install`
4. Create a new single-node Sandbox MongoDB database in US EAST
5. Set `MONGOLAB_URI` env var on Heroku
6. Run `git push heroku master`
7. Run `heroku ps:scale web=1`
8. Run `heroku open`

## License

The MIT License (MIT)

Copyright (c) 2016 SitePoint

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

#123
heroku config:set MONGODB_URI=mongodb+srv://<user>:<password>@<cluster>.mongodb.net/test?retryWrites=true
export MONGODB_URI=mongodb://localhost:27017
#web
https://protected-ridge-73240.herokuapp.com/