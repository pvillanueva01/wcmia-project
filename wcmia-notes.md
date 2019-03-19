## Plugins

Topics: Hooks, actions, settings, Customizer API

https://github.com/davidwolfpaw/wcmia2019-plugin-workshop

- Create folder toc ontain all files
- You can separate sections of your code into different files and add them as includes

## OOP with Wordpress 

uses code classes together to solve problems

https://carlalexander.ca/approaching-object-oriented-programming-wordpress/#slides

- Wordpress used procedural programming - programming using steps, since PHP as a language did not have that capability until PHP 5
- Put procedural code into a class, namespacing is a must, prefix it = this is the WP way!
- Programming uses Legos!!!
- Class post, page, author, etc
- OOP framweorks do the heavy lifting in the regular programming, but for WP this is different, you have to design and build the whole thing from scratch
- Most plugins need Class Admin Page, Class Options, Class Metabox, Class Plugin
- Ecommerce Classes products, sales, etc.
- These classes have properties, methods, a constructor

## Tools and Techniques for WP Local Development

https://www.chriswiegman.com/2019/03/slides-from-wordcamp-miami-2019/

https://github.com/wordpress-coding-standards/wordpress-coding-standards

https://code.visualstudio.com/docs/?dv=osx

- API testing: Insomnia, Postman, Paw
- Unit Testing: phpunit, qunit

## Webpack for WP Development

https://wpscholar.com/


### Terminology

- Handy for JS, module bundler, minify files
- entry point: root of the dependency graph
- output: where the generated bundles go (path)
- loaders: intercept dependencies and process them before bundled
- plugins to add capabilities for webpack

### Demo

- Be sure to have node and npm installed, go to the root of your plugin/file
- npm init to start package.json file
- npm i -D wepack webapck-cli
- set up webpack.config file, see: https://gist.github.com/wpscholar 

## Design Principles for Software Architecture

- Clients care about cost, timeline and effectiveness
- Changes happening early in the process are easier to change/fix

