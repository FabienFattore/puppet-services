<script>
    let isOpen = false;
  
    function toggleMenu() {
      isOpen = !isOpen;
    }
  </script>
  
  <button on:click={toggleMenu}>Menu</button>
  {#if isOpen}
    <div class="mobile-menu">
      <ul>
        <li>Option 1</li>
        <li>Option 2</li>
        <li>Option 3</li>
      </ul>
    </div>
  {/if}
  
  <style>
    .mobile-menu {
      display: {isOpen ? 'block' : 'none'};
      /* Ajoutez d'autres styles de menu mobile ici, par exemple, pour le positionnement, les couleurs, etc. */
    }
  </style>
  