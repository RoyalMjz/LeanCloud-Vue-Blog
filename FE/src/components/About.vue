<template>
  <div class="about-wrapper">
    <h2 class="list-title">槑头脑</h2>
    <p>iOS Developer</p>
    <a href="https://github.com/RoyalMjz">Github</a>
    <a href="http://weibo.com/u/3810450792">微博</a>
  </div>
</template>

<script type="text/babel">
  import { updateHeadline } from '../vuex/actions'
  export default {
    vuex: {
      actions: {
        updateHeadline: updateHeadline
      }
    },
    created () {
      this.updateHeadline('关于')
    }
  }
</script>

<style>
  .about-wrapper {
    width: 80%;
    padding: 1rem;;
  }

  .about-wrapper a {
    color: #4078c0;
    display: block;
    transition: all .4s;
  }

  .about-wrapper a:hover {
    color: #80b2ff;
  }

  .about-wrapper p, .about-wrapper h2, .about-wrapper a {
    margin: 1rem auto;
  }

  .about-wrapper p {
    font-size: 1.8rem;
  }

  .about-wrapper a {
    font-size: 1.6rem;
  }

  @media screen and (max-width: 768px) {
    .about-wrapper p {
      font-size: 1.6rem;
    }

  }
</style>
