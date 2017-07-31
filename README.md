# A Grunt Project Template for Frontend Development

A streamlined web development project structure using Javascript, Sass, and Grunt. This is a project originally built for Motion Math's homepage at <http://motionmathgames.com>. 

## Getting Started

You'll need to install:

1. [Node.js](https://nodejs.org/en/)

2. [Bower](http://bower.io/)

3. [Grunt](http://gruntjs.com/)


Then, on the command line, to run your project locally:

```
npm install
grunt
```

To package your project for distribution:

```
grunt dist
```

If you haven't used [Sass](http://sass-lang.com) before, be sure to check out the [Sass Basics](http://sass-lang.com/guide) guide.

The project comes set up for using [Bootstrap](http://getbootstrap.com/) along with Sass for styling. 


## HTML Templates

The project comes set up with a templating system for HTML that supports a different set of values for development and distribution. You can edit the corresponding value files in the templates directory and set default values in templates/default.json. Default values will be overriden by those in dev.json and dist.json when available. You can read more about how templating works: [grunt-template](https://github.com/mathiasbynens/grunt-template).


## Project Structure

    .
    ├── html              # HTML files that will be located in the top level at time of hosting
    ├── css               # Sass files (.scss) that will be compiled into css
    ├── js                # Javascript files that are bundled into minified files
    ├── assets            # Static assets that are directly copied to the distribution folder
    ├── public            # Generated directory containing bower components and hosted files or packaged files ready for distribution
    ├── Gruntfile.js      # Defines Grunt tasks for developing and building the project
    └── README.md