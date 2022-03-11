<script>
  import Button from "./Button.svelte";
  import Badge from "./Badge.svelte";
</script>

<div>
  <div class="wrapper">
    <div class="btn">
      <Button type="neutral">Inbox</Button>
    </div>
    <div class="notification">
      <Badge type="secondary">99+</Badge>
    </div>
  </div>
</div>

<style>
  .wrapper {
    display: inline-block;
  }

  .btn {
    position: absolute;
  }

  .notification {
    position: relative;
    left: 90%;
    top: -8px;
  }
</style>
