<nav>
  <ul>
    <li>
      <img
        src="/src/routes/libs/svg/1-removebg-preview.png"
        alt="logo"
        class="logo"
      />
    </li>
    <a href="https://google.com"><li>Home</li></a>
    <button class="nav-toggle">
      <svg
        class="hamburger d-lg-none"
        viewBox="0 0 48 32"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M24 32H0V26.6667H24V32ZM48 18.6667H0V13.3333H48V18.6667ZM48 5.33333H24V0H48V5.33333Z"
          fill="#7fa0a1"
        />
      </svg>
    </button>
    <li>About</li>
    <li>Products</li>
    <li>Team</li>
    <li>Blog</li>
  </ul>

  <ul>
    <li>
      <a href="https://forms.google.com/" role="button" class="outline"
        >Join Now</a
      >
    </li>
  </ul>
</nav>

<style>
  nav {
    /* background: rgb(255, 0, 0);
    background: linear-gradient(
      90deg,
      rgba(255, 0, 0, 1) 0%,
      rgba(255, 153, 51, 1) 99%
    ); */
    color: black;
    height: 10vh;
    background: #ffffff;
  }

  nav > ul {
    display: flex;
    flex-direction: row;
  }

  img {
    width: 5em;
    height: 5em;
  }

  button {
    background: white;
    height: 3em;
    width: 3em;
  }
</style>
