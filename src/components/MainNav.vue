<template>
  <header class="w-full text-sm">
    <div class="fixed top-0 left-0 w-full h-16 bg-white">
      <div
        class="flex flex-nowrap h-full px-8 mx-auto border-b border-solid border-brand-gray-1"
      >
        <a :href="url" class="flex items-center text-xl h-full">{{
          companyName
        }}</a>

        <nav class="h-full ml-12">
          <ul class="flex h-full p-0 m-0 list-none">
            <li class="h-full mr-9">
              <a href="" class="flex h-full items-center py-2.5">Teams</a>
            </li>
            <li class="h-full mr-9">
              <a href="" class="flex h-full items-center py-2.5">Locations</a>
            </li>
            <li class="h-full mr-9">
              <a href="" class="flex h-full items-center py-2.5"
                >Life at Fettah Company</a
              >
            </li>
            <li class="h-full mr-9">
              <a href="" class="flex h-full items-center py-2.5">How we hire</a>
            </li>
            <li class="h-full">
              <a href="" class="flex h-full items-center py-2.5">Students</a>
            </li>
            <li class="h-full">
              <a href="" class="flex h-full items-center py-2.5">Jobs</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: "MainNav",
  data() {
    return {
      companyName: "Fettah",
      url: "www.carrers.google.com",
    };
  },
};
</script>
