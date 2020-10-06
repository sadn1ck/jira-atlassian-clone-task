<template>
  <header
    class="lg:px-16 px-6 bg-white flex flex-wrap items-center lg:py-0 py-2 sticky top-0 shadow-lg"
  >
    <div class="flex-1 flex justify-between items-center">
      <a href="#">
        <img
          src="https://wac-cdn.atlassian.com/dam/jcr:e348b562-4152-4cdc-8a55-3d297e509cc8/Jira%20Software-blue.svg?cdnVersion=1280"
          alt=""
          style="height:20px"
        />
      </a>
    </div>

    <label for="menu-toggle" class="pointer-cursor lg:hidden block"
      ><svg
        class="fill-current text-gray-900"
        xmlns="http://www.w3.org/2000/svg"
        width="20"
        height="20"
        viewBox="0 0 20 20"
      >
        <title>menu</title>
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path></svg
    ></label>
    <input class="hidden" type="checkbox" id="menu-toggle" />

    <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
      <nav>
        <ul
          class="lg:flex items-center justify-between text-base text-gray-700 pt-4 lg:pt-0"
        >
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >Features</a
            >
          </li>
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >Product Guide</a
            >
          </li>
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >Pricing</a
            >
          </li>
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400 lg:mb-0 mb-2"
              href="#"
              >Enterprise</a
            >
          </li>
        </ul>
      </nav>
      <a
        href="#"
        class="lg:ml-4 flex items-center justify-start lg:mb-0 mb-4 pointer-cursor"
      >
        <button class="bg-indigo-600 text-white rounded p-3">
          Get it free
        </button>
      </a>
    </div>
  </header>
</template>
<script>
export default {};
</script>

<style>
#menu-toggle:checked + #menu {
  display: block;
}
</style>