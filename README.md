![chrome_54Uk8Qpx8p](https://user-images.githubusercontent.com/54861487/86740454-4a074e00-c054-11ea-8d35-ddcb438982e7.png)

[![Netlify Status](https://api.netlify.com/api/v1/badges/f88fe30e-103a-4157-8ead-30de668b037c/deploy-status)](https://app.netlify.com/sites/vue-preloader/deploys)

## Demo and playground
Live demo - https://vue-preloader.netlify.app/

[Playground Website](https://vue-preloader.netlify.app/).
Adjust the settings using the playground options. On the bottom of the page you will find the source code that you can directly use in your project or you can manually change the props.

## Installation

```bash
# use yarn
yarn add 
# use npm
npm install --save 
```

## Usage

In your main.js
```js
import Vue from 'vue'


```

In your template
```vue
<template>
  <loader object="#ff7b00" 
    color1="#ffffff" 
    color2="#17fd3d" 
    size="5" 
    speed="2" 
    bg="#343a40" 
    objectbg="#999793" 
    opacity="100" 
    name="circular">
  </loader>
</template>
```

>note(you can either use the [playground](https://vue-preloader.netlify.app/) website to automatically get all the props set or you can set them manaully using the below prop list. You can also resort to not passing any prop, in this case the preloader will use default settings.)

## Props
| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| name | string | 'spinning' | decides the type of loader |
| object | string | '#ff9633' | set the color of the loaders. hex or color |
| color1 | string | only for circular | set the color of the circular loader disk1. hex or color |
| color2 | string | only for circular | set the color of the circular loader disk2. hex or color |
| size | number | 5 | set the size of loader |
| bg | string | '#343a40' | set the color of the loader background. hex or color |
| objectbg | string | '#999793' | set the color of the loader object background. hex or color |
| opacity | number | 80 | set the opacity of background |
| speed | number | 2 | animation speed in seconds |

## Author

&#169; [Vinayak sharma](https://github.com/vinayaksh42)
 [Hrishikesh Agarwal](https://github.com/codetheorem)

