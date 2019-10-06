
<template>
  <div id="MyFirstSlideshow">
    <div class="eg-slideshow">
      <slide enter="fade in">
        <h1>In the beginning...</h1>
      </slide>
      <slide enter="fade in">
        <h1>html</h1>
      </slide>
      <slide enter="fade in">
        <h1>Javascript</h1>
      </slide>
      <slide enter="fade in">
        <h1>Angular, React</h1>
      </slide>
      <slide enter="fade in">
        <h1>new Vue()</h1>
      </slide>
      <slide enter="fade in">
        <h1>Declarative Rendering</h1>
      </slide>
      <slide enter="fade in">
        <h1>Conditionals and Loops</h1>
      </slide>
      <slide enter="fade in">
        <h1>v-on and v-bind</h1>
      </slide>
      <slide enter="fade in">
        <h1>Vue Instance</h1>
      </slide>
      <slide enter="fade in">
        <h1>Data, Methods</h1>
      </slide>
      <slide enter="fade in">
        <h1>Vue Lifecycle</h1>
      </slide>
      <slide enter="fade in">
        <h1>Components</h1>
      </slide>
      <slide enter="fade in">
        <h1>Syntax</h1>
      </slide>
      <slide enter="fade in">
        <h1>Templating</h1>
      </slide>
      <slide enter="fade in">
        <h1>Shorthand</h1>
      </slide>
      <slide enter="fade in">
        <h1>JS in Templates</h1>
      </slide>
      <slide enter="fade in">
        <h1>Computed vs Methods</h1>
      </slide>
      <slide enter="fade in">
        <h1>function</h1>
      </slide>
      <slide enter="fade in">
        <h1>Props</h1>
      </slide>
      <slide enter="fade in">
        <h1>Emitting Events</h1>
      </slide>
      <slide enter="fade in">
        <h1>Slots</h1>
      </slide>
      <slide enter="fade in">
        <h1>Transitions</h1>
      </slide>
      <slide enter="fade in">
        <h1>Single File Components</h1>
      </slide>
      <slide enter="fade in">
        <h1>Ecosystem</h1>
      </slide>
      <slide enter="fade in">
        <h1>Unit Testing</h1>
      </slide>
      <slide enter="fade in">
        <h1>Typescript</h1>
      </slide>
      <slide enter="fade in">
        <h1>Don't use classes</h1>
      </slide>
      <slide enter="fade in">
        <h1>Hooks</h1>
      </slide>
      <slide enter="fade in">
        <h1>Vue Router</h1>
      </slide>
      <slide enter="fade in">
        <h1>Vuex</h1>
      </slide>
      <slide enter="fade in">
        <h1>Vuepress</h1>
      </slide>
      <slide enter="fade in">
        <h1>Nuxt</h1>
      </slide>
      <slide enter="fade in">
        <h1>Gridsome</h1>
      </slide>
      <slide enter="fade in">
        <h1>Nativescript Vue</h1>
      </slide>
    </div>
  </div>
</template>

<script>
import eagle from 'eagle.js'

export default {
  mixins: [eagle.slideshow],
  infos: {
    title: 'Vue for the New',
    description: 'A boilerplate to get you started',
    path: 'vue-for-the-new'
  }
}
</script>

<style lang='scss'>
  @import url(https://fonts.googleapis.com/css?family=Patrick+Hand+SC);

  #MyFirstSlideshow {
    .eg-slideshow {
      font-family: 'Patrick Hand SC';
      background-color: #f8f8f2;

      .eg-slide {
        display: flex;
        align-items: center;
        justify-content: center;

        .eg-slide-content {

        }
      }
    }

    .eg-slide-content {

    }
  }
</style>
