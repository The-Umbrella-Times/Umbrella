<!-- navbar -->
<nav id="nav">
  <div class="nav-center">
    <!-- nav header -->
  </div>
  <!-- links -->
  <div class="links-container">
    <ul class="links">
      <li>
        <a href="#home" class="scroll-link">home</a>
      </li>
      <li>
        <a href="#about" class="scroll-link">about</a>
      </li>
      <li>
        <a href="#services" class="scroll-link">services</a>
      </li>
      <li>
        <a href="#tours" class="scroll-link">tours</a>
      </li>
    </ul>
    <div class="nav-header">
      <img
        src="/src/routes/libs/svg/1-removebg-preview.png"
        class="logo"
        alt="logo"
      />
      <button class="nav-toggle">
        <svg
          class="hamburger d-lg-none"
          viewBox="0 0 48 32"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M24 32H0V26.6667H24V32ZM48 18.6667H0V13.3333H48V18.6667ZM48 5.33333H24V0H48V5.33333Z"
            fill="#000000"
          />
        </svg>
      </button>
    </div>
  </div>
</nav>

<style>
  :root {
    /* dark shades of primary color*/
    --clr-primary-1: hsl(205, 86%, 17%);
    --clr-primary-2: hsl(205, 77%, 27%);
    --clr-primary-3: hsl(205, 72%, 37%);
    --clr-primary-4: hsl(205, 63%, 48%);
    /* primary/main color */
    --clr-primary-5: #49a6e9;
    /* lighter shades of primary color */
    --clr-primary-6: hsl(205, 89%, 70%);
    --clr-primary-7: hsl(205, 90%, 76%);
    --clr-primary-8: hsl(205, 86%, 81%);
    --clr-primary-9: hsl(205, 90%, 88%);
    --clr-primary-10: hsl(205, 100%, 96%);
    /* darkest grey - used for headings */
    --clr-grey-1: hsl(209, 61%, 16%);
    --clr-grey-2: hsl(211, 39%, 23%);
    --clr-grey-3: hsl(209, 34%, 30%);
    --clr-grey-4: hsl(209, 28%, 39%);
    /* grey used for paragraphs */
    --clr-grey-5: hsl(210, 22%, 49%);
    --clr-grey-6: hsl(209, 23%, 60%);
    --clr-grey-7: hsl(211, 27%, 70%);
    --clr-grey-8: hsl(210, 31%, 80%);
    --clr-grey-9: hsl(212, 33%, 89%);
    --clr-grey-10: hsl(210, 36%, 96%);
    --clr-white: #000;
    --clr-red-dark: hsl(360, 67%, 44%);
    --clr-red-light: hsl(360, 71%, 66%);
    --clr-green-dark: hsl(125, 67%, 44%);
    --clr-green-light: hsl(125, 71%, 66%);
    --clr-secondary: hsla(182, 63%, 54%);
    --clr-black: #222;
    --transition: all 0.3s linear;
    --spacing: 0.25rem;
    --radius: 0.5rem;
    --light-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    --dark-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    --max-width: 1170px;
    --fixed-width: 620px;
  }

  nav {
    background: white;
    /*padding: 1rem 1.5rem; */
  }
  /* fixed nav */
  .fixed-nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background: white;
    box-shadow: var(--light-shadow);
  }
  .fixed-nav .links a {
    color: var(--clr-grey-1);
  }
  .fixed-nav .links a:hover {
    color: var(--clr-secondary);
  }
  /* .fixed-nav .links-container {
  height: auto !important;
} */
  .nav-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .nav-toggle {
    font-size: 1.5rem;
    color: var(--clr-grey-1);
    background: transparent;
    border-color: transparent;
    transition: var(--transition);
    cursor: pointer;
  }
  .nav-toggle:hover {
    color: var(--clr-secondary);
  }
  .logo {
    height: 50px;
  }
  .links-container {
    height: 0;
    overflow: hidden;
    transition: var(--transition);
  }
  .show-links {
    height: 200px;
  }
  .links a {
    background: var(--clr-white);
    color: var(--clr-grey-5);
    font-size: 1.1rem;
    text-transform: capitalize;
    letter-spacing: var(--spacing);
    display: block;
    transition: var(--transition);
    font-weight: bold;
    padding: 0.75rem 0;
  }
  .links a:hover {
    color: var(--clr-grey-1);
  }
  @media screen and (min-width: 800px) {
    nav {
      background: transparent;
    }
    .nav-center {
      width: 90vw;
      max-width: 1170px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .nav-header {
      padding: 0;
    }
    .nav-toggle {
      display: none;
    }
    .links-container {
      height: auto !important;
    }
    .links {
      display: flex;
    }
    .links a {
      background: transparent;
      color: var(--clr-white);
      font-size: 1.1rem;
      text-transform: capitalize;
      letter-spacing: var(--spacing);
      display: block;
      transition: var(--transition);
      margin: 0 1rem;
      font-weight: bold;
      padding: 0;
    }
    .links a:hover {
      color: var(--clr-white);
    }
  }
</style>
