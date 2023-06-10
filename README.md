# npm-import

## Importing code

Clone this repo
```bash
git clone https://github.com/mozey/npm-import.git
cd npm-import
```

Install node_modules directly from a github repo [mozey/npm-package](https://github.com/mozey/npm-package)<sup>[1]</sup>, and from a local dir [mozey/npm-local](https://github.com/mozey/npm-local)<sup>[2]</sup>
```bash
npm install
```

**TODO** Run tests


## Specify version

**TODO** Update package to a specific version


## Reference

[1] Package hosted on github previously saved as a dev dependency like this
```bash
npm install --save-dev mozey/npm-package
# Always commit the lockfile
# https://stackoverflow.com/a/76058921/639133
```

[2] It's also possible to specify a [local dependency in package.json](https://stackoverflow.com/a/26028854/639133) (as of npm 2.0.0)
```bash
export PRO_PATH="/absolute/path/to/your/projects/dir"
npm install --save-dev "$PRO_PATH/npm-local"
```