<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=IBM+Plex+Sans:300,400,700&display=swap");

body {
  font-family: "IBM Plex Sans", sans-serif;
  box-sizing: border-box;
  margin: 0 auto;
  word-break: break-word;
  font-kerning: auto;
  font-variant: normal;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-rendering: optimizeLegibility;
  display: flex;
  flex-direction: column;
  background-color: #274c77;
}

div {
  box-sizing: border-box;
}

h1 {
  font-weight: bold;
  color: #191716;
  letter-spacing: -1.4px;
  margin-bottom: 0;
  margin-top: 0;
  font-size: 2rem;
}

h2 {
  font-weight: 300;
  color: #191716;
  letter-spacing: -1px;
  border-bottom: 0.375rem solid #f4d35e;
  padding-bottom: 0.75rem;
  margin-bottom: 0;
  margin-top: 0;
  align-self: flex-start;
  font-size: 1.5rem;
}

p {
  color: #191716;
  letter-spacing: -0.26px;
  margin-top: 2rem;
  line-height: 32px;
  font-size: 1rem;
}

.main-container {
  display: flex;
  flex-direction: column;
  padding-bottom: 1.5rem;
  background-color: white;
}

.secondary-container {
  background-color: #274c77;
}

.hero {
  display: flex;
  flex: 1;
  flex-direction: column;
  padding: 6rem 2rem 2rem 2rem;
}

.contact {
  display: flex;
  flex-direction: column;
  flex: 1;
  padding-left: 2rem;
}

.description {
  max-width: 33rem;
}

.contact-item {
  font-size: 1rem;
  font-weight: bold;
  text-decoration: none;
  color: #191716;
  display: flex;
  align-items: center;
  margin-top: 2rem;
}

.contact-item .fab,
.contact-item .fas {
  font-size: 1.5rem;
  margin-right: 0.75rem;
}

.contact-item:hover {
  color: #2274a5;
}

@media (min-width: 768px) {
  .main-container {
    flex-direction: row;
    padding-bottom: 0;
  }

  .hero {
    padding: 10rem 6rem 6rem 6rem;
  }

  .contact {
    justify-content: center;
  }
}

@media (min-width: 1024px) {
  h1 {
    font-size: 4rem;
  }

  h2 {
    font-size: 3rem;
    border-bottom: 0.75rem solid #f4d35e;
  }

  p {
    line-height: 44px;
    font-size: 1.25rem;
  }

  .contact {
    justify-content: center;
    padding-left: 0;
  }

  .contact-item {
    font-size: 1.25rem;
  }

  .contact-item .fab,
  .contact-item .fas {
    font-size: 2rem;
  }
}
</style>
