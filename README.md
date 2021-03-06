# [Machine Learning Questions](https://git.io/fj0yP) ![build](https://travis-ci.org/ztlevi/Machine_Learning_Questions.svg?branch=master)

Github repo: https://github.com/ztlevi/Machine_Learning_Questions

Gitbook is deployed over [here](https://git.io/fj0yP).

## Start to contribute

```sh
git clone https://github.com/ztlevi/Machine_Learning_Questions.git

cd Machine_Learning_Questions

# Pre-commit plugins
pip3 install pre-commit
pre-commit install

# Please use nodejs 10
brew install nodenv node-build
nodenv install 10.23.2
nodenv local 10.23.2 # set local nodejs version

# Install dependencies
npm install
npm run docs:prepare

# Start to watch the book
npm start # or npm run docs:watch

# Deploy the book
npm run docs:publish
```

## Use the code

```sh
pip3 install pipenv
pipenv install
pipenv shell
```
