<template>
 <div style="width: 50%; align: center; float: center; margin: 10px auto">
 <h1 style="font-family: 'Stick No Bills', sans-serif; font-size: 40px;color: lightblue; -webkit-text-stroke-width: 1px; -webkit-text-stroke-color: #42b883; text-shadow: 10px 10px 10px #000;">Odin's Twitter API Integration</h1>

  <a
   class="twitter-timeline"
   :href="src"
   :data-theme="dark ? 'dark' : 'light'"
   :data-link-color="dataLinkColor"
  ></a>
  </div>
</template>

<script>
export default {
  props: {
    src: {
      type: String,
      default: 'https://twitter.com/VikingNation4?ref_src=twsrc%5Etfw'
    },
    dark: {
      type: Boolean,
      default: true
    },
    dataLinkColor: {
      type: String,
      default: '#2B7BB9'
    }
  },
  created () {
    const twitterFeed = document.createElement('script')
    twitterFeed.setAttribute('src', 'https://platform.twitter.com/widgets.js')
    document.head.appendChild(twitterFeed)
  }
}
</script>
