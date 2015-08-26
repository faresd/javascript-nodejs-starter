### Prismic.io Website Starter for NodeJS (uses express and jade)

This application is a "batteries included", ready to use website and blog engine. It is designed with document types similar to existing CMS like Wordpress, **blog posts** and **pages**.

#### Getting started

* Download the [latest release]()
* Unzip locally or on your server
* Modify `prismic-configuration.js` by adding your API end point by changing `apiEndpoint` and if needed `accessToken`.
* That's it!

To run it on your local machine, 2 possibilities:

* In command line: 
  npm install
  node app

Some remarks:

* Your repository must be a clone of http://prismicwebsite.me. You can modify the default document masks, but that may require adapting the NodeJS source code.

#### Deploy your NodeJS application

An easy way to deploy your NodeJS application is to use [Heroku](http://www.heroku.com). Just follow these few simple steps once you have successfully [signed up](https://id.heroku.com/signup/www-header) and [installed the Heroku toolbelt](https://toolbelt.heroku.com/):

Create a `Procfile` file at your application root, to declare the server command:

```
web: node app.js
```

Create a new Heroku application

```
$ heroku create
```

Push your code to heroku:

```
$ git push heroku master
```

Ensure you have at least one node running:

```
$ heroku ps:scale web=1
```

You can now browse your application online:

```
$ heroku open
```

#### Get started with prismic.io

You can find out [how to get started with prismic.io](https://developers.prismic.io/documentation/UjBaQsuvzdIHvE4D/getting-started) on our [prismic.io developer's portal](https://developers.prismic.io/).

#### Understand the JavaScript development kit

You'll find more information about how to use the development kit included in this starter project, by reading [its README file](https://github.com/prismicio/javascript-kit/blob/master/README.md).

### Contribute to the starter project

Contribution is open to all developer levels, read our "[Contribute to the official kits](https://developers.prismic.io/documentation/UszOeAEAANUlwFpp/contribute-to-the-official-kits)" documentation to learn more.


#### License

This software is licensed under the Apache 2 license, quoted below.

Copyright 2015 Prismic.io (http://www.prismic.io).

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
