<nav>
  <a href="/">Home</a>
  <a href="/about">About Us</a>
  <a href="/curriculum">Curriculum</a>
  <a href="/tuition-fees">Tuition/Fees</a>
  <a href="/student-clinic">Student Clinic</a>
  <a href="/contact">Contact Us</a>
</nav>

<main>
  <slot></slot>
</main>

<style>
  nav {
    display: flex;
    justify-content: center;
    background-color: #333;
    padding: 1em;
  }

  a {
    color: white;
    padding: 1em;
    text-decoration: none;
  }
</style>