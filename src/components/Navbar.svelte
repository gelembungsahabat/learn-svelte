<style>
  .navbar {
    position: fixed;
    opacity: 0.8;
    background-color: #333;
    top: 0;
    left: 0;
    z-index: 9899;
    width: 100%;
    height: 55px;
  }

  ul {
    list-style-type: none;
    margin-top: 0px;
    margin-left: 0px;
    padding: 0;
    overflow: hidden;
  }

  li {
    float: left;
  }

  li a {
    display: block;
    color: white;
    text-align: center;
    padding: 18px 20px;
    text-decoration: none;
  }

  li a:hover:not(.active) {
    background-color: #111;
  }
  /* 
  @screen sm {
    .navbar {
      background-color: #111;
    }
  }

  @screen md {
    .navbar {
      @apply bg-blue-100;
    }
  } */
</style>

<div class="navbar">
  <ul>
    <li>
      <a href="/">HOME</a>
    </li>
    <li>
      <a href="/about">ABOUT</a>
    </li>
  </ul>
</div>
