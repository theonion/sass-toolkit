# reuseable sass files at the onion

<a href="http://development.sass-toolkit.divshot.io/">Online Documention</a>

## install

Add this project to your `bower.json`

Currently only available through git:

```
  "dependencies": {
    "sass-toolkit": "https://github.com/theonion/sass-toolkit.git#master"
  },
  "resolutions": {
    "sass-toolkit": "master"
  }
```

## local development

Use bower link to develop locally without having to cycle through a
publishing loop.

In your local sass-toolkit directory:
```
bower link
```

In the project you're working in:
```
bower link sass-toolkit
```

## documentation

`npm install`
`npm run sassdoc`

Documentation will generate into `sassdoc/index.html`

Be sure to publish changes to the toolkit before deploying/pushing your
branch.

## publishing documentation

`npm run update-docs` will generate and deploy the documentation to divshot.
`npm run push-docs` will merely deploy the documentation to divshot.

## available utilities

### flexbox

```sass
@include 'bower_components/sass-toolkit/utils/flexbox'
```
