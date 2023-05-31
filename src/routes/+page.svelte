<script>
  import Nav from "./Nav.svelte";
</script>

<header>
  <Nav />
</header>
<body>
  <section class="hero">
    <h1>Your Daily Dose of Positivity</h1>
    <p>Be happy, for once.</p>
  </section>
</body>

<!-- <div class="custom-shape-divider-bottom-1685375161"> -->
<!--   <svg -->
<!--     data-name="Layer 1" -->
<!--     xmlns="http://www.w3.org/2000/svg" -->
<!--     viewBox="0 0 1200 120" -->
<!--     preserveAspectRatio="none" -->
<!--   > -->
<!--     <path d="M1200 120L0 16.48 0 0 1200 0 1200 120z" class="shape-fill" /> -->
<!--   </svg> -->

<!-- </div> -->
<style>
  html,
  body {
    background: white;
  }
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

  .custom-shape-divider-bottom-1685375161 {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    transform: rotate(180deg);
  }

  .custom-shape-divider-bottom-1685375161 svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 100px;
  }

  .custom-shape-divider-bottom-1685375161 .shape-fill {
    fill: #ffffff;
  }
</style>
