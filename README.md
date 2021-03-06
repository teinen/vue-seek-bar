# vue-seek-bar

Very simple page top scroll seek bar with Vue.js.

![demo image](https://user-images.githubusercontent.com/25704785/52998027-8b9a5780-3465-11e9-98d7-12595bc8f8cb.gif)

## Install

```bash
# npm
npm install vue-seek-bar

# yarn
yarn add vue-seek-bar
```

## Usage

```js
<template>
  <div id="main">
    <VueSeekBar color="#42b983" opacity="0.9" height="3" />
    <div>
      Your page contents here!!!
    </div>
  </div>
</template>

<script>
import VueSeekBar from "vue-seek-bar";

export default {
  components: { VueSeekBar }
};
</script>
```

## Props

### `color`

Specify seek bar color.  
You can use both color code(`#000000`), and `rgb()`.

### `opacity`

Specify seek bar opacity.  
Input `0.1` to `1.0`.

### `height`

Specify seek bar height.

## License

MIT

## Author

teinen
