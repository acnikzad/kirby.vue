<template>
  <section>
    <div class="quote">
      <h1>Build a Quote</h1>
    </div>
    <div class="row">
      <div class="col span-1-of-2 options">
        <p>Select trailer:</p>
        <p>Select color:</p>
      </div>
      <form>
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
          <br>
          <br>
          <select id="">
            <option value="">--Please choose an option--</option>
            <option value="red">Red</option>
            <option value="black">Black</option>
            <option value="gray">Gray</option>
            <option value="blue">Blue</option>
            <option value="white">White</option>
          </select>
          <br>
          <br>
          <textarea name=”ContactCommentt” rows=”8″ cols=”50″>Questions or comments?</textarea>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
};
</script>
