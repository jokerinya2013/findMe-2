<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}

body {
  margin: 0;
}

header {
  background: #36007c;
  width: 100%;
  height: 4rem;
  display: flex;
  justify-content: center;
  align-items: center;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.26);
}

header h1 {
  font-size: 2rem;
  color: white;
  margin: 0;
}

button {
  font: inherit;
  font-size: 1.25rem;
  background: #36007c;
  color: white;
  border: 1px solid #36007c;
  border-radius: 6px;
  padding: 0.5rem 1.5rem;
  margin: 0.5rem 0;
  cursor: pointer;
}

button:focus {
  outline: none;
}

button:hover,
button:active {
  background: #55007c;
  border-color: #55007c;
}

button:disabled,
button:disabled:hover,
button:disabled:active {
  background: #ccc;
  color: #9b9b9b;
  border-color: #ccc;
  cursor: not-allowed;
}

@media (min-width: 768px) {
  .modal {
    left: calc(50% - 15rem);
    width: 30rem;
  }
}
</style>
