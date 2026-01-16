<header class="header">
  <nav class="nav">
    <a href="/" class="nav-left">OMMI</a>
    <div class="nav-right">
      <a href="/">Home</a>
      <a href="/about">About Us</a>
      <a href="/curriculum">Curriculum</a>
      <a href="/tuition-fees">Tuition/Fees</a>
      <a href="/student-clinic">Student Clinic</a>
      <a href="/contact">Contact Us</a>
    </div>
  </nav>
</header>

<main style="flex-grow: 1;">
  <slot />
</main>

<footer class="footer">
  <p>Made with ♥ by Joshua Francis</p>
</footer>

<style>
  :root {
    --color-dark: #333;
    --color-light-background: #EFFDF9;
    --color-background-light: #ffffff;
    --color-accent: #A0AC94;
    --color-accent-blue: #93B8C1;
    --color-text-light: #ffffff;
  }

  .header {
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  .nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: var(--color-dark); /* #333 Alternatively #A0AC94 or #93B8C1 but those seem too light now. */
    padding: 1em;
  }

  .nav-left {
    color: var(--color-text-light);
    padding: 0.5em 1em;
    text-decoration: none;
    border: 1px solid var(--color-text-light);
    font-weight: bold;
  }

  .nav-right a {
    color: var(--color-text-light);
    padding: 1em;
    text-decoration: none;
  }

  .footer {
    background-color: var(--color-dark); /* Match header or choose a complementary color */
    color: var(--color-text-light);
    padding: 1em;
    text-align: center;
    width: 100%;
  }
</style>