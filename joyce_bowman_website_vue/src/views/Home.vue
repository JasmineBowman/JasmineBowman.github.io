<template>
  <div id="app">
    <div class="home">
    
      <div class="items">

        <article class="item thumb span-1">
          <h2>You really got me</h2>
          <a href="images/fulls/01.jpg" class="image"><img src="images/thumbs/01.jpg" alt=""></a>
        </article>

        <article class="item thumb span-2">
          <h2>Ad Infinitum</h2>
          <a href="images/fulls/02.jpg" class="image"><img src="images/thumbs/02.jpg" alt=""></a>
        </article>

        <article class="item thumb span-1">
          <h2>Different</h2>
          <a href="images/fulls/03.jpg" class="image"><img src="images/thumbs/03.jpg" alt=""></a>
        </article>

        <article class="item thumb span-1">
          <h2>Elysium</h2>
          <a href="images/fulls/04.jpg" class="image"><img src="images/thumbs/04.jpg" alt=""></a>
        </article>

        <article class="item thumb span-3">
          <h2>Kingdom of the Wind</h2>
          <a href="images/fulls/05.jpg" class="image"><img src="images/thumbs/05.jpg" alt=""></a>
        </article>

        <article class="item thumb span-1">
          <h2>The Pursuit</h2>
          <a href="images/fulls/06.jpg" class="image"><img src="images/thumbs/06.jpg" alt=""></a>
        </article>

        <article class="item thumb span-2">
          <h2>Boundless</h2>
          <a href="images/fulls/07.jpg" class="image"><img src="images/thumbs/07.jpg" alt=""></a>
        </article>

        <article class="item thumb span-2">
          <h2>The Spectators</h2>
          <a href="images/fulls/08.jpg" class="image"><img src="images/thumbs/08.jpg" alt=""></a>
        </article>

      </div>
  </div>
</div>


</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'home',
  components: {
    HelloWorld
  }
};
</script>
