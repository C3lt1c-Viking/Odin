<template>
  <div class="hello" style="margin: 0 auto; text-align: center; float: center">
    <h1>{{ msg }}</h1>
    <p>
      Odin Love;<br/>
      Website Developer<br/>
      Mobile Application Developer<br/>
      Ethical Hacker<br/>
      Family Driven<br/>
      Gamer<br/>
    </p>
    <h3>Connect with Odin;</h3>
    <ul>
      <li><a href="https://github.com/C3lt1c-Viking" style="cursor: crosshair;" target="_blank" rel="noopener">GitHub</a></li>
      <li><a href="https://www.facebook.com/OdinLove.1990" style="cursor: crosshair;" target="_blank" rel="noopener">Facebook</a></li>
      <li><a href="https://twitter.com/C3lt1cViking" style="cursor: crosshair;" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://www.twitch.tv/c3lt1cviking" style="cursor: crosshair;" target="_blank" rel="noopener">Twitch</a></li>
      <li><a href="mailto:odinlove90@gmail.com" style="cursor: crosshair;" target="_blank" rel="noopener">Email</a></li>
    </ul>
    <h3>Projects Odin Has Worked On;</h3>
    <ul>
      <li><a href="https://octanedeck.herokuapp.com/" style="cursor: cell;" target="_blank" rel="noopener">OctaneDeck</a></li>
      <li><a href="https://rocky-dawn-56916.herokuapp.com/" style="cursor: cell;" target="_blank" rel="noopener">Expertware</a></li>
      <li><a href="https://b1-tech.herokuapp.com/" style="cursor: cell;" target="_blank" rel="noopener">EZ-Rater</a></li>
      <li><a href="https://khrissyscreations.com/" style="cursor: cell;" target="_blank" rel="noopener">Khrissys Creations</a></li>
    </ul>
    <h3>Frameworks Used;</h3>
    <ul>
      <li><a href="https://vuejs.org/" target="_blank" rel="noopener">VueJS</a></li>
      <li><a href="https://rubyonrails.org/" target="_blank" rel="noopener">Ruby on Rails</a></li>
      <li><a href="https://www.php.net/" target="_blank" rel="noopener">PHP</a></li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: String
  }
})
</script>

<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #0000FF;
}
</style>
