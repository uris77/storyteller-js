# TDD - Grunt - BB - Archetype.
This is a skeleton that can be used to quickly start a Marionettejs/Backbonejs utility/component. It was created out of
a need to build re-usable components across projects using TDD. This is a customized version of https://github.com/uris77/tdd-grunt-archetype.

__Note__: this was inspired by [Linemanjs](https://github.com/testdouble/lineman). If you need to build rich javascript
front-end,please consider using __Linemanjs__. This utility is only for building small contained libraries that depend
on Backbonejs and Marionettejs.

# Development
Checkout the code:
```
$ git clone git@github.com:uris77/tdd-grunt-bb-archetype my_new_project_name
```
1. Set up the dev environment after checking out the code:
```bash
$ npm install
```

2. The code is contained inside the __src__ dir, and the specs inside __spec__ dir.

3. Run the specs:
```bash
$ grunt spec
```
The specs are run with __Testem__ and uses __Jasmine__.

4. Clean compiled assets:
```bash
$ grunt clean
```

5. Compile Handlebarjs templates
```bash
$ grunt handlebars
```

6. Building
```bash
$ grunt build
```
Build files will be generated in __/build__ directory. It will have both a minified version and a development version.


## Requirements
* Nodejs
* npm
* gruntjs

## License
[GPLv3](http://www.gnu.org/licenses/gpl-3.0.html)