<script>
  export let size = "xl";
</script>

<div class={size}><p><slot /></p></div>

<style>

div{
    width: 40px;
    height: 40px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background: var(--neutral-color);
    color: var(--font-primary-color);
}

  .xl {
   
    border-radius: 50%;
    padding: 3rem;
    margin: 1rem;
   
  
  }
  p {
    
    font-size: 2rem;
    align-self: center;
  }

  .l {
    border-radius: 50%;
    padding: 2rem;
    margin: 1rem;
    font-size: 1rem;
 
  
  }
</style>
