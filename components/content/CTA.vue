<template>
  <div class="text-gray-700 body-font force-center cta">
    <div class="px-5 py-24 text-center">
      <h1 class="text-4xl font-bold py-5 title-font text-white">
        Streamline your work with automation
      </h1>
      <p class="text-white">
        Save time, stay focused and work smarter with Jira automation.
      </p>
      <button
        class="text-white bg-indigo-500 border-0 my-5 py-3 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg"
      >
        Learn more about automation
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.cta {
  background-color: #172b4d;
}
@media (min-width: 768px) and (max-width: 1023px) {
  .cta {
    background-image: url("https://wac-cdn.atlassian.com/dam/jcr:e1b033e1-4d7d-46a3-995c-2a55731e800b/automation-banner-L%20768.svg?cdnVersion=1280"),
      url("https://wac-cdn.atlassian.com/dam/jcr:43f0949b-f655-4d01-bc18-258b25c74912/automation-banner-R%20768.svg?cdnVersion=1280");
    background-position: left center, right center;
    background-repeat: no-repeat, no-repeat;
    background-size: auto 100%, auto 100%;
  }
}
@media (min-width: 1024px) and (max-width: 1439px) {
  .cta {
    background-image: url("https://wac-cdn.atlassian.com/dam/jcr:efd533a9-0494-4b71-9c49-425525a7da97/automation-banner-L%201024.svg?cdnVersion=1280"),
      url("https://wac-cdn.atlassian.com/dam/jcr:fda286e4-106a-4c37-a80e-08818adad41d/automation-banner-R%201024.svg?cdnVersion=1280");
    background-position: left center, right center;
    background-repeat: no-repeat, no-repeat;
    background-size: auto 100%, auto 100%;
  }
}
@media (min-width: 1440px) {
  .cta {
    background-image: url("https://wac-cdn.atlassian.com/dam/jcr:4598ed32-5d28-4506-92d2-0a815556e2e4/automation-banner-L.svg?cdnVersion=1280"),
      url("https://wac-cdn.atlassian.com/dam/jcr:6bfbb10d-d747-40dc-8f31-28383f896f33/automation-banner-R.svg?cdnVersion=1280");
    background-position: left center, right center;
    background-repeat: no-repeat, no-repeat;
    background-size: auto 100%, auto 100%;
  }
}
</style>