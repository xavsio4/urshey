<template>
  <div class="bg-black text-white">
    <Hero />
    <a name="about" />
    <div class="text-center p-10">
      <h3 class="text-4xl">THEY WERE</h3>
      <p class="centered">
        <i class="icon icon-circle"></i><i class="icon icon-circle"></i
        ><i class="icon icon-circle"></i>
      </p>
      <div class="mt-4">
        <p class="text-2xl">
          Urshey was a belgian pop-rock band born next to Namur.
        </p>
        <p class="text-2xl mt-4">
          Their first and only album "Travel &amp; Ghosts" has been distributed
          by Universal Belgium and can be now found in Amazon, iTunes, Spotify.
        </p>
        <h3 class="mt-4 text-2xl">Listen to Urshey on</h3>
        <div class="flex flex-row justify-center">
          <a
            class="m-2"
            href="https://itunes.apple.com/lu/album/travel-and-ghosts/id573835085"
            ><img src="~/static/itunes.png" target="blank"
          /></a>
          <a class="m-2" href="http://myspace.com/urshey/videos" target="blank"
            ><img src="~/static/Myspace.png"
          /></a>
          <a class="m-2" href="http://www.spotify.com" target="blank"
            ><img src="~/static/spotify.png"
          /></a>
          <a
            class="m-2"
            href="http://www.amazon.fr/Travel-Ghosts-Urshey/dp/B009WUOD8E/ref=sr_1_3?ie=UTF8&amp;qid=1390925029&amp;sr=8-3&amp;keywords=urshey"
            target="blank"
            ><img src="~/static/Amazon.png"
          /></a>
        </div>
        <p>The band splitted by the end of 2007</p>
        <p>&nbsp;</p>
      </div>
    </div>
    <a name="audio" />
    <div class="bg-black ml-20 mr-20 mb-20">
      <player />
    </div>
    <a name="gallery" />
    <gallery />
    <footerbar></footerbar>
  </div>
</template>

<script>
import Player from '~/components/Player.vue'
export default {
  components: { Player },
}
</script>
<style>
body {
  background-color: #f2f2f2;
  font-family: 'EB Garamond', serif;
  font-weight: 300;
  font-size: 16px;
  color: #555;

  -webkit-font-smoothing: antialiased;
  -webkit-overflow-scrolling: touch;
}
</style>
