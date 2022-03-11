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

      <pre><code>          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="primary" &gt; Primary &lt;/Badge&gt;
</code></pre>
    </article>
    <article>
      <Badge type="secondary">secondary</Badge>

      <pre><code>          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="secondary" &gt; secondary &lt;/Badge&gt;
</code></pre>
    </article>
    <article>
      <Badge type="accent">accent</Badge>

      <pre><code>          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="accent" &gt; accent &lt;/Badge&gt;
</code></pre>
    </article>
    <article>
      <Badge type="ghost">ghost</Badge>

      <pre><code>          &lt;script&gt;
            import Badge from "./Componentes/Badge.svelte";
          &lt;/script&gt;
          
          &lt;Badge type="ghost" &gt; ghost &lt;/Badge&gt;
</code></pre>
    </article>
  </section>

  <section>
    <h2>Button component</h2>

    <article>
      <Button type="neutral">Default</Button>
      <pre><code>        &lt;script&gt;
          import Button from "./Componentes/Button.svelte";
        &lt;/script&gt;
        
        &lt;Button type="neutral"&gt; neutral &lt;/Button&gt;
</code></pre>
    </article>
    <article>
      <Button type="primary">primary</Button>
      <pre><code>        &lt;script&gt;
          import Button from "./Componentes/Button.svelte";
        &lt;/script&gt;
        
        &lt;Button type="primary"&gt; primary &lt;/Button&gt;
</code></pre>
    </article>

    <article>
      <Button type="secondary">secondary</Button>
      <pre><code>        &lt;script&gt;
          import Button from "./Componentes/Button.svelte";
        &lt;/script&gt;
        
        &lt;Button type="secondary"&gt; secondary &lt;/Button&gt;
</code></pre>
    </article>

    <article>
      <Button type="accent">accent</Button>
      <pre><code>        &lt;script&gt;
          import Button from "./Componentes/Button.svelte";
        &lt;/script&gt;
        
        &lt;Button type="accent"&gt; accent &lt;/Button&gt;
</code></pre>
    </article>

    <article>
      <Button type="ghost">ghost</Button>
      <pre><code>        &lt;script&gt;
          import Button from "./Componentes/Button.svelte";
        &lt;/script&gt;
        
        &lt;Button type="ghost"&gt; ghost &lt;/Button&gt;
</code></pre>
    </article>

    <article>
      <Button type="link">link</Button>
      <pre><code>        &lt;script&gt;
          import Button from "./Componentes/Button.svelte";
        &lt;/script&gt;
        
        &lt;Button type="link"&gt; link &lt;/Button&gt;
</code></pre>
    </article>
  </section>

  <section>
    <h2>Footer component</h2>
    <article>
      <Footer />
      <pre><code>    &lt;script&gt;
      import Footer from "./Componentes/Footer.svelte";
    &lt;/script&gt;
    
    &lt;Footer /&gt;
</code></pre>
    </article>
  </section>

  <section>
    <h2>Card Component</h2>

    <article>
      <Card />

      <pre><code>    &lt;script&gt;
        import Card from "./Componentes/Card.svelte";
      &lt;/script&gt;
      
      &lt;Card /&gt;
  </code></pre>
    </article>
  </section>

  <section>
    <h2>Avatar component</h2>
    <article>
      <Avatar>XL</Avatar>

      <pre><code>    &lt;script&gt;
        import Avatar from "./Componentes/Avatar.svelte";
      &lt;/script&gt;
      
      &lt;Avatar&gt; XL &lt;/Avatar&gt;
  </code></pre>
    </article>

    <article>
      <Avatar size="l">L</Avatar>

      <pre><code>    &lt;script&gt;
        import Avatar from "./Componentes/Avatar.svelte";
      &lt;/script&gt;
      
      &lt;Avatar size="l"&gt; L &lt;/Avatar&gt;
  </code></pre>
    </article>

    <article>
      <Avatar size="m">M</Avatar>

      <pre><code>    &lt;script&gt;
        import Avatar from "./Componentes/Avatar.svelte";
      &lt;/script&gt;
      
      &lt;Avatar size="M"&gt; M &lt;/Avatar&gt;
  </code></pre>
    </article>

    <article>
      <Avatar size="s" mode="active">S</Avatar>

      <pre><code>    &lt;script&gt;
        import Avatar from "./Componentes/Avatar.svelte";
      &lt;/script&gt;
      
      &lt;Avatar size="s" mode="active"&gt; S &lt;/Avatar&gt;
  </code></pre>
    </article>
  </section>

  <section>
    <h2>notification component</h2>
    <article>
      <Notification />

      <pre><code>      &lt;script&gt;
        import Notification from "./Componentes/Notification.svelte";
      &lt;/script&gt;
      
      &lt;Notification /"&gt;
  </code></pre>
    </article>
  </section>
</main>

<style>
</style>
