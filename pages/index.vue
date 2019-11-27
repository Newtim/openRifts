<template>
  <section class="container docs-container">
    OpenRifts is House Rules project meant to help people make characters in the fun world of paladium.

    <div class="side-note">
      <h3>Hey! Stuff is missing!</h3>
      <p>Some content you may be expecting, it is not here yet, I am working on it. </p>
      
    </div>

    <h1>Join us in creating the new OpenRifts!</h1>
    <p>We’re starting on a new version of the site with lots of new, highly-requested features like: better search, more art, tokens, inline rollers, and more!</p>

    <p>If you enjoy OpenRifts, join us on Discord to talk about it. Our discord is a place to talk about the redesign as well as rules, tools, art, gaming in general, or anything else on your mind!</p>

    <p>We will also start working on creating more supporting art for the OpenRifts.</p>
    
  </section>
</template>

<script>
import axios from 'axios'
import StatBonus from '~/components/StatBonus.vue'

export default {
  components: {
    StatBonus
  },
  data () {
    return {
      monsters: [],
      spells: [],
    }
  },
}
</script>

<style>
.monster-block, .spell-block {
  margin-top: 1rem;
}
</style>

