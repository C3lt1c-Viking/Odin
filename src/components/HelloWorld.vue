<template>
  <div class="hello" style="margin: 0 auto; text-align: center; float: center;')">
    <h1 style="font-family: 'Orbitron', sans-serif; color: #FFF; -webkit-text-stroke-width: 1px; -webkit-text-stroke-color: #42b883; text-shadow: 10px 10px 10px #000;">{{ msg }}</h1>
    <p style="font-family: 'Cinzel', serif; font-size: 25px;">
      Odin Love;<br/>
      Website Developer<br/>
      Mobile Application Developer<br/>
      Ethical Hacker<br/>
      Family Driven<br/>
      Gamer<br/>
    </p>
    <h3 style="font-family: 'Stick No Bills', sans-serif; font-size: 20px; -webkit-text-stroke-width: 1px; -webkit-text-stroke-color: #42b883; color: #000; font-size: 30px;">Connect with Odin;</h3>
    <ul>
      <li><a href="https://github.com/C3lt1c-Viking" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">GitHub</a></li>
      <li><a href="https://www.facebook.com/OdinLove.1990" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">Facebook</a></li>
      <li><a href="https://twitter.com/C3lt1cViking" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://www.twitch.tv/c3lt1cviking" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">Twitch</a></li>
      <li><a href="mailto:odinlove90@gmail.com" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">Email</a></li>
      <li style="font-family: 'Play', sans-serif; color: #F00; font-size: 20px;">Mobile: (469) 954-4923</li>
    </ul>
    <h3 style="font-family: 'Stick No Bills', sans-serif; font-size: 20px; -webkit-text-stroke-width: 1px; -webkit-text-stroke-color: #42b883; color: #000; font-size: 30px;">Projects Odin Has Worked On;</h3>
    <ul>
      <li><a href="https://octanedeck.herokuapp.com/" style="cursor: cell; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">OctaneDeck</a></li>
      <li><a href="https://rocky-dawn-56916.herokuapp.com/" style="cursor: cell; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">Expertware</a></li>
      <li><a href="https://b1-tech.herokuapp.com/" style="cursor: cell; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">EZ-Rater</a></li>
      <li><a href="https://khrissyscreations.com/" style="cursor: cell; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">Khrissys Creations</a></li>
    </ul>
    <h3 style="font-family: 'Stick No Bills', sans-serif; font-size: 20px; -webkit-text-stroke-width: 1px; -webkit-text-stroke-color: #42b883; color: #000; font-size: 30px;">Frameworks Used;</h3>
    <ul>
      <li><a href="https://vuejs.org/" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">VueJS</a></li>
      <li><a href="https://rubyonrails.org/" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">Ruby on Rails</a></li>
      <li><a href="https://www.php.net/" style="cursor: crosshair; font-family: 'Play', sans-serif; color: #F00; font-size: 20px;" target="_blank" rel="noopener">PHP</a></li>
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
/*
font-family: 'Cinzel', serif;
font-family: 'Orbitron', sans-serif;
font-family: 'Play', sans-serif;
font-family: 'Rubik Moonrocks', cursive;
font-family: 'Space Mono', monospace;
font-family: 'Stick No Bills', sans-serif;
*/
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
