<nav>
  <ul>
    <li><img src="libs/svg/logo.svg" alt="logo" /></li>
    <a href="#"><li>Home</li></a>
    <li>About</li>
    <li>Products</li>
    <li>Team</li>
    <li>Blog</li>
  </ul>

  <ul>
    <li><a href="#" role="button" class="outline">Join Now</a></li>
  </ul>
</nav>

<main>
  <section class="hero">
    <h1>Your Daily Dose of Positivity</h1>
    <p>Be happy, for once.</p>
  </section>
</main>

<style>
  section.hero {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .hero {
    background: rgb(255, 0, 0);
    background: linear-gradient(
      90deg,
      rgba(255, 0, 0, 1) 0%,
      rgba(255, 153, 51, 1) 99%
    );
    color: white;
    text-align: center;
  }
  .hero > p {
    color: white;
  }
  nav {
    background: rgb(255, 0, 0);
    background: linear-gradient(
      90deg,
      rgba(255, 0, 0, 1) 0%,
      rgba(255, 153, 51, 1) 99%
    );
    color: white;
  }
</style>
