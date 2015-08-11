# reuseable sass files at the onion

## install

Add this project to your `bower.json`

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

## available utilities

### flexbox

```sass
@include 'bower_components/sass-toolkit/utils/flexbox'
```
