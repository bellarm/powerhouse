<template>
  <div class="home-contact">
    <div class="title">
      CONTACT
    </div>
    <div class="subtitle">
      I havent got time to style this im sorry -bella
    </div>
    <form class="contact-form">
      <div>
        <label class="label" for="name">Name</label>
        <input type="text" name="name" id="name" placeholder="Name">
      </div>
      <div>
        <label class="label" for="email">Email</label>
        <input type="text" name="email" id="email" placeholder="Email">
      </div>
      <div>
        <label class="label" for="details">Details</label>
        <textarea name="details" id="details"  placeholder="Details"></textarea>
      </div>

    </form>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-contact {
  padding-top: 30px;
  padding-bottom: 30px;
  width: 100%;
  overflow: hidden;
  height: 80vh;
}

.box {
  margin-top: 30vh;
  padding: 50px 30px 50px 30px;
  float: left;
  background-color: white;
  width: 50%;
}

.title {
  text-align: center;
  font-size: 60px;
  font-family: 'Oswald', sans-serif;
  color: #000000;
  text-decoration: underline;
}

.subtitle {
  padding: 10px 10px 10px 10px;
  font-size: 20px;
  font-family: 'Lora', serif;
  color: #000000;
}

.contact-form {
  font-size: 16px;
  width: 500px;
  padding: 15px 30px;
  border-radius: 4px;
  margin: auto;
  width: 500px;
}

.contact-form .label {
  display: block;
}

</style>
