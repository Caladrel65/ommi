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

<main>
  <slot />
</main>

<style>
  .nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    padding: 1em;
  }

  .nav-left {
    color: white;
    padding: 0.5em 1em;
    text-decoration: none;
    border: 1px solid white;
    font-weight: bold;
  }

  .nav-right a {
    color: white;
    padding: 1em;
    text-decoration: none;
  }
</style>