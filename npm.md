# npm

[npm](https://npmjs.com/) is lots of things.

## Configuration

### Set prefix (for installing packages globally)

```
npm config set prefix <directory>
```

## Usage

### Bump version (and create a git commit with a tag)

```
npm version <patch|minor|major> -m "<message>"
```

### Install a package from cache (for offline usage)

```
npm --cache-min Infinity install <package>
```
