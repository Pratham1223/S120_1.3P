<template>
  <div class="about">
    <h2>About Me</h2>
    <p>Some text about me. Some text about me. I am lorem ipsum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing
      elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </p>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vel odio assumenda ex architecto accusamus aut consequuntur mollitia alias aliquam animi ipsa libero ratione, tempora similique, debitis fuga fugit voluptatibus! Ad?</p>
    <h3>My Skills</h3>
    <ul>
      <li>Photography</li>
      <li>Web Developement</li>
      <li>Writting</li>
   </ul>
  </div>
  </template>
  <style scoped>
  .about {
  margin: 10px;
  padding: 20px;
  border: 1px solid #1e1ec8;
  border-radius: 5px;
  background-color: #edf0f3;
}

.about h2 {
  font-size: 20px;
}

.about p {
  font-size: 15px;
  line-height: 1.5;
}

.about ul {
  margin-left: 20px;
  font-size: 16px;
}
</style>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'AboutView',
  components: {
    HelloWorld
  }
}
</script>
    