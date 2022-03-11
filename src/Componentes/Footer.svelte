<script>
</script>

<footer>
  <ul>
    <h3>Service</h3>
    <li>Branding</li>
    <li>Design</li>
    <li>Marketing</li>
    <li>Advertisement</li>
  </ul>

  <ul>
    <h3>Company</h3>
    <li>About us</li>
    <li>Contact</li>
    <li>Jobs</li>
    <li>Press kit</li>
  </ul>

  <ul>
    <h3>Legal</h3>
    <li>Terms of use</li>
    <li>Privacy policy</li>
    <li>Cookie policy</li>
  </ul>
</footer>

<style>
  footer {
    display: grid;
    grid-template-columns: repeat( auto-fill, minmax(200px, 1fr) );
    background: var(--neutral-color);
    padding: 2rem;
    color: var(--font-primary-color);
    font-size: 0.9rem;
    width: 100%;
    min-width: 60vw;
  }

  h3 {
      text-transform: uppercase;
      color: var(--neutral-color-hover);
      margin: 1.5em 0 0.8em 0;
  }

  ul{
      list-style: none;
      line-height: 1.3rem;
  }
</style>
