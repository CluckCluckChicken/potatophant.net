<template>
  <div class="container">
    <Logo />
      <h1 class="text-7xl font-sans">
        potatophant
      </h1>
      <div class="flex flex-row">
        <a href="https://scratch.mit.edu/users/potatophant/" class="transition duration-200 ease-out transform hover:scale-110 hover:bg-blue-500 text-blue-500 hover:text-white font-sans text-4xl rounded-xl px-8 py-4 mt-4">
          Scratch
        </a>
        <a href="https://github.com/CluckCluckChicken" class="transition duration-200 ease-out transform hover:scale-110 hover:bg-gray-800 text-gray-800 hover:text-white font-sans text-4xl rounded-xl px-8 py-4 mt-4">
          GitHub
        </a>
        <a href="https://magnifier.potatophant.net/" class="transition duration-200 ease-out transform hover:scale-110 hover:bg-green-600 text-green-600 hover:text-white font-sans text-4xl rounded-xl px-8 py-4 mt-4">
          Magnifier
        </a>
      </div>
    <NuxtChild />
  </a>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
