<script>
  import Button from "./Button.svelte";
  import Badge from "./Badge.svelte";
</script>

<div class="notification">
  <span><Button type="neutral">Inbox</Button></span>
  <span class="mark"><Badge type="secondary">99+</Badge></span>
</div> 

   
<style>
  .notification {
  position: relative;
  display: inline-block;
}


.notification .mark {
  position: absolute;
  top: -8px;
  right: -20px;
  
}
</style>
