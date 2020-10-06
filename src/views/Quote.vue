<template>
  <section>
    <h1 class="text-center">Build A Trailer</h1>
    <form class="quote">
      <div class="form-group">
        <label for="firstname">First Name</label>
        <input type="firstname" class="form-control" id="firstname" aria-describedby="emailHelp" placeholder="First Name">
      </div>
      <div class="form-group">
        <label for="lastname">Last Name</label>
        <input type="lastname" class="form-control" id="lastname" aria-describedby="emailHelp" placeholder="Last Name">
      </div>
      <div class="form-group">
        <label for="phonenumber">Phone Number</label>
        <input type="email" class="form-control" id="phonenumber" aria-describedby="emailHelp" placeholder="Phone Number">
        <small id="emailHelp" class="form-text text-muted">We'll never share your phone number with anyone else.</small>
      </div>
      <div class="form-group">
        <label for="exampleInputEmail1">Email address</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
      </div>
      <div class="form-group">
        <label for="exampleFormControlSelect1">Select Trailer</label>
        <select class="form-control" id="exampleFormControlSelect1">
          <option>-- Select Trailer --</option>
          <option>XTR Off Road</option>
          <option>XTR-XL Off Road</option>
          <option>XTC Off Road</option>
          <option>Command Camp Off Road</option>
        </select>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
};
</script>
