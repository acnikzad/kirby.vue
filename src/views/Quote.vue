<template>
  <section>
    <div class="quote">
      <h1>Build a Quote</h1>
    </div>
    <div class="row">
      <div class="col span-1-of-2">
        <h3>Select trailer:</h3>
      </div>
      <div class="col span-1-of-2">
        <select id="">
          <option value="">--Please choose an option--</option>
          <option value="XTR">XTR Off Road Teardrop Trailer</option>
          <option value="XTR-XL">XTR-XL Off Road Teardrop Trailer</option>
          <option value="XTC">XTC Off Road Teardrop Trailer</option>
          <option value="ST-Sport">Xsport ST Teardrop Trailer</option>
          <option value="XTS">XTS Model Teardrop Trailer</option>
          <option value="Cub">Cub Classic Vintage Teardrop Trailer</option>
          <option value="Camp">Command Camp Off Road Teardrop Trailer</option>
          <option value="Blackhawk">Blackhawk Off Road Adventure Trailer</option>
        </select>
      </div>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
