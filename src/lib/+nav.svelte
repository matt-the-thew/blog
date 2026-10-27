<nav>
  <div class="title">
    <h1 class="title">Matt Morton's Blog</h1>
    <sub>v0.1.0</sub>
  </div>
  <div class="pages">
    <a href="#">blog</a>
    <a href="#">projects</a>
  </div>
</nav>

<style>
  nav {
    background-color: #000;
    margin: 0;
    padding: 0 5rem;

    display: flex;
    justify-content: space-between;

    font-family: var(--font);
  }

  .title {
    color: var(--primary);
    display: flex;
  }

  sub {
    padding-top: 15%;
    color: var(--accent);
  }

  .pages {
    display: flex;
    gap: 1rem;
    align-items: center;
  }

  a {
    color: #f3f3f3;
    text-decoration: none;
    font-size: 1.2rem;

    padding: 0.5rem;
  }

  a:hover {
    color: var(--accent);
    transition-duration: 100ms;
  }
</style>
