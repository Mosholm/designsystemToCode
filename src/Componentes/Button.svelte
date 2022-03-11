<script>
export let type = "neutral";
</script>

<button class={type}><slot/></button>

<style>
button{
    color: var(--font-primary-color);
    padding: 1rem;
    text-transform: uppercase;
    font-weight: 700;
    border: none;
    border-radius: 8px;
    transition: all 0.4s;
}

.neutral{
    background: var(--neutral-color);
}
.neutral:hover{
    background: var(--neutral-color-hover);
}

  .primary {
    background:var(--primary-color);
  }

  .primary:hover {
    background:var(--primary-color-hover);
  }

  .secondary {
      background: var(--secondary-color);
  }

  .secondary:hover {
      background: var(--secondary-color-hover);
  }

  .accent {
      background: var(--accent-color);
  }

  .accent:hover {
      background: var(--accent-color-hover);
  }

  .ghost {
      background: none;
      color: var(--font-ghost-color);
  }

  .ghost:hover {
      background: none;
      color: var(--neutral-color-hover);
  }

  .link {
      background: none;
      color: var(--primary-color);
  }
</style>
