
<template>
  <div id="MyFirstSlideshow">
    <div class="eg-slideshow">
      <slide enter="animated fadeInDown">
        <h1>Vue for the New</h1>
        <img src="./assets/vue-logo.png" alt="Vue.js logo">
      </slide>
      <slide :steps=4 enter="bounceInRight" leave="bounceOutDown">
        <h3>The Progressive Javascript Framework</h3>
        <div class="center">
          <eg-transition enter="bounceInLeft" leave="bounceOutLeft">
            <h4 v-if="step >= 2">Reactivity</h4>
          </eg-transition>
          <eg-transition enter="bounceInRight" leave="bounceOutRight">
            <h4 v-if="step >= 3">Composability</h4>
          </eg-transition>
          <eg-transition enter="bounceInLeft" leave="bounceOutLeft">
            <h4 v-if="step >= 4">Ecosystem</h4>
          </eg-transition>
        </div>
      </slide>
      <slide enter="animated fadeInDown">
        <h1>Evan You</h1>
        <img src="./assets/evan-you.jpg" alt="Vue.js logo">
      </slide>
      <slide :steps=3 enter="bounceInRight" leave="bounceOutDown">
        <h4>What Came Before...</h4>
          <eg-transition enter="bounceInLeft" leave="none">
            <img v-if="step == 2" src="./assets/iconfinder_JQuery_logo_282806.png" alt="Vue.js logo">
          </eg-transition>
          <eg-transition enter="bounceInLeft" leave="none">
            <img v-if="step == 3" src="./assets/jquery-soup.png" alt="Vue.js logo">
          </eg-transition>
      </slide>
      <slide :steps=2 enter="bounceInRight" leave="bounceOutDown">
        <h3>The Enterprise Alternative</h3>
        <div class="center">
          <eg-transition enter="bounceInLeft" leave="bounceOutLeft">
            <img v-if="step >= 2" src="./assets/angular.png" alt="Vue.js logo">
          </eg-transition>
          <eg-transition enter="bounceInRight" leave="bounceOutRight">
            <img v-if="step >= 3" src="./assets/react-logo.png" alt="Vue.js logo">
          </eg-transition>
        </div>
      </slide>
      <slide :steps=2 enter="bounceInRight" leave="bounceOutDown">
        <h3>The Facebook Frontrunner</h3>
        <div class="center">
          <eg-transition enter="bounceInRight" leave="bounceOutRight">
            <img v-if="step >= 2" src="./assets/react-logo.png" alt="Vue.js logo">
          </eg-transition>
        </div>
      </slide>
      <slide enter="animated fadeInDown">
        <h4>new Vue();</h4>
        <img src="./assets/declarative.png" alt="simple vue example">
      </slide>
      <slide :steps=4 enter="bounceInRight" leave="bounceOutDown">
        <h3>Declarative Rendering</h3>
        <div class="center">
          <eg-transition enter="bounceInLeft" leave="bounceOutLeft">
            <h4 v-if="step >= 2">"Mustache" Template syntax</h4>
          </eg-transition>
          <eg-transition enter="bounceInRight" leave="bounceOutRight">
            <h4 v-if="step >= 3">Data Binding</h4>
          </eg-transition>
          <eg-transition enter="bounceInLeft" leave="bounceOutLeft">
            <h4 v-if="step >= 4">Reactivity</h4>
          </eg-transition>
        </div>
      </slide>
      <slide enter="animated fadeInDown">
        <img src="./assets/new-vue.png" alt="simple vue example">
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

      .eg-slide-content {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
      }
    }
  }
</style>
