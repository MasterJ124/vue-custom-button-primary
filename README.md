# vue-custom-button-primary

This isn't particularly useful, it's used as a demo for how to publish Vue components to NPM!

## Environment Support

- Support Vue 2 & Vue 3

## Using npm

We recommend using npm to install，it not only makes development easier，but also allow you to take advantage of the rich ecosystem of Javascript packages and tooling.

```
npm install vue-custom-button-primary --save
```

## Usage

main.js

```
import "vue-custom-button-primary/lib/vue-custom-button-primary.css"
```

pages/index.vue

```
<template>
  <VueCustomButtonPrimary>Primary Button</VueCustomButtonPrimary>
</template>

<script>
import VueCustomButtonPrimary from "vue-custom-button-primary";
</script>
```
