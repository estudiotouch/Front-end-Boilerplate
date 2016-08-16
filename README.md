# Front-end-Boilerplate
Basic structure for front-end development

##Assets

###Framework
- Bootstrap v3.3.6 (SASS version)

###Vendors
- Jquery v2.2.4
- Jquery Migrate v1.4.1
- Modernizr v3.3.1

###Managers
- Grunt
- Bower

####Grunt plugins
- Concurrent
- Clean
- Concat
- Copy
- Cssmin
- Imagemin
- JShint
- Sass (grunt-sass with libsass)
- Sass globbing
- Uglify
- Watch
- Spritesmith
- Usemin + Wiredep

##Sync with source
```sh
  $ git fetch upstream
  $ git checkout master
  $ git merge upstream/master
  ```

##Usage

1. Install dependencies, packages and initial structure

```sh
  $ npm install && bower install
  ```
2. Build project

```sh
  $ grunt build
  ```
3. Watch files

```sh
  $ grunt
  ```
