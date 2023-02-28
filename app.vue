<template>
  <div class="wrapper">
    <p>ScratchLo</p>
  </div>
  hello
  <component is="style" scoped>
      .wrapper {
        position: sticky;
        top: 0;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        flex-wrap: nowrap;
        box-sizing: border-box;
        height: 3rem;
        font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        font-size: 0.75rem;
        font-weight: bold;
        background-color: var(--header-background);
        color: white;
        border-bottom: 1px solid rgba(0, 0, 0, 0.1);
        box-shadow: 0 0 3px rgb(0 0 0 / 25%);
        overflow: auto;
        scrollbar-width: none;
        z-index: 10;
    }
  </component>
</template>
