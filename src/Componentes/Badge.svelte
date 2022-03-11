<script>
    export let type = "neutral";
    </script>
    
    <span class={type}><slot/></span>
    
    <style>
    span{
        color: var(--font-primary-color);
        padding:0.1rem 1rem;
       
        font-size: 0.7em;
        font-weight: 500;
        border: none;
        border-radius: 12px;
    }
    
    .neutral{
        background: var(--neutral-color);
    }

    
      .primary {
        background:var(--primary-color);
      }
    

    
      .secondary {
          background: var(--secondary-color);
      }
    
 
    
      .accent {
          background: var(--accent-color);
      }
    

    
      .ghost {
          background: var(--font-primary-color);
          color: var(--font-ghost-color);
      }

      .tag {
          background: var(--font-primary-color);
          color: black;
          border: 1px solid black
      }
    
    
    </style>
    