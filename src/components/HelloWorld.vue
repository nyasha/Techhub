<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p> Entrepreneurship Club aims to serve the broad range  of demands from those seeking to engage in entrepreneurship, creativity, and innovation throughout Zimbabwe. </p>
    <ul>
      <li>
        <a
          href="https:/cowork.co.zw"
          target="_blank"
        >
          Sign up
        </a>
      </li>
      <li>
        <a
          href="https://www.facebook.com/pg/techhubharare/community/"
          target="_blank"
        >
          Forum
        </a>
      </li>
      <li>
        <a
          href="https://discordapp.com/channels/340160225338195969/389885858729164801"
          target="_blank"
        >
          Community Chat
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/hararehub"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <br>
      <li>
        <a
          href="https://www.facebook.com/notes/tech-hub-harare/tech-hub-harares-innovative-mind/699829433725648/"
          target="_blank"
        >
          Want to learn more?
        </a>
      </li>
    </ul>
    <h2>Connecting with us is easy</h2>
    <ul>
      <li>
        <a
          href="https://www.facebook.com/techhubharare/"
          target="_blank"
        >
          Facebook
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/HarareHub"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <li>
        <a
          href="https://www.facebook.com/techhubharare/videos/589191111456148//"
          target="_blank"
        >
          Learn more
        </a>
      </li>
      <li>
        <a
          href="https://docs.google.com/forms/d/e/1FAIpQLSekEPQ5fM0nKloJtFJL4MnPNu8SB--fvRIKuYZIgxAykAKNaQ/viewform?usp=sf_link"
          target="_blank"
        >
          Join Now 
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to our Entrepreneurship club"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
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
  color: #42b983;
}
</style>
