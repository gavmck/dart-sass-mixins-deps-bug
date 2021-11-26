# Dart Sass Mixins from Dependencies bug with quiet-deps

Dart sass still emits warnings with `--quiet-deps` if you include mixins from a dependency then run that mixin, because it sees the context as local.

## Install

`npm install`

## Run

`npm run sass` and check the output in the console