# grunt-static-site

[![Greenkeeper badge](https://badges.greenkeeper.io/lukekarrys/grunt-static-site.svg)](https://greenkeeper.io/)

[![Build Status](https://travis-ci.org/lukekarrys/grunt-static-site.png?branch=master)](https://travis-ci.org/lukekarrys/grunt-static-site)

### First time

```sh
git clone git@github.com:lukekarrys/grunt-static-site.git
mv grunt-static-site $PROJECT_NAME
cd $PROJECT_NAME
rm -rf .git/
git init
git commit -A -m "Initial commit"
npm install
# Update `homepage` and `repository` in `package.json`
```

### Dev

```sh
npm start
```

### Prod

```sh
npm run build
npm run deploy:gh
# or
npm run deploy:surge
```
