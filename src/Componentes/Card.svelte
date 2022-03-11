<script>
  import Badge from "./Badge.svelte";
  import Button from "./Button.svelte";
</script>

<div class="Card">
  <img src="https://placebear.com/400/200" alt="" />
  <div class="header">
    <h2>Title</h2>
    <Badge type="secondary">New</Badge>
  </div>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius sed expedita,
    enim cumque magnam amet?
  </p>

  <div class="tag">
    <Badge type="tag">Fashion</Badge>
    <Badge type="tag">Products</Badge>
  </div>
  <div class="btn">
    <Button type="primary">Buy now</Button>
  </div>
</div>

<style>
  .Card {
    max-width: 300px;
    margin: 1rem;
    border-radius: 12px;
    -webkit-box-shadow: 4px 8px 7px -1px rgba(114, 114, 114, 0.47);
    box-shadow: 4px 8px 7px -1px rgba(114, 114, 114, 0.47);
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  img {
    border-top-left-radius: 12px;
    border-top-right-radius: 12px;
    width: 100%;
  }

  .header {
    display: flex;
    align-items: baseline;
    gap: 1rem;
    padding: 0 1rem;
  }

  h2 {
    font-size: 0.9rem;
    line-height: 1rem;
  }

  p {
    font-size: 0.8rem;
    padding: 0 1rem;
  }

  .tag {
    padding: 0 1rem;
  }

  .btn {
    align-self: flex-end;
    padding: 0 1rem 1rem 0;
  }
</style>
