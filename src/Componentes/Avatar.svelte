<script>
  export let size = "xl";
  export let mode;
</script>

<div class="avatar">
  <span class={size}><p><slot/></p></span>
  <span class:active={mode === "active"} />
</div>

<style>
  .avatar {
    background-color: #555;
    color: white;
    padding: 1.3rem;
    text-decoration: none;
    position: relative;
    display: inline-block;
    border-radius: 50%;
  }
  .xl {
    font-size: 3rem;

  }

  .l {
    font-size: 2rem;
  }

  .m {
    font-size: 1rem;
  }

  .s {
    font-size: 0.5rem;
  }

  p {
    text-align: center;
  }

  .avatar .active {
    position: absolute;
    top: -5px;
    right: -5px;
    width: 20px;
    min-height: 20px;
    border-radius: 50%;
    background: rgb(10, 121, 0);
    border: 2px solid white;
    color: white;
  }
</style>
