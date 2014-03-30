# Client App Skeleton

web app skeleton

## Components

- coffee-script
- browserify
- power-assert
- mocha-phantomjs

## Build

```
npm install
bower install
npm run patch
grunt build
grunt test
```

## Result

```
  1) Array#indexOf() should return index when the value is present:
     AssertionError: # /Users/ken/work/client-app-skeleton/test/initialize.coffee:13

    return assert(this.ary.indexOf(who) !== minusOne);
                       |   |       |    |   |
                       |   |       |    |   -1
                       |   |       |    false
                       |   -1      "ariya"
                       [1,2,3]
```

## Tasks

```
# build app
grunt build

# run mocha-phantomjs
grunt test

# server with run test
grunt server
```
