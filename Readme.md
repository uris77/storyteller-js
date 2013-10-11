#  Storyteller JS Version

# Development
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
