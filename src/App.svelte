<script>
  import Badge from "./Componentes/Badge.svelte";
  import Button from "./Componentes/Button.svelte";
  import Footer from "./Componentes/Footer.svelte";
  import Card from "./Componentes/Card.svelte";
  import Notification from "./Componentes/Notification.svelte";
  import Avatar from "./Componentes/Avatar.svelte";
</script>

<main>
  <h1>Designsystem</h1>

  <section>
    <h2>Badge</h2>

    <article>
      <Badge type="neutral">neutral</Badge>

      <pre><code>          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="neutral" &gt; neutral &lt;/Badge&gt;
</code></pre>
    </article>

    <article>
      <Badge type="primary">Primary</Badge>

      <pre><code>
          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="primary" &gt; Primary &lt;/Badge&gt;
</code></pre>
    </article>

    <article>
      <Badge type="secondary">Secondary</Badge>
      <pre><code          >&lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="secondary" &gt; Secondary &lt;/Badge&gt;
</code></pre>
    </article>

    <article>
      <Badge type="accent">accent</Badge>

      <pre><code>
          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="accent" &gt; accent &lt;/Badge&gt;
</code></pre>
    </article>

    <article>
      <Badge type="ghost">ghost</Badge>

      <pre><code>
          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="ghost" &gt; ghost &lt;/Badge&gt;
</code></pre>
    </article>
  </section>

  <h2>Button component</h2>
  <div class="display">
    <Button type="neutral">Default</Button>
    <Button type="primary">Primary</Button>
    <Button type="secondary">Secondary</Button>
    <Button type="accent">Accent</Button>
    <Button type="ghost">Ghost</Button>
    <Button type="link"><a href="##">Link</a></Button>
  </div>

  <h2>Footer component</h2>
  <Footer />

  <h2>Card Component</h2>
  <Card>Fashion</Card>

  <h2>Avatar component</h2>
  <div class="display">
    <Avatar>K</Avatar>
    <Avatar size="l">K</Avatar>
  </div>

  <h2>notification component</h2>
  <Notification />
</main>

<style>
  .display {
    display: flex;
    gap: 1rem;
    padding: 1rem;
    align-items: center;
  }
</style>
