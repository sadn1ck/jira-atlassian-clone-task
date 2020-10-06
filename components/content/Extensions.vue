<template>
  <section class="text-gray-700 body-font">
    <div
      class="container mx-auto flex px-5 py-8 lg:py-24 md:flex-row flex-col items-center px-16"
    >
      <div class="lg:max-w-lg lg:w-full  md:w-1/2 w-5/6 mb-10 md:mb-0 force-center">
        <img
          class="object-cover object-center rounded shadow-2xl"
          alt="hero"
          src="https://wac-cdn.atlassian.com/dam/jcr:5ea2fadd-0605-4c16-a464-a85e342f5918/build-atlassian.png?cdnVersion=1280"
          style="height: 150px"
        />
      </div>
      <div
        class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center"
      >
        <h1 class="title-font sm:text-4xl text-xl mb-4 font-bold text-gray-900">
          Extend Jira Software with apps
        </h1>
        <p class="mb-8 leading-relaxed">
          Tempo Timesheets, Zephyr, and over 3,000 other apps ensure Jira
          Software can be custom tailored to fit any and every use case.
        </p>
      </div>
    </div>
    <div class="apps" style="min-height: 150px"></div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.apps {
  background-image: url("https://wac-cdn.atlassian.com/dam/jcr:ae6a494b-edfe-484f-a106-4539e348377b/marketplace%20section-update.svg?cdnVersion=1280");
  background-position: bottom;
  background-repeat: no-repeat;
  background-size: auto;
}
</style>