## Requirements

* Node Js

## Setup

Once you have cloned this repo to your machine you should do the following:

1. run `npm install` this will install all the deps (specified in the `package.json` to your machine [aka jest for now])
2. you can then run the test suite locally using this command `npm run test`
3. you can view the actual site itself by opening the file called `index.html`

## Run Unit Tests

You can run this command:

```
npm test
```
ORk
```
npm run test
```

To trigger all the unit tests to run locally on your machine, so that 
you can see which tests are working and which are not.


## Lint Check Tip:

You can run this command:

```
npx standard
```
OR
```
npm run lint
```

To perform a lint check locally on your machine!

You can run this command:

```
npx standard --fix
```

To automatically change your code and fix the lint problems without doing any
code changes yourself! Nice!


## surge?

http://surge.sh/

surge
makeup details


<path> <domain> must end in surge.sh

surge . bk-sample-site-staffs.surge.sh

env:
  SURGE_TOKEN: ${{ secrets.SURGE_TOKEN }}
run: surge --project ./ --domain <your-prefered-surge-subdomain>.surge.sh --token $SURGE_TOKEN

## Own GHA 

New Dir
created yml file
created index.js file
npm init enter all
edited yml file
editied indx file
deps:
"@actions/core": "^2.0.1"
npm install
git init
ga
gcom
create private repo and push
tag and push v1
gitignore! node_mods
i
test
