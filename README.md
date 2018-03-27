# social-sense-meta
This is a meta repository that describes the (currently) three components of the social-sense system


## social-sense-query
The above system is an implementation of an application server that interacts with social media providers to get access to user tokens/secrets. 
The server itself is developed in a PHP framework called [Laravel](https://laravel.com/). It works in conjunction with Oauth1/2 standards for logging in and out.

## social-sense-graphql
The above system is a [GraphQL](https://graphql.org/) server written with [Express.JS](https://expressjs.com/) using the [Express-GraphQL](https://github.com/graphql/express-graphql) package.
It is presently necessary that the social-sense-query server supports a subset of the providers supported by the social-sense-graphql server.


## social-sense-data
The above system is a [Flask](http://flask.pocoo.org/) server written with Python for ad-hoc data processing/exploration. 
